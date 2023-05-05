Download Link: https://assignmentchef.com/product/solved-cse234-final-project-hangman-game
<br>
In this project you will implement a modified hangman game machine with Logisim. For the game, the minimum requirements are as follows:

<ol>

 <li>The word is taken as 64-bit input.</li>

 <li>Each 8 bit refers to the ascii code of a character. Therefore, the word is 8 characters at most. For instance “hello” is represented as:</li>

</ol>

00000000 00000000 00000000 01101000 01100101 01101100 01101100 01101111

<ol start="3">

 <li>The machine will show the number of characters in the word on 7-segment display.</li>

 <li>The user selects a character by pushing a button, which means that for each character there is a different button input for the machine. If the selected character is absent in the word a LED is turned ON. If ten LEDs are turned ON the user loses, otherwise if the user can find all letters in the word, he wins.</li>

 <li>The machine will show the found letters in the word using a TTY display in Logisim. It also shows the whole word at the end even if the user loses. (Remember you can use carriage return, line feed and backspace with TTY.)</li>

 <li>When the game ends the user can restart a new game with another button.</li>

 <li></li>

</ol>

<table>

 <tbody>

  <tr>

   <td width="351"></td>

  </tr>

  <tr>

   <td></td>

   <td></td>

  </tr>

 </tbody>

</table>

<ul>

 <li>If you build your machine without FSM and sequential design and instead you perform only combinational design. YOU GET 0 CREDIT EVEN IF IT WORKS FLAWLESS. So perform your design following the sequential circuit design steps.</li>

</ul>

We love giving extra credits in this course. If you design any of the below BONUS parts you get extra points. In order to get extra points you have to design BONUS parts exactly the same as explained below. Also if the minimum requirements are not accurately working you cannot get BONUS credits. By fulfilling all BONUS parts and the minimum requirements above you can get at most 175pts from the final project.

BONUS:

<ol>

 <li>You can show a hanging man instead of turning ON leds by using LED matrix in Logisim. (25pts)</li>

 <li>You can remember the number of times the user won and show that on scoreboard using 7segment displays for the scoreboard. Show the score as user vs machine. (25pts)</li>

 <li>You can implement a word memory using 128 64-bit registers (two 128×32-bit ROM in Logisim) each holding a different word and select one of them randomly so that you do not need to take a word as input. Your circuit should also be able to take word from outside. (25pts)</li>

</ol>

Any improvements on the project other than those above will not be graded.

Any cheating attempt is punished by -100.


