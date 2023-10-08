Swapping the Values of Two variables
----------------------------------------

When you *swap* the values of two variables such as ``x`` and ``y``, ``x`` will have the initial 
value in ``y`` and ``y`` will have the initial value in ``x``.  If x's initial value was 6 and y's
was 2 then after the swap x will have a value of 2 and y will have a value of 6.


.. activecode:: ps-pre-swap-run-code-ac
   :autograde: unittest

   Run the code below.  Does it correctly swap the values?
   ~~~~

   # set the initial values of x and y
   x = 6
   y = 2

   # print the values
   print("x =", x)
   print("y =", y)

   # swap the values of x and y
   x = y
   y = x

   # print the values
   print("x =", x)
   print("y =", y)


Practice Problems
-----------------------------------------------------

Please read the following and run the code.

.. activecode:: ps-run-code-1
   :autograde: unittest

   The following has the correct code to *swap* the values in x and y 
   (so that x ends up with y's initial value and y ends up with x's initial value).  Run the code to see that it works.
   ~~~~
   x = 6
   y = 2

   print("x =", x)
   print("y =", y)

   temp = x
   x = y
   y = temp

   print("x =", x)
   print("y =", y)

.. activecode:: ps-run-code-2
   :autograde: unittest

   The following has the correct code to *swap* the values in x and y 
   (so that x ends up with y's initial value and y ends up with x's initial value). There are also 
   comments that explain the code. Run the code to see that it works.
   ~~~~
   # set the initial values of x and y
   x = 6
   y = 2

   # print the values
   print("x =", x)
   print("y =", y)

   # swap the values of x and y
   temp = x
   x = y
   y = temp

   # print the values
   print("x =", x)
   print("y =", y)

The following has just the steps in English to *swap* the values in x and y 
(so that x ends up with y's initial value and y ends up with x's initial value),

.. code-block:: Python

   # set the initial values of x and y

   # set temp to the value of x

   # set x to the value of y

   # set y to the value of temp


Feedback
==================================

.. shortanswer:: ps-runcode-sa

   Please provide feedback here. Please share any comments, problems, or suggestions.

What to do next
============================
.. raw:: html

    <p>Click on the following link to go to the post test: <b><a id="ps-post"><font size="+2">Post Test</font></a></b></p>

.. raw:: html

    <script type="text/javascript" >

      window.onload = function() {

        a = document.getElementById("ps-post")
        a.href = "ps-post.html"
      };

    </script>
