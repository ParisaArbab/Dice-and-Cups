# Dice-and-Cups
simulating dice with different numbers of sides (six, ten, and twenty) and a class for managing a collection of these dice. 
This code defines classes for simulating dice with different numbers of sides (six, ten, and twenty) and a class for managing a collection of these dice. Here's a summary of each part:

Dice Classes
SixSidedDie: Represents a six-sided die with methods to roll the die (generating a random number between 1 and 6), get the current face value, and return a string representation of the die.
TenSidedDie: Inherits from SixSidedDie but overrides the roll method to generate a random number between 1 and 10. It also provides its own string representation.
TwentySidedDie: Similar to TenSidedDie, it extends SixSidedDie but adjusts the roll method for a twenty-sided die, generating numbers between 1 and 20, with its own string representation.
Cup Class
Cup: Manages a collection of dice, which can include any mix of six-, ten-, and twenty-sided dice. The class provides methods to roll all dice in the cup, summing their face values, retrieve the sum of the current face values, and return a string representation of the cup and its contents.
Functionality
Dice of different types can be created, rolled individually, and their face values accessed.
The Cup class allows multiple dice to be rolled at once, summing their results, which is useful for games requiring the combined outcome of several dice.
This setup demonstrates object-oriented programming concepts like inheritance (where TenSidedDie and TwentySidedDie inherit from SixSidedDie) and composition (where Cup contains multiple dice objects).
