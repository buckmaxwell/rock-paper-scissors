# rock-paper-scissors
Exploring the logistics of running a world-wide rock paper scissors contest


# Strategy

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


## Expense travel

Given a pair, Randomly select a 'traveling' player from the pair. If there is
only one player in the pair, the player is not a traveling player. If the
players are within walking distance travel budget is 0. If they are within
driving distance, compensation should include a night in a hotel. If they need
to take a plane, we will pay for the flight.








2. Commence match, if loser, end, if winner, continue


