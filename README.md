# Guess a Number Game

This Jibo skill plays the age-old game where you pick a number, and Jibo tries to guess the number.

To make it a little interesting, Jibo picks a different range for you each time.

## Features
* Configure the largest range Jibo can use with the notepad variables min and max in the first ExecuteScript behavior.
* Instructions are only given the first time through.
* Jibo pauses until you say you have your number picked out.
* You can tell Jibo either 'higher/lower' to say whether he should guess higher or lower, or 'low/high' to indicate whether his guess is low or high. These can be mixed and matched.
* When you guess the number, Jibo gives his score and offers to let you play again.
* If you don't provide sensible input, Jibo prompts for what he needs.

## Possible enhancements
* Display Jibo's guess on in numbers on his screen as he guesses.
* Allow Jibo to pick the number and the player to guess. (Requires SDK support for NLU of numbers, which is not released yet.)
* Better checking at boundaries. For example, if Jibo is already at the lower bound and the player says to go lower.
