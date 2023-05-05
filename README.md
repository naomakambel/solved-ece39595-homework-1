Download Link: https://assignmentchef.com/product/solved-ece39595-homework-1
<br>
<strong>Part A </strong>

Using an IDE, run the simple C++ program included with this homework in an IDE.  Students in previous C++ courses like Microsoft’s VisualStudio, which is available for Windows, Linux and MacOS.  Eclipse is another.  Feel free to use another one, if you like.  Take a screen shot of the screen after running the program in the IDE, and turn it in to Brightspace.

<strong>Part B. </strong>

<strong>Part i. </strong>

Write a C++ program that declares an Automobile class.  The class has variables to hold a vehicle identification number that can be represented as an integer, miles driven, which can be represented as a float, and the date of the last maintenance, which should be stored as a string.  A class attributes (variables) should be private.

Automobile should have a getter for each of the above values.   The getter for the maintenance date returns a String.  The statement for forming the string for the date is

<strong>“”+std::to_string(mm)+”/”+std::to_string(dd)+”/”+std::to_string(yy);</strong>

where “mm”, “dd” and “yy” are the integer variables holding the month, day and year, respectively.

The constructor for automobile takes values for each of the variables, and for the month, day and year, i.e., it will take an int, float, int, int and int.

A separate file, HW1.cpp, contains the main function.  It should call the constructor twice to create two Automobile objects, and then print out the values of each automobile using

<em>std::cout &lt;&lt; </em>&lt;string to be printed&gt;<em> &lt;&lt; std::endl; </em>

<strong>Part ii. </strong>

Take the Automobile class above and store the maintenance date as three integer values, month, date and year, instead of as a string.  The getters and setters for the date should still take three integers and return a String, respectively.

You should be able to run an unchanged HW1.cpp against the changed Automobile class and get the same results you got with the original Automobile class.