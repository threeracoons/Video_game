# Video_game

 

CAC - 1
Data Analytics Lab

MINI PROJECT REPORT


Prof. 
Kandula Balagangadhar Reddy



By
Threeshal Sashtiy B S
Dhananjay Chandel
3B.Sc DS A



Abstract
In this assignment, we were asked to create a code in python that has Implementation of List, Dictionaries, String & String Functions, Various Operators, Conditional Statements, Looping Statements, and User Defined Functions. Our topic, A turn based fighting video game, Was done with Jupyter, with the UI in the code’s output itself, graphics could not be added in regular python.

About the code’s application:
The Code is based on the popular video game franchise, “Pokémon”, the game has its own story surrounding it as well, about you going into a haunted cavern, hence the name of the game’s file is “POKEMON: THE HAUNTED CAVERNS”, and with that story and an instructions part, the game begins.
After knowing the premise of the story, you only fight ghost type Pokémon, there are 8 ghost types in total that you might encounter, you’ll have to fight through an endless amount of them using your six Pokémon, with three balanced (reasonably) Pokémon, a stone wall like Pokémon, a glass cannon like Pokémon and a Pokémon that is an absolute powerhouse which is a dragon, but since you are in a cave, there are no items to heal your Pokémon, so means you will have to fight as long as you can until all your Pokémon have been defeated.
The game also is like a high-score game, where there is no end goal but to go as far as you possibly can, your high score can vary because just like in the actual Pokémon games, there is a lot of RNG (random number generator), as luck based as it is, there is also a bit of balancing done in it as well to reduce the luck factor.
Your Pokémon are fixed to this team, Here is Your Team:-
                                                                                                          




Functions:
This is a large code with many functions, but the entire code requires only one import called “random”, random allows the code to have use the ability of creating a random output from a list, a range of numbers, etc. Giving the code the power of making a probability.
Apart from the library of random, the functions and classes in the code include:-

CLASS: Character, this defines every entity in the code as a character, your Pokémon, or the enemy Pokémon.

__INIT__ : This is the function that defines and begins the entire function, where the characters have a name, hit points (hp) and attack power.

ISALIVE: This function checks whether the characters are still alive and ready to fight or not

ATTACK: This the most important part of the code, as attacking the enemies is a huge part of the game, it defines the damage dealing in the fight.

DEFEND: This code helps reduce the incoming damage in a fight for a turn.

SPECIAL_ATTACK: This is a different code, the special attack does damage equal to the enemies hp at that moment, but this code will only run if the random integer gives you the right number in a 1/5 odds.

RECEIVE_DAMAGE:  The Recieve_damage correlates to the attack function, it shows the damage dealt in that turn from the attack.

RESET: This code will only apply to the enemies, because once an enemy is defeated, they can reappear again later on.

DISPLAY_STATS: This function displays the stats of the characters (their hp only) in the fight.

CHOOSE_CHARACTER: There are two parts to this code:
•	User end: You have six players that you get to choose from.
•	Back end: This is the selection of your enemy, this character is chosen at random between a few ghost types.

BATTLE: This function is where the fight begins, between the player of your choice and the enemy of the CPU’s choice, the battle allows you to access the three previously mentioned functions and one new option that is not a function, Run Away, which completely stops the program and says that you ran away before ending.

SAVE_LOG: This is the code that documents the outcome of each turn and each battle into a .txt file called “Poke-battle log”.

ADVENTURE:  This function is the last one, where your players and enemies are created, the Adventure is a loop function which repeats the code of “battle” in a 1/3 probability, if it doesn’t occur, then the user continues through the Adventure, the loop is counted every time it runs and is displayed as a score, the score counts even if the “Battle” begins, it works kind of like a main function.
These are all the functions present in the program for the game.








SUMMARY
The code is for a simple video game, a Pokémon game at that, it simulates the Random Number Generator based gameplay that it is known for, along with its incredible character design, the game has a fixed set of Pokémon for you whose images have been shown. The ghost type enemies will be shown below. The game has you moving which is counted in a loop function, The User Interface of the code is present in the output itself, every function is mentioned in the report/documentation.
The enemies:
                                                                                                                                 
