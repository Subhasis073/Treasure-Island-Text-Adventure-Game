**Overview**

The Treasure Island Text Adventure Game is an interactive, story-based Python console application where the player navigates through a sequence of choices in search of hidden treasure. The game uses conditional branching to create different story paths and endings. This project demonstrates my understanding of decision-based program flow, user input handling, and creative narrative design in Python.


**Learning Objectives & Technical Implementation**

This project helped me strengthen logical thinking, improve code readability, and practice building interactive storytelling experiences.

Concept & Description

1. Interactive User Input - Used the input() function to receive user decisions at each step of the adventure.
Incorporated .lower() to handle user input case-insensitively and avoid errors.

2. Conditional Branching for Game Paths - Implemented multiple if, elif, and else blocks to create different story outcomes based on player choices.
Enabled branching storylines such as:
Safe paths leading closer to the treasure
Dangerous paths leading to game-over scenarios
   
3. Story-Driven Gameplay - Designed a narrative setting (an adventurous treasure hunt), making the experience engaging and explorative.

4. Clear Prompts & Output Messages - Provided descriptive messages, guiding the player through situations like:
Choosing directions
Making survival decisions
Finding or failing to reach the treasure

End-of-Game Conditions


**Example Interaction**

Welcome to Treasure Island.
Your mission is to find the treasure.

You're at a crossroad. Where do you want to go? Left or Right? left
You arrive at a lake. Do you want to Wait for a boat or Swim across? wait
A boat arrives and takes you safely. You reach the island.

You see three doors: Red, Blue, and Yellow. Which one do you choose? yellow

You found the treasure! 🏆🎉

Displayed either:

“You Win! 🏆” when the treasure is found

or “Game Over 💀” when the wrong decisions lead to failure
