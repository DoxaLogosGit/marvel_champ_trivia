# MARVEL_CHAMP_TRIVIA
Trivia question generator for Marvel Champions LCG card game.  The purpose of this code is help players enhance their knowledge of the game and challenge each other with the knowledge in hand.  Hopefully it will make them better players.

This is the core library for using UnicornSnuggler's [Cerebro bot](https://github.com/UnicornSnuggler/Cerebro) which has
[API access](https://cerebro-beta-bot.herokuapp.com/cards)

It will generate a wide variety of questions about the Marvel Champions LCG card pool. 

Questions like:

    1. Name an aspect of a given card title (plus subtitle if it has one)
    2. What type of card is it based on card title
    3. What are the attack/thwart/defense values of a given hero/ally
    4. What is the recovery rate of an alter-ego
    5. What are the traits of a given card
    6. What pack did a card first appear 
    7. Which card has the following flavor text
    8. How many copies of this card can be in your deck

The list above is not exhaustive, but will provide a good jumping off point as more questions are added. The interface will allow a user to customize how many and what kind of questions they would like generated.

This project will be a library only that will hopefully be integrated into other projects like a trivia bot for Discord or a simple web app.

 The first phase of the project will focus on the player cards.  Once that is well tested and working, the next phase will bring villain cards into the mix.