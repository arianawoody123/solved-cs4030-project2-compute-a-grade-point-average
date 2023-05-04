Download Link: https://assignmentchef.com/product/solved-cs4030-project2-compute-a-grade-point-average
<br>
Before starting to code your solutions, write pseudocode and/or draw flowcharts. Do not start coding until you have a deeper understanding of what the solutions should look like. Write pseudocode from which you can directly code your program.

<ol>

 <li><strong> Compute a Grade Point Average</strong></li>

</ol>

The letter grades below are converted to points for the purpose of computing a grade point average (GPA). Note that this particular table does not include a D-. The name of your Python source code file will be FirstnameLastname_S_02_01.py, where S = your single-digit section number.

<table>

 <tbody>

  <tr>

   <td width="55">Letter</td>

   <td width="65">Points</td>

   <td width="30"> </td>

   <td width="55">Letter</td>

   <td width="59">Points</td>

  </tr>

  <tr>

   <td width="55">A+</td>

   <td width="65">4.2</td>

   <td width="30"> </td>

   <td width="55">C+</td>

   <td width="59">2.8</td>

  </tr>

  <tr>

   <td width="55">A</td>

   <td width="65">4.0</td>

   <td width="30"> </td>

   <td width="55">C</td>

   <td width="59">2.2</td>

  </tr>

  <tr>

   <td width="55">A-</td>

   <td width="65">3.9</td>

   <td width="30"> </td>

   <td width="55">C-</td>

   <td width="59">2.0</td>

  </tr>

  <tr>

   <td width="55">B+</td>

   <td width="65">3.7</td>

   <td width="30"> </td>

   <td width="55">D+</td>

   <td width="59">1.8</td>

  </tr>

  <tr>

   <td width="55">B</td>

   <td width="65">3.2</td>

   <td width="30"> </td>

   <td width="55">D</td>

   <td width="59">1.2</td>

  </tr>

  <tr>

   <td width="55">B-</td>

   <td width="65">3.0</td>

   <td width="30"> </td>

   <td width="55">F</td>

   <td width="59">0</td>

  </tr>

 </tbody>

</table>




Write a program that converts a list of letter grades entered by a user to a GPA for several GPA calculations. Also calculate the overall GPA for all grades entered.

1.1       Loop until the user enters ‘quit’ at which time proceed at step 1.6.

1.2       Do an inner loop until the user enters a blank line.

1.3       Prompt the user for the next grade. If the grade is invalid (e.g., E+, +A, G, HEY, or Q-), ignore this grade, inform the user and prompt again.

1.4       Here, the user entered a valid grade. Using a list or a series of if-elif-else statements, translate the grade to points and accumulate the total points and the count so you can calculate an overall average later. Prompt for the next grade.

1.5       If the user enters a blank line, calculate and print the GPA for the grades just entered. Your program should correctly handle the case where the user enters no grades. In that case, print “No GPA calculated” and resume at step 1.2.

1.6       Calculate and print the overall average of all GPAs that were processed.

The sum of all points processed

Overall average =       ————————————————

The number of all grades processed

What information do you have to track to be able to produce the overall average?

This problem is derived from <em>The Python Workbook</em>, by Ben Stephenson, page 23, exercise 51 and page 31, exercise 66.




<ol start="2">

 <li><strong> Coin Flip Simulation.</strong></li>

</ol>

Flip a coin until three consecutive occurrences of the same side of the coin are tossed (three heads in a row, HHH, or three tails in a row, TTT). You will simulate the tossing of a coin and find the average number of flips, the minimum number of flips and the maximum number of flips in all simulations. The name of your Python code file will be FirstnameLastname_S_02_02.py, where S = your single-digit section number.




Use Python’s randint() function to generate a 1 or 2 randomly representing H or T. You’ll need to import that function from the ‘random’ module with this statement before your code begins:




from random import randint




2.1       Ask the user how many simulations they want to run, say N. If the user presses the &lt;Enter&gt; key or enters 0 or a negative number, exit the program.

2.2       Loop N times.

2.3       Loop until you find three heads or three tails in a row, HHH or TTT, respectively.

2.4       Start flipping coins. Use randint(1,2) to generate a 1 or 2 for heads and tails respectively.

2.5       Count flips and check for HHH or TTT.

2.6       When you get HHH or TTT, print the flips in the current simulation and accumulate the number of flips, minimum number of flips to get three in a row and the highest number of flips to get three in a row. The flips should be displayed with Hs and Ts with a space between each flip, like H T T H H H

2.7       Go on to the next simulation, if there is one.

2.8       Print the average number of flips, the minimum number of flips and maximum number of flips.

2.9       Resume at step 2.1.




This problem is based on <em>The Python Workbook</em>, by Ben Stephenson, page 37, exercise 80.


