Swapping the Values of Two variables
----------------------------------------

When you *swap* the values of two variables such as ``x`` and ``y``, ``x`` will have the initial 
value in ``y`` and ``y`` will have the initial value in ``x``.  If x's initial value was 6 and y's
was 2 then after the swap x will have a value of 2 and y will have a value of 6.

.. activecode:: ps-pre-swap-ac
   :autograde: unittest

   Run the code below?  Does it correctly swap the values?
   ~~~~

   x = 6
   y = 2
   temp = 0

   # print the values
   print(x)
   print(y)

   # swap the values of x and y
   x = y
   y = x

   # print the values
   print(x)
   print(y)

Practice Problems
-----------------------------------------------------

Please answer
the following problems to the best of your ability without any
outside help. You can stop working on a problem after you have worked
on it for about five minutes without solving it.

Problems
==============

.. parsonsprob:: ps_swap_code_only_pp
   :numbered: left
   :practice: T
   :adaptive:
   :noindent:

   The following has the correct code to *swap* the values in x and y 
   (so that x ends up with y's initial value and y ends up with x's initial value), but the code is mixed up and contains one extra block which is not needed in a correct solution.  Drag the needed blocks from the left into the correct order on the right. Check your solution by clicking on the Check button.  You will be told if any of the blocks are in the wrong order or if you need to remove one or more blocks.  After three incorrect attempts you will be able to use the Help Me button to make the problem easier.
   -----
   x = 3
   y = 5
   =====
   temp = x
   =====
   x = y
   =====
   y = temp
   =====
   y = x #distractor: the value of x is set to y so you should set it to the value of temp

.. parsonsprob:: ps_swap_code_and_comments_pp
   :numbered: left
   :practice: T
   :adaptive:
   :noindent:

   The following has the correct code to *swap* the values in x and y (so that x ends up with y's initial value and y ends up with x's initial value), but the code is mixed up and contains one extra block which is not needed in a correct solution.  Drag the needed blocks from the left into the correct order on the right. Check your solution by clicking on the Check button.  You will be told if any of the blocks are in the wrong order or if you need to remove one or more blocks.  After three incorrect attempts you will be able to use the Help Me button to make the problem easier.
   -----
   # set the initial values of x and y
   x = 3
   y = 5
   =====
   # set temp to the value of x
   temp = x
   =====
   # set x to the value of y
   x = y
   =====
   # set y to the value of temp
   y = temp
   =====
   # set y to the value of x
   y = x #distractor: the value of x is set to y so you should set it to the value of temp

.. parsonsprob:: ps_swap_comments_pp
   :numbered: left
   :practice: T
   :adaptive:
   :noindent:

   The following has just the steps in English to *swap* the values in x and y 
   (so that x ends up with y's initial value and y ends up with x's initial value), but the blocks are mixed up and there is one extra block which is not needed in a correct solution.  Drag the needed blocks from the left into the correct order on the right. Check your solution by clicking on the Check button.  You will be told if any of the blocks are in the wrong order or if you need to remove one or more blocks.  After three incorrect attempts you will be able to use the Help Me button to make the problem easier.
   -----
   # set the initial values of x and y
   =====
   # set temp to the value of x
   =====
   # set x to the value of y
   =====
   # set y to the value of temp
   =====
   # set y to the value of x #distractor: if x already has the value of y you should set y to the value of temp

Feedback
==================================

.. shortanswer:: ps-parsons-sa

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
