# milestone_2.py
Hangman Project
# Create a list containing the names of your 5 favorite fruits.
favorite_fruits = ["Blueberry", "Banana", "Figs", "Strawberry", "Raspberry"]

# Assign this list to a variable called word_list.
word_list = favorite_fruits

print(word_list)
['Blueberry', 'Banana', 'Figs', 'Strawberry', 'Raspberry']

import random

fruits_list = ['Blueberry', 'Banana', 'Figs', 'Strawberry', 'Raspberry']

# Choose a random word from the list
random_word = random.choice(fruits_list)

# Print the randomly chosen word
print("Randomly chosen word:", random_word)
Randomly chosen word: Banana
Randomly chosen word: Blueberry

# Using the input function, ask the user to enter a single letter
# Assign the input to a variable called guess
guess = input("Enter a single letter: ")

# Create an if statement that checks if the length of the input is equal to 1 and the input is alphabetical.
guess = input("Enter a single letter: ")

if len(guess) == 1 and guess.isalpha():
    # In the body of the if statement, print a message that says "Good guess!".
    print("Good guess!")
else:
    # Create an else block that prints "Oops! That is not a valid input." if the preceding conditions are not met.
    print("Oops! That is not a valid input.")
Oops! That is not a valid input.


