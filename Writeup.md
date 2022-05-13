
# Writeup

Work in progress...

   For our Final Project, We decided to make a HTML website, which showcases all of our Casino themed games - Somewhat like a _digital casino_.
To start of, we wanted to create a name and establish a somewhat "credible looking" homescreen, we chose the name "Sasquatch" (for reasons unknown), as our name, and then we started to work on our website. First of, we decided to inclue a [GIF that displays a sasquatch](https://giphy.com/gifs/gjHuIwidiRcjemb1GH) from Giphy. We then started to work on the more functional aspects of the website. 

   We started of by adding a "alert" or "notification" button, in the bottom right corner. This button, is meant to allow the user to propose updates, and add their own games. This button remains permenantly in the bottom right corner of the user's screen, no matter where he is on the website. This button also displays the user a popup when hovered over, instructing the user what its purpose is.

   Next, we added a way to display the games, the method which we chose in the end was a slideshow. In the slideshow, we have all the games, and a "welcome page" that is first seen when you scroll to that sector. Additionally, the slideshow also has arrows which will change color when you hover over them, so that you can easily see them even when you are viewing a page with a white background.
   
   The Final Thing we added within the website was a auto scroll button. Because we moved the slideshow further down the page, we had to make it at least somewhat clear that the user must scroll down to view the games, it was for that reason that we added a downwards pointing arrown which directs the user where to go. Then, to make the arrow more functional, we made it an arrow that will auto scroll to the game, when you click on it.
   
The games we added were:
-  Slot Machine
- Blackjack
- Guess an Number
- Coin Flip
- Roulette (not russian)
- Keno
- Blackjack 2.0
- Slots (C)  

The slot machine works by importing the random and time python modules. In a seperate file, I made all of the possible graphics for the slot machine, and imported that into my main.py. I started off by setting the amount of money that the user starts off with. I choose a random number between 0 and 26 for the slots position. Each one of the numbers corresponds to a graphic from my graphics.py. The program asks the user how much money they want the bet and then prints out the display based on the slots position. The program checks if the position equals to 8 17 or 26(The winning positions), if so, the user wins 3x the money, if they lose, they lose the amount of money they betted. This program keeps running until the user wants to quit.

Blackjack (python), works by importing the random and time modules from the python library. Then, I generate two cards for the player and bot and print them out in the terminal. Next is the main loop setup, the while loop starts by checking if the player’s score is 21 (in which case they win and I break from the loop). Then, we take the player’s input, where they decide to hit or stay. the code starts by generating a third card for the player and then checking whether their score is less than, equal to, or greater than 21. If the score is greater than 21 then the player loses. If the score is equal to 21 then the player wins. If the score is less than 21 then the game continues and the bot plays. For the bot to play, there is a simple algorithm for the bot to make a decision that maximizes the bot’s chances of winning. In this algorithm, if the bot’s total is less than or equal to 16, the bot hits, and it then checks whether the bot’s total is less than, equal to, or greater than 21 (same as player). Else, the bot decides to stay (game continues). When the player stays, the bot needs to make a decision. We created a simple algorithm for the bot so that it hits when the bot’s total is greater than or equal to 16 or when the player’s total is greater than the bot’s. Else the bot stays, and then we compare the bot’s score with the player’s score to determine the winner.

Guess an Number, is a pretty simple game...

In Coin Flip, we made it...

Roulette works by...

The way Keno works is...

Blackjack (C) works by having a array called deck, which then is shuffled by a program. This deck, is then “dealt to the players, and the players each have 2 cards, currently, I only have a bot, and one other player. Then, a total for the cards is calculated, and that data is presented to the player. Then afterwards, the player is given the option to hit or stay. This happens multiple times, and eventually, the output, of the player winning, busting, and the same for the bot, is presented.

Finally Slots (C), works by first asking the user if they would like to play or not, then...
