Download Link: https://assignmentchef.com/product/solved-cs2310-assignment-1-arithmetic-expressions
<br>
In this assignment, students will write a program to solve arithmetic expressions. When the program runs, it reads in an expression <em>(on a single line)</em> and prints out the corresponding answer in the specified format.

Input expressions contain multiple real numbers with arithmetic operators in between. For simplicity, only <strong>+ –</strong> <strong>*</strong> and <strong>/</strong> are used in the expressions, there is no parenthesis ( ) nor advanced mathematics like power or square root. Expressions are basically interpreted from left to right. However, the program should also take the <em>precedence rules</em> into consideration. In other words, if the expression contains multiply/divide, it must be handled before add and subtract.

To simplify the problem further, we only consider expressions with TWO or THREE numeric operands:

<ul>

 <li>Example (2 operands): <strong>2 + 2.6 =</strong></li>

 <li>Example (3 operands): <strong>2 * 3.4 + 5 =</strong></li>

</ul>

The program should detect the number of operands and solve accordingly.




Submitted program will be tested <em>repeatedly</em> by PASS, each time with different input test case. <em>(Note: The program only needs to read in ONE expression, students do not need to create loops to handle the 2<sup>nd</sup>, 3<sup>rd</sup> expression…etc. It is automatically handled by PASS)</em> Students may assume that the input expression is always valid and always ends with the equal (<strong>=</strong>) sign. Students can also assume that <u>there are spaces between</u> <u>numbers, operands and the equal sign</u> such that they will not “<em>stick together”. </em>




<h1>2 Program Behavior</h1>

When the program runs, it first prints out the message “<strong>Please input the formula:</strong>” on a single line. The program then read the whole expression from keyboard and calculate the corresponding answer <em>(hint: you may detect the number of operands by checking whether the input character is </em><strong><em>=</em></strong><em> )</em>. After evaluation, the program then prints a “box” (using <strong>/</strong>, − , <strong></strong>, and <strong>|</strong> characters), inside which it writes: “ <strong>The answer is &lt;answer&gt;</strong> ”.

The output number should be printed in exactly 2 decimal places. Note that the length of the bounding box also varies according to the magnitude and format of the final answer.




Students may assume that there will not be “Division by Zero” cases and that the magnitude of the answer is no greater than 1000000000.




<strong>Sample Input / Output: <em>(for demonstration purpose, user input colored in</em></strong><strong><em> blue)</em></strong>

<table width="0">

 <tbody>

  <tr>

   <td width="283"><strong>Please input the formula: </strong><strong>1 + 2 * 3 = </strong><strong>/——————– </strong><strong>| The answer is 7.00 | ——————–/</strong></td>

   <td width="306"><strong>Please input the formula: </strong><strong>10 / 3 = </strong><strong>/——————– </strong><strong>| The answer is 3.33 | ——————–/</strong></td>

  </tr>

  <tr>

   <td width="283"><strong>Please input the formula: </strong><strong>8.5 + 1.3 + 0.2 = </strong><strong>/——————— </strong><strong>| The answer is 10.00 | </strong><strong>———————/ </strong></td>

   <td width="306"><strong>Please input the formula: </strong><strong>1.5 * 0 = </strong><strong>/——————– </strong><strong>| The answer is 0.00 | ——————–/</strong></td>

  </tr>

 </tbody>

</table>




<h1>3 Marking criteria</h1>

Submitted program will be tested repeatedly with PASS. <strong>Correctness </strong>marks will be graded objectively based on the number of correct outputs reported by PASS.

<ul>

 <li>If the program is not compilable, correctness mark will be zero</li>

 <li>Make sure that the output format (spelling, spacing…etc) follows <em>exactly </em>the sample output above otherwise PASS will consider your answer incorrect. Note that the marker will make NO manual attempt to check or re-mark program output.</li>

</ul>

Unlike tutorial exercises, for assignment, PASS will NOT make ALL test cases visible online. <em>(i.e. there are hidden test cases)</em>. You should not assume that the report generated from the “Test” button is your final result.










Note that the marking in PASS is automatic, therefore the following situations may lead to extremely low marks:

<ul>

 <li>Submission of non <strong>.cpp</strong> files <em>(e.g. .exe or .zip files)</em></li>

 <li>Submission with the “<strong>test</strong>” function rather than the “<strong>submit</strong>” function</li>

 <li>Input/output does not match the requirements as defined.</li>

</ul>

<em>(e.g. incorrect spacing, incorrect spelling, letter cases or punctuations) </em>


