🎯 Number Guessing Game (Java)

A fun and interactive command-line game built in Java where the player tries to guess a randomly generated number between 1 and 100. The game provides hints after each guess and tracks the number of attempts taken to find the correct answer.

📌 Features
🎲 Random number generation (1–100)
🔢 Unlimited guessing attempts
📈 Tracks number of attempts
⬆️ "Too High" and ⬇️ "Too Low" hints
⚠️ Input validation for numbers outside the range
🏆 Performance-based feedback
🖥️ Simple console-based user interface
📂 Project Structure
Numberguessinggame.java
🚀 Getting Started
Prerequisites
Java JDK 8 or higher
Any Java IDE (VS Code, IntelliJ IDEA, Eclipse) or Terminal
Compile the Program
javac Numberguessinggame.java
Run the Program
java Numberguessinggame
🎮 How to Play
The program randomly selects a number between 1 and 100.
Enter your guess.
The game will tell you if your guess is:
Too High
Too Low
Correct
Keep guessing until you find the correct number.
The game displays your total attempts and performance message.
💻 Sample Output
=========================================
        Welcome to Number Guessing!
=========================================
I have picked a number between 1 and 100.
Can you guess it?

Enter your guess: 50
Too Low! Try a higher number.

Enter your guess: 75
Too High! Try a lower number.

Enter your guess: 62
Correct! The number was: 62
You guessed it in 3 attempt(s)!
Great job!
🛠 Technologies Used
Java
Scanner Class
Random Class
Loops (while)
Conditional Statements (if-else)
📚 Concepts Practiced
User Input Handling
Random Number Generation
Looping
Conditional Logic
Variables and Data Types
Basic Game Development
🏆 Scoring Feedback
Attempts	Feedback
1	Amazing — first try!
2–5	Great job!
6+	Keep practicing to improve!
⚠ Input Validation

If the user enters a number outside the valid range:

Please enter a number between 1 and 100.
🔮 Future Improvements
Multiple difficulty levels
Limited attempts mode
High score tracking
Replay option
Multiplayer mode
GUI version using Java Swing
👨‍💻 Author

Ankush Kumawat
