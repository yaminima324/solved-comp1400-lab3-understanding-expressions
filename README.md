Download Link: https://assignmentchef.com/product/solved-comp1400-lab3-understanding-expressions
<br>
An International Standard Book Number (ISBN) is a unique number assigned to each book.  ISBN-10 has ten digits in 4 parts which the last digit is “check digit”. The check digit is base eleven, and can be 0-9 or X (instead of 10). To compute a missing check digit, each digit should be multiplied by its position in the number (counting from the right). Then, the sum of these products should

be divided by 11 to find the remainder. Finally, the check digit can  be found by subtracting the remainder from 11.

For example, take the ISBN 0-201-53082-?:

<ol>

 <li>First calculate sum of products: 0×10 + 2×9 + 0×8 + 1×7 + 5×6 + 3×5 + 0×4 +</li>

</ol>

8×3 + 2×2 = 98

<ol start="10">

 <li>Remainder upon dividing by 11 is 10.</li>

 <li>Remainder is subtracted from 11.</li>

 <li>Check digit is 1.</li>

</ol>

For more information, watch the following Youtube video about finding the missing check digit of an ISBN number     https://www.youtube.com/watch?v=5qcrDnJg-98

<strong>Part A: RAPTOR Exercise </strong>




<ol>

 <li>Start RAPTOR and create a flowchart that asks the user to enter the first 9 digits of an ISBN-10, and displays the corresponding check digit.</li>

 <li>Run the flowchart with different numbers.</li>

 <li>Save the flowchart to a file named “isbn.rap” in the working directory on the PC you are using.</li>

 <li>Demonstrate the isbn.rap file to GA/TAs and run with different input values.</li>

</ol>




<strong>Part B: C Programming Exercise </strong>

<strong> </strong>

<ol>

 <li>Implement the algorithm as represented by “isbn.rap”, and write an equivalent C program that accomplishes what the flowchart does. The program, however, is allowed to call the scanf(…) function only once. A sample interaction is shown below:</li>

</ol>




Enter the first nine digits of ISBN: <u>020153082</u>  Check digit: 1




<ol>

 <li>Save your program to a file named “isbn.c” in the working directory on the PC you are using.</li>

 <li>Demonstrate the isbn.c file to GA/TAs and run with different input values.</li>

 <li><strong>Hint</strong>: To read single digits, we’ll use scanf with the %1d conversion specification.</li>

</ol>




<strong>EVALUATION: </strong>

You need to show your GA/TA the complete programs at the end of this lab, or at the beginning of your next lab. The marks you will receive for this lab are made of two parts: Lab work marks 10 and attendance marks 5. <strong>Total 15 marks</strong>.




<strong>Lab Work Mark</strong>: Your C code will be evaluated based on your solutions for the problems based on the following scheme:




<ol>

 <li>Does the code run and meet specifications?

  <ul>

   <li>Is input adequate and input data type properly validated?</li>

   <li>Is processing adequate?</li>

   <li>Is output correct and adequate?</li>

   <li>Is the code compliable?</li>

   <li>Is the code run properly?</li>

  </ul></li>

</ol>




<ol start="2">

 <li>Is the code properly commented?

  <ul>

   <li>Is the program title, programmer’s first and last name, and the date posted at the top in a multi-line comment?</li>

   <li>Is each significant step of the program properly commented?</li>

   <li>Are comments added to clarify details?</li>

   <li>Are comments clear, accurate, neatly formatted, and have no misspellings?</li>

  </ul></li>

</ol>




<ol start="3">

 <li>Is the code properly formatted?

  <ul>

   <li>Are blocks of code indented according to their parent-child relationship?</li>

   <li>Do curly braces line up vertically?</li>

   <li>Is there an empty line between significant steps (blocks) of the program?</li>

   <li>Is the width of the code contained within a reasonable limit so that minimal horizontal scrolling is required (with 800 x 600 monitor resolution), and there is minimal line-wrapping when printed?</li>

   <li>Is camel-case notation used for variable, e.g. employeeLastName?</li>

  </ul></li>

</ol>




<strong>IMPORTANT: </strong>

ASK QUESTIONS IF YOU GET STUCK, BUT DO YOUR OWN CODE. ANY CODE SUSPECTED TO BE SIMILAR TO ANOTHER SUBMISSION WILL CAUSE BOTH SUBMISSIONS TO RECEIVE A ZERO MARK ON ALL LABS AND BE REPORTED FOR PLAGIARISM.