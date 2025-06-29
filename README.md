# GAME OF TAASH (./CYB3RSEV3N)
This is our Capstone Project for our First Year PDS Lab.
This project is our attempt at making a video game based on Sevens(Badam Satti) with the use of C Language and an external library "Raylib". 

## Information
The game of Badam Satti is very intuitive with easy to follow rules but at the same time sufficiently complex to allow for unique stategies.

**RULES**
- A standard deck of 52 cards is distributed  equally among all the playing members(Usually 4).
- Cards are played out to form a layout of sequences going up and down in suit starting from the seven (as in many solitaire games).
- The player with Seven of Hearts plays first.
- A player who cannot play passes.
- The game continues until one's hand is completely empty.
- The game is won by emptying one’s hand before the other players.

As we can see the game is not completely fair as there is a lot of luck involved but one can still maximize his/her chance of winning by blocking other player's cards and playing the cards that are as far away from 7 as possible given the player has a choice, infact this strategy was used for ai players in the code with some minor tweaking.

## How to Play
1. Click on Cell-H18 to start the game.
2. Use the mouse cursor to choose the card and left clicked to play the card if it's a valid move.
3. The Indicator on left side shows if the Card is playable or not(RED = NO, GREEN = YES, YELLOW = NO CARD SELECTED).
4. If you have no valid card then click on the Glowing red pass button(RED = Pass, Grey= not pass).
5. Once the game ends, a win screen shows up, you can either choose to play again or go back to main menu.
6. You can pause or quit to the main menu whenever you want(mind that the game will reset if you quit to the main menu).
7. If you wish you can see the credits anytime from the main menu.

## Features
- Unique artstyle- We wanted the game to feel as interesting as possible. We finally decided to stick with a Futuristic Cyberpunk artstyle.
- Intelligent AI players- The AI players play intelligently dynamically according to the situation, following are the ai type we coded-
1. RANDOM- As the name suggests, this ai plays random valid moves.
2. FUNCTION- This ai plays the game by choosing the best card based on a function.
3. Monte Carlo- This ai player plays the card based on the probablity of winning by running countless random simulations of the game and choosing the card with inherently best outcomes.
- Textures and Sound effects- Using the functions provided in raylib we added textures and sound
- Countless Quality of Life features- Can be noticed while playing the game.

## Scraped Features
A lots of features had to be scraped to meet the deadline.
1. Full MTCS.
2. Ai avatar system- We wanted to add animated ai players to the now empty black screen you see. The Ai avatar were to respond dynamically according to the current winning and losing player, some snippet of this code can still be found in ai working.txt


## Points for Improvement
- More structured coding (The code is readable but a more structured code is essential to avoid spaghetti code).
- Hardcoded values- Currently the code is resolution depended because of hardcoded values, instead we could have used variables for custom scaling depending upon device's resolution.
- We should have implemented a full Monte Carlo Tree Search (MCTS) for a much smarter ai and to save compute. 
- Better Random function- We used Rand() function with modulus to get desired random values between two numbers but this method is ever so slightly biased. Anyways the function generates a large range of random values therefore the effect of this bias is negligible.
- Use of function to draw buttons- Right now the buttons system is fully functional but using a function would have reduced  lines of code.

## Team Experience
**WHAT WE LEARNED**
1. Fundamentals of application development.
2. Several Algorithms.
3. Applying the theoritical knowledge to model a real world problems.
4. Fixing Memory Leak(Once in the development, a very severe memory leak occured where the program was leaking 30KB every frame which is 30*60 KB every second!!.
If it were not for our talented team this project would have never completed.
We learnt to collaborate, exchanged knowledge with other fellow team members and together solved a plethora of problems we encounted during the development.
This project was not only about the code but also about game development and use of computer graphics to build an interactive ui.

## Credits
All of the contribution of our team members is in Project report document and credit section of our game.

**MISC CREDITS**
- MAIN MENU art- Taken from Thespian's Youtube Video and then converted into individual frames.
- Rest of the art(Game screen, Buttons,Logo) was hand drawn by one of our team member.
- Main menu sound was taken from a youtube video titled "GHOST- Dark Ambience".
- Button sounds were taken from Cyberpunk 2077 and spliced together.
- Credits music- Mind Games (Prey 2017).

   

    










    
    


  
