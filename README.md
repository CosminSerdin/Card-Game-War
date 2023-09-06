# Simple Card Game in Python

This is a Python implementation of a simple card game played between two players. The game is a variation of the classic card game War, where players draw cards and compete to have the highest-ranked cards.

## Overview

In this card game, two players (Player One and Player Two) are created. A standard deck of 52 cards is shuffled and divided evenly between the two players, with each player receiving 26 cards.

The game consists of multiple rounds, where players draw cards from their decks and compare the ranks of the drawn cards. The player with the higher-ranked card wins the round and collects both cards. If the ranks are equal, a "war" is declared, and each player places five cards on the table, with the player who wins the subsequent round collecting all the cards on the table.

The game continues until one of the players runs out of cards or a predefined number of rounds is reached. The player with the most cards at the end of the game is declared the winner.

## Features

- Deck of 52 cards, including four suits (Hearts, Diamonds, Spades, Clubs) and thirteen ranks (Two, Three, Four, Five, Six, Seven, Eight, Nine, Ten, Jack, Queen, King, Ace).
- Classes for Card, Deck, and Player to represent game elements.
- Shuffling and dealing of cards to players.
- Logic for comparing card ranks and handling "war" rounds.
- Determination of the game winner based on the number of cards held.
