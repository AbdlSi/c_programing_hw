# c_programing_hw

I have completed all parts of the homework as requested in the assignment. Here is what the program does:

* **Random Grid**: It makes a  board and fills every spot with a random lowercase letter.
 
* **Hiding Words**: It places specific words like "great", "hello", and "code" into the grid using coordinates.
 
* **8-Way Search**: When you guess a word, the code looks in all 8 directions (up, down, left, right, and all diagonals) starting from the row and column you enter.

* **Uppercase Feedback**: If you find the word, the program changes those letters to uppercase so they stand out on the board.

* **Winning the Game**: The game keeps track of how many words you found and tells you "Congratulations!" when they are all finished.

* **Exit Option**: You can stop playing anytime by typing "exit".



## Notes:

I followed the rules for the assignment such as:

* **No Pointers**: I did not use any pointers; I only used structs, arrays, and functions that pass by value.

* **Structs**: I used a WordItem struct for the words and a Puzzle struct to hold the whole game.


## Functions that I used in the Code

* fill_random_map: Fills the board with random 'a-z' letters.

* place_all_words: Puts the hidden words on the map at the start.

* find_word_direction: Checks all 8 directions around the point you pick.

* uppercase_found_word: Makes the found letters BIG.

* play_game: The main loop that asks for your word and coordinates.
