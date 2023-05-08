Download Link: https://assignmentchef.com/product/solved-sdev300-week1-simple-python-calculator
<br>
<strong>Python Applications for Lab1</strong>

This lab consists of two parts. The first exercise calculates the minimum and maximum of 5 numbers input by a user. The second exercise produces a simple Python calculator where a user selects the math operator and then enters two values as input for the operator selected. <strong> </strong>

<ol>

 <li>Using the AWS Cloud9 IDE write a program that takes 5 input values from a user and prints the minimum and maximum value. Be sure to prompt the user for each of the 5 input values. The following is a possible application interface. Other application interfaces are possible as well.</li>

</ol>

Welcome to the Python MinMax Application!

This application calculates the minimum and maximum of 5 integer values entered by a user.

Enter your first integer:

4

Enter your second integer:

7

Enter your third integer:

2

Enter your fourth integer:

12

Enter your fifth integer:

1

The minimum integer entered was 1.

The maximum integer entered was 12.

Thanks for trying the Python MinMax application.

*************************************************************************************

Hints:

<ol>

 <li>Use int() to cast the string entered by the user to an integer</li>

 <li>Use min() and max() to calculate the minimum and maximum values</li>

 <li>Test with many combinations. For example, what happens if you enter a non-number?</li>

 <li>Use comments to document your code</li>

</ol>

Note: without any exception handling, you should see issues/errors when testing your program.

<ol start="2">

 <li>Using the AWS Cloud9 IDE Write a Python calculator application that prompts a user to calculate the sum, difference, modulus, product or quotient of two input integers. Since we can’t loop yet, the application should run once and then exit. The application should prompt the user to select the mathematical operator, display what was selected and then prompt the user to enter the two integers.</li>

</ol>

If the user enters a 0 for the second number when the division operator is selected, the application should warn that divide by zero is not allowed and exit.

The following is a possible application interface. Other application interfaces are possible as well.

Welcome to the Python Calculator Application.

What calculation do you want to perform?

<ul>

 <li>Addition (+)</li>

 <li>Subtraction (-)</li>

 <li>Division (/)</li>

 <li>Multiplication (*)</li>

 <li>Modulus (%)</li>

</ul>

Enter 1,2,3,4 or 5 indicating your selection.

2

Subtraction was selected.

Enter your first integer:

12

Enter your second integer

3

The difference of 12 and 3 is 9.

Thanks for trying the Python calculator

***************************************************************************

Hints:

<ol>

 <li>Use int() to cast the string entered by the user to an integer</li>

 <li>Use the mathematical operators, if statements and comparison operators as needed 3. Test with many combinations. For example, what happens if you enter a non-number?</li>

 <li>Use comments to document your code</li>

</ol>

<strong> </strong>

<ol start="3">

 <li>Document your test results for each application within the AWS Cloud9 classroom environment. The test document should include a test table that includes the input values, the expected results and the actual results. A screen capture should be included that shows the actual test results of running the test case. Be sure to include multiple test cases to provide full coverage for all code. For example, if you have you should demonstrate each mathematical operator selected works as expected and every statement in the code is reached through the test cases<strong>. (20 points)</strong></li>

</ol>

A possible test table may look like this:

<table width="623">

 <tbody>

  <tr>

   <td width="64">Test Case</td>

   <td width="111">Input</td>

   <td width="160">Expected Output</td>

   <td width="156">Actual Output</td>

   <td width="133">Pass?</td>

  </tr>

  <tr>

   <td width="64">1a</td>

   <td width="111">1,2,3,4,5</td>

   <td width="160">Minimum = 1, Maximum =5</td>

   <td width="156">Minimum = 1, Maximum =5</td>

   <td width="133">Yes</td>

  </tr>

  <tr>

   <td width="64">1b</td>

   <td width="111">2,10,1,11,11</td>

   <td width="160">Minimum = 1, Maximum =11</td>

   <td width="156">Minimum = 1, Maximum =11</td>

   <td width="133">Yes</td>

  </tr>

  <tr>

   <td width="64">1c</td>

   <td width="111">3,g,e,s,7</td>

   <td width="160">Error</td>

   <td width="156">Error</td>

   <td width="133">Yes but note in future this needs to be addressed.</td>

  </tr>

  <tr>

   <td width="64">…</td>

   <td width="111"> </td>

   <td width="160"> </td>

   <td width="156"> </td>

   <td width="133"> </td>

  </tr>

 </tbody>

</table>




Screen capture of test cases:

Figure 1. Test Case 1a Execution results

Figure 2. Test Case 1b Execution results

Figure 3. Test Case 1c Execution results