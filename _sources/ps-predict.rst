Prediction
-----------------------------------------------------

Read the code below and then answer the following question.

.. code-block:: python

      # set the initial values of x and y
      x = 6
      y = 2

      # print the values
      print("x", x)
      print("y", y)

      # swap the values of x and y
      x = y
      y = x

      # print the values
      print("x", x)
      print("y", y)

.. poll:: ps-predict-poll
   :option_1: It will print: 6, 2, 2, 6
   :option_2: It will print: 2, 6, 6, 2
   :option_3: It will print: 6, 2, 2, 2
   :option_4: It will print: 2, 6, 6, 6 
   :option_5: None of the above

   What will the code above print?  To save space we are showing all of the answers on one line with a comma between values rather than on different lines.


Feedback
==================================

.. shortanswer:: ps-prediction-sa

   Please provide feedback here. Please share any comments, problems, or suggestions.


What to do next
============================

.. raw:: html

    <p>Click on the following link to go the practice problems: <a id="ps-practice2"><font size="+2">Practice Problems</font></a></p>

.. raw:: html

    <script type="text/javascript" >

     function getCookie(cname) {
        let name = cname + "=";
        let decodedCookie = decodeURIComponent(document.cookie);
        let ca = decodedCookie.split(';');
        for(let i = 0; i <ca.length; i++) {
           let c = ca[i];
           while (c.charAt(0) == ' ') {
              c = c.substring(1);
           }
           if (c.indexOf(name) == 0) {
              return c.substring(name.length, c.length);
           }
        }
        return "";
     }

     function setCookie(cname, cvalue) {
        document.cookie = cname + "=" + cvalue + ";";
     }

     window.onload = function() {

        a = document.getElementById("ps-practice2")

        // get prev set cookie
        var EXP_COOKIE = 'python-swap2'
        var cond = getCookie(EXP_COOKIE);

        // if no prev set cookie: generate random condition and set cookie
        if (cond != 'r' && cond != 'p') {
           var v = Math.floor(Math.random() * 2);
           if (v < 1) {
               cond = 'r';
           } else {
               cond = 'p';
           }
           setCookie(EXP_COOKIE, cond);
        }

        if (cond == 'r') {
           a.href = "ps-parsons.html"
        } else if (cond == 'p') {
           a.href = "ps-runcode.html"
        }
     };
    </script>
