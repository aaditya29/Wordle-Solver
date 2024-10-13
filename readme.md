# Wordle Solver

This is a C++ program that solves the popular game Wordle. Wordle is a word-guessing game where the player has to guess a five-letter word within six attempts.

## Installation

## Usage

1. Enter a five-letter word when prompted.
2. The program will provide feedback on your guess.
3. Keep guessing until you find the correct word or run out of attempts.

## Example

```
$ ./wordle_solver
Enter your guess: apple
Incorrect letters: aple
Correct letters in wrong position: 1
Attempts remaining: 5

Enter your guess: table
Incorrect letters: tble
Correct letters in wrong position: 1
Correct letters in correct position: 1
Attempts remaining: 4

Enter your guess: hello
Incorrect letters: hllo
Correct letters in wrong position: 1
Correct letters in correct position: 1
Attempts remaining: 3

Enter your guess: world
Incorrect letters: wrld
Correct letters in wrong position: 1
Correct letters in correct position: 1
Attempts remaining: 2

Enter your guess: words
Incorrect letters: wrds
Correct letters in wrong position: 1
Correct letters in correct position: 1
Attempts remaining: 1

Enter your guess: sword
Incorrect letters: wrd
Correct letters in wrong position: 1
Correct letters in correct position: 1
Attempts remaining: 0

You ran out of attempts. The word was "sword".
```
