# Conditional-Skill-test-3
In this conditional skill test, I'm to create a conditional that checks whether a certain result machine is active, and if so, it gives the user a response depending on what the score variable is.
# Plan
This task I'm required to give in 3 variables:
- `machineActive`: Contains an indicator of whether the answer machine is switched on or not (true/false)
- `score`: Contains your score in an imaginary game. This score is fed into the answer machine, which provides a response to indicate how well you did.
- `response`: Begins uninitialized, but is later used to store a response that will be printed to the output panel.
# Algorithm
 Create an if...else structure that checks whether the machine is switched on and puts a message into the response variable if it isn't, telling the user to switch the machine on.

Inside the first if...else, you need to nest a switch statement that puts appropriate messages into the response variable depending on what the value of the score is — if the machine is turned on. The different conditional tests (and resulting responses) are as follows:

- Score of less than 0 or more than 100 — "This is not possible, an error has occurred."
- Score of 0 to 19 — "That was a terrible score — total fail!"
- Score of 20 to 39 — "You know some things, but it\'s a pretty bad score. Needs improvement."
- Score of 40 to 69 — "You did a passable job, not bad!"
- Score of 70 to 89 — "That\'s a great score, you really know your stuff."
- Score of 90 to 100 — "What an amazing score! Did you cheat? Are you for real?"
