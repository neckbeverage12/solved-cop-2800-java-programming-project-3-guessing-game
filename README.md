Download Link: https://assignmentchef.com/product/solved-cop-2800-java-programming-project-3-guessing-game
<br>
5/5 - (7 votes)

For this project you are to implement a stand-alone Java program to play a guessing game.  Your program should pick a random number between one and ten (inclusive) and prompt the user for their guess.  For each guess made, your program should tell the user if the guess was too high, too low, or correct.  The user should only have four (4) tries to get it right before they lose the game.



When a game is over, a dialog should announce if they won or lost and ask the user if they want to play again.  Your dialog should have yes and no buttons.  If they lost this dialog box must show them what the correct answer was.

All user input and output should be done using javax.swing.JOptionPane class, which display dialog boxes.  Other than this, the program is non-GUI.

Your project must be a stand-alone program, not an applet.Other Requirements:The program should use the class java.util.Random to generate the numbers (which is easier than using java.lang.Math random number functions), and use the swing JOptionPane input dialog to read in the user’s guess, and a message dialog for the game over dialog.  The user is told if the guess is too low or too high, or if they got the right answer.  If the user doesn’t guess correctly with four tries, they lose.

As this is your first programming assignment where I don’t provide sample code to use, I provide the design of the program for you.  Your code must have the following methods at least:

public static void main ( String [] args )This method is responsible for the “Play again?” logic, including the you won/you lost dialog.  This means a loop that runs at least once, and continues until the player quits.static boolean playGame ( ??? )This method is responsible for playing one complete game each time it is called, including the what is your guess? input dialog.  Note the message displayed in the input dialog changes each time through the loop, to show if the user’s last guess was too high or too low.  The method should return true if the user won.  If they don’t guess correctly after four tries, the user has lost and the method should return false.static int compareTo ( ???, ??? )This method compares the user input (a single guess) with the correct answer.  It returns a negative integer if the guess is too low, a positive integer if the guess is too high, and 0 (zero) if the guess is correct.No other methods are needed, but if you can make a good case for it you may have additional methods.  (You still need these three methods.)  You must decide what arguments, if any, to pass to these methods.  Please note you must use the design implied by the methods I have required.  (Even if you would have designed the game program differently!)

You must meet all the requirements from the description above.  If you include any creative extras, be sure your program still performs the guessing game as described above.  Creative extras are extrasand you are not free to modify the project requirements.

A non-working project can score quite well (so don’t be afraid to turn one in).  Also a fully working project may not score 100%.

You must work alone on your project, however you can ask your instructor for help anytime.  Do not wait until the last minute to begin work on your projects!Sample Game Log:Below is the captured output of a sample run of this game.  Your game should work the same way.  To make this easier to follow, the model solution has had the GUI input and output replaced with non-GUI I/O, but is otherwise identical.  User input is shown using boldface.

C:Tempjava GuessingGameNonGUI(4 Guesses left) What is your guess (1-10)? 5(3 Guesses left) Too high! What is your guess (1-10)? 3(Game Over) Correct! Well done! Play again (y/n)? y(4 Guesses left) What is your guess (1-10)? 10(3 Guesses left) Too high! What is your guess (1-10)? 9(2 Guesses left) Too high! What is your guess (1-10)? 8(1 Guesses left) Too high! What is your guess (1-10)? 7(Game Over) Sorry, you lose! (number was 2) Play again (y/n)? nC:Temp

You should download the model solution GuessingGame.class and run it a few times, using:

C:Tempjava GuessingGame