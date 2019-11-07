# rock-paper-scissors
Exploring the logistics of running a world-wide rock paper scissors contest


# Definitions 

## Pair 

If number of people is greater than 1, Create n pairs of people by grouping
people with the closest person who has completed an equal number of matches. If
number of people is > 1. A pair can include 1 person if there is an odd number
of people.

## Shoot

Pairs play rock paper scissors unti the outcome is not a tie. The loser is no
longer a contestant. In cases wehre there is only one person in the pair that
person wins. The winners number of wins increments by 1, so does her number of
matches.

Record the location to the travel log. 
Record current location on both contestants


## Decide traveling player

Given a pair, Randomly select a 'traveling' player from the pair. If there is
only one player in the pair, the player is not a traveling player.


## Expense travel

If the players are within walking distance travel budget is 0. If they are
within driving distance, compensation should include a night in a hotel. If they
need to take a plane, we will pay for the flight and a hotel.

Record the cost in the budget.


## Travel log

Stores flight records


## Budget

Stores the expensed flights and hotels.

## Travel

Record the new location of the traveling player

# Game play

While the number of contestants is greater than 1,

If all rounds have finished:

  1. Pair
  2. Decide traveling player
  3. Expense Travel
  4. Travel
  5. Shoot

Else:

  continue














2. Commence match, if loser, end, if winner, continue


