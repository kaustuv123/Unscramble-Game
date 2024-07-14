Unscramble app
=================================

Overview
----------------

Unscramble is an engaging Android app developed using the ViewModel Architecture in Kotlin. The app challenges users to unscramble shuffled letters to form meaningful words. It is designed to be fun, interactive, and a great way to test and improve your vocabulary.


Features
--------------
* **Word Unscrambling**: The app presents the user with a scrambled word, and the user must guess the correct word.
* **Scoring System**: Users earn 20 points for each correct guess.
* **Skip Option**: If users cannot guess a word, they can skip to the next one.
* **Game Rounds**: Each game consists of 10 words (including skipped words).
* **Final Score**: At the end of each round, a dialog box appears to congratulate the user and display their score.


Getting Started
---------------
1. Install Android Studio, if you don't already have it.
2. Download the sample.
3. Import the sample into Android Studio.
4. Build and run the sample.

Technical Details
---------------
* ViewModel Architecture: The app leverages ViewModel Architecture to manage UI-related data in a lifecycle-conscious way.
* Kotlin: The app is coded entirely in Kotlin, ensuring modern and efficient code practices.
* Web Scraping: 200 of the most commonly used nouns were scraped from an online dictionary to populate the word list.
* Randomization: Words are chosen randomly and their letters are shuffled for the user to guess.

How to Play
---------------
1. Start the Game: Launch the app to begin a new game.
2. Unscramble Words: A scrambled word will appear on the screen. Type your guess into the input box.
3. Submit or Skip: Press "Submit" to check your guess or "Skip" to move to the next word if you're unsure.
4. Score Points: Earn 20 points for each correct guess.
5. Complete the Round: After 10 words, a dialog box will appear to congratulate you and display your final score.

User Interface
----------------
The user interface is designed to be clean and intuitive, ensuring a smooth gaming experience. Here’s a snapshot of the UI:
![Screenshot 2024-07-14 160526](https://github.com/user-attachments/assets/877d864e-10d1-4f70-bb82-365170e51342)

