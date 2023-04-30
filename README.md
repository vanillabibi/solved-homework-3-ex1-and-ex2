Download Link: https://assignmentchef.com/product/solved-homework-3-ex1-and-ex2
<br>
<strong>Overview</strong>

In this module/week’s homework assignment, you will complete 2 exercises that will allow you to practice your skill with the topics of generic collections, lambdas, and streams that you learned about in the Reading &amp; Study materials for this module/week.

<strong> </strong>

<strong>Instructions</strong>

<ol>

 <li>Refer to the Homework Grading Rubric before you begin this assignment.</li>

 <li>Complete the detailed instructions for each exercise included in the sections below. For each exercise, begin with a new Java project.</li>

 <li>As you write your code, provide all pertinent documentation in the form of JavaDoc comments for all classes and methods.

  <ol>

   <li>All class-level comments must include a description of the class along with your nameand links to any resources you used (other than the textbook) while writing your code.</li>

   <li>Each method must also have a comment that indicates the purpose of the method and, if applicable, the purpose of all parameters and return value.</li>

   <li>Additional in-line comments must be used to explain complex algorithms or unique solutions to the problem.</li>

  </ol></li>

 <li>Print, sign, and scan (or take a photo of) the Pledge of Academic Integrity.</li>

 <li>After you have completed the exercises for this assignment, submit the following via the Blackboard submission link: a digital copy of your signed pledge sheet, a compressed folder containing your code, and any additional written requirements specified below. <strong>Failure to submit a signed pledge of academic integrity for this assignment will result in an automatic grade of zero (0) for this assignment</strong>.</li>

</ol>




<strong>Exercise 1</strong>

Use a HashMap to create a reusable class for choosing one of the 13 predefined colors in class Color. The names of the colors will be used as keys, and the predefined Color objects will be used as values. Place this class in a package that can be imported into any Java program. Use your new class in a GUI application that allows the user to select one of the colors from a JList. The JList should receive its values from the HashMap programmatically. When the user clicks a button, the application must change the background color of a JPanel to the currently selected color in the JList.




<strong>Exercise 2</strong>

<ol>

 <li>Create an Invoice class with 4 attributes: PartNumber (type int), PartDescription (type String), Quantity (type int), and Price (type double).</li>

 <li>Create a constructor that allows you to initialize all 4 attributes from values passed in as parameters.</li>

 <li>Override the toString() method to display all 4 attributes in a format of your choosing.</li>

 <li>Create a List of 10 Invoices containing data of your choosing.</li>

 <li>Use lambdas and streams to perform the following queries on the list of Invoice objects and display the results:

  <ol>

   <li>Sort the Invoice objects by PartDescription, then display the results.</li>

   <li>Sort the Invoice objects by Price, then display the results.</li>

   <li>Map each Invoice to its PartDescription and Quantity, sort the results by Quantity, then display the results.</li>

   <li>Map each Invoice to its PartDescription and the value of the Invoice (i.e., Quantity * Price). Order the results by Invoice</li>

   <li>Modify Part (d) above to select the Invoice values in the range of $200 to $500 (inclusive) and display the results separately.</li>

  </ol></li>

</ol>

<strong> </strong>

.