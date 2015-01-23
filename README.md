# Project_Raymond

War is a simple card game for 2-6 players. Cards are split between players, each turn every 
player plays 1 card from the top of their pile. Highest card wins. If the cards are of equal 
value (this event is called a "battle"), players are playing down 2 more cards face down and 
another card face up - highest card wins. If the cards are still equal, the process is being
repeated. Player who wins a turn collects all the cards that were used and puts them on a pile
next to his cards. Cards in players initial deck and won pile are always facing down, so players
don’t know what is coming next. Once a player uses up all of his initial cards, the pile of 
previously won cards is being used next. Player is out of the game when he/she doesn’t have any
more cards to play. Player who collects all of the cards wins.

Project Raymond is a simulation of the game that will calculate various statistics and data about War.


# Requirements

Game structure<br>
<br>-deck has to be shuffled between each game
<br>-cards are split between all players
<br>-if there are 2 or 4 players, every player gets the same amount of cards
<br>-if there are 3, 5 or 6 players, it should be decided randomly who gets extra cards


<br>Deck structure
<br><br>-ace high
<br>-colours don't have any significance, but should still be accounted for
<br>-it should take between 1 and 3 seconds to finish each turn, unless its a "battle" - this 
should last between 5 and 8 seconds (this should not be shown in real time, as hundreds of 
games should be simulated every second). 
<br>-when a player wins a turn, the cards won should be put on a pile in a random order

<br>Statistics structure:

-a way of running the simulation X number of times to find out the statistics listed below

<br>Types of stats needed:

-odds of winning a game when a player has 1 less or 1 more card then other players
<br>-odds of winning a game when initial deck has 1,2,3 or 4 aces
<br>-odds of winning a game when initial deck has 1,2,3 or 4 2s
<br>-average length of the game with 2-6 players

UI to be decided, maybe a web gui?


Rest TBC
