# I-can-read-your-mind   (written in Python 3, Thonny)
A great mind game where you guess correctly someone's chosen number.  
The code is just a mind assist for you to learn the trick.

-  OK, ask someone to choose a large number (it works with small numbers too, but not as impressive)
-  Perhaps, ask for a random phone # with area code, so that will give 10 digits.  They need to write it down.
-  Or maybe a 5 or 6 digit number because, as you will see, the subject has to do math on the number.
-  But, tell them to use lots of different digits and not to use all the same digit.
-  Then, ask them to scramble the digits in their number in any order they wish.  Write that number down.
-  They are to subtract the smaller number from the larger number. All without you seeing it.
-  Then ask them to select any one of the non-zero digits in the answer resulting from their subtraction.
-  Then ask them to think of that chosen number.
-  Then ask them to read you each of the other digits, slowly, that they did not select. 
-  If you are good, you can do the math in your head.
- 
-  In your head you do a modulo-9 addition of each number they call out and get a total.
-  
-  Example,  they pick 6245123508, scrambled = 2408513652, diff = 3836609856
-  They by their whim choose #9 (non-zero by instruction) from the answer and keep it secret
-  They read out to you the remainging digits
-  you, do this:
-   3...8.(think 11)...3...(think 14)...6 .(think 20 but convert to 2 b/c 20%9 is 2)....6...(think 8)....0 (dismiss)..
-  ....9 (dismiss)....8....(think 16)......5...(think 21)....6...(think 27 but dismiss since 27%9 = 0)
-  So, you come up with 0, and therefore the subject's chosen # was 9 !   (total modulo 9)
-  You have become a mysterious mind reader!
-  
-  My python code accepts no input, it is just there to show you what your mind needs to do and the real reason was so that I 
-  could practice Python coding.  I learned alot!   One issue I had was that I wanted to randomly have an initial number between 4 and 10 digits.
-  But, the program produces a 9 or 10 digit # every time.  If anyone can find my error, let me know through github or www.fuzzywidget.com.
