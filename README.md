# CoolCalc
A Simple Calculator App for Android.

# How Does It Work?
Its functioning is very simple, When you press a button it displays what you tapped on the Text Label and also stores in a varable(runningNumber),
when you tap on another button it <i>places</i> that number on the back of the previous number, and does it till it reaches to the end of the Label.

when you Press any operator, the running Number is stored in another Variable(leftValueStr) and the varible where it was previously stored is wiped, and repeats the above process for the new number.

Case 1:
If you press Equals button the app stores the 2nd Running number into 3rd variable(rightValueStr), clears the runningNumber Variable and it executes the operation and displays the result in the text Label.

Case 2:
If you press another operator, the app executes the previous operation(if any) and displays the result and stores it in the very first variable(leftValueStr) and when you enter a new number it stores it in the 2nd variable(rightValStr) and performs the operation if Equals is pressed or does same thing(Case 2) all over again if any other Operator is Pressed.

# Bugs/Flaws

/------- Fixed ----------/
1) The App stores the numbers in Integer form and thus will crash if a number more than the max value of Int32 is used for any operation.
max possible value of Int32 is - 2 147 483 647 (10 Digits)


Easiest Fix - Try changing Integers to 64 Bit Integers in the code.

/------- Fixed ----------/


2) UI doesnt fill the whole space on the phone..


Easiest Fix - By using Constraints.

# Conclusion

App Made By - Raghav Vashisht

Course Enrolled - Devslopes Course for Android
