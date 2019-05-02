# Poker
Java Texas Hold 'em game

### Done:
* Card and deck abstractions
* Methods to determine a player's best hand 
  * e.g. from a player's 2 hole cards + 5 community cards, what is the highest ranked hand he can play
>1. Royal Flush 
>2. Straight Flush
>3. Four of a kind   
> et cetera

### To do:
* Fully implement players as well as a table object to store the data of a poker round
  * Table
    * pre-flop, flop, turn, river, or an interim?
    * list of players
    * pot size
    * community cards
    * last turn
  * Player
    * in the round?
    * how many chips
    * dealer? small blind? big blind?
    * how many chips have they bet in the current round
* Create the functionality to play a round of poker
  * Show cards
  * Allow bets starting at dealer
    * Add bet to pot, show players the actions of other players
    * If a player folds, remove from table
  * If only one player hasn't folded, end round and award pot
  * When back at dealer, go to next round--repeat til last round of betting
  * Showdown, award pot to winner
* Create a GUI 
  * or, make this application a server which sends the state of the poker game to a web client which can respond with a players action, creating a multiplayer online poker game
