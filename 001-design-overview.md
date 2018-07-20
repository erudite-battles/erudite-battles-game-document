# Erudite Battles

Erudite Battles is a Competitive Educational Card Game.  The player needs to build a deck with cards collected to play matches against other players.

## Deck Hero

The player choose an aligment between the ones available, initialy **Culture**, **Logic** and **Science**. These aligment will decide what kind of cards you can use to build your deck.

## Matchmaking

Due the nature of aligment we will not be able to match a player against another who have the same aligment.

## Battle

The battle objective is to reduce the enemy HP to 0. For that there are 2 phases, one where the players will use the cards which affect different factors, and a battle phase where both players will answer a selected question and, based on the performance will damage the other.

### Resources

 - Cards: cards extracted from the deck. Once there are no more cards we shuffle the discard pile back to the deck.
 - Energy: Used to play the cards, initially you get some base from the hero but permanents can increase it.
 - Permanent: A card that has been played and now stay in the board.
 - Health: The players hero health.

### Phases

Every turn is composes by multiple phases.

#### Gather

This phase is used to effectevely distribute cards, energy and resources to the players.

#### Plan

During planning players will be able to play cards, each player have up to 10 seconds to play their cards. Once they have no cards or resource to play these cards

#### Battle

During this phase, a question will be selected based on the current algiment state and then both players will answer it at the same time.
