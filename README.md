## Objectives

- To design a Finite State Machine (FSM) to implement a slot machine

## Description
A slot machine is a certain type of casino game. Traditional slot machines are coin-operated machines with three or more reels, which spin when a lever on the side of the machine is pulled. The machines include a currency detector that validates the coin or money inserted to play. The machine typically pays off based on patterns of symbols visible on the front of the machine when it stops (It’s not that we are encouraging you to gamble, but why not mimic this idea of game to implement Finite State machine concept).

## Functionality
- Leftmost three LED digits represent three reels, counting up for 0 to 9. 
- Rightmost LED starts with 0 
- Three buttons to operate the machine 
- Note: Active High and switch must be debounced. Debounced check three times if button is pressed. Check once for button released. 
- When BTNL pressed, going to keep counting up from 000. Counted at different rates for randomness
- BTNR stops the counter	
- Displays V if victory 
- Displays 0 if loss
- BTNC continues the cound

## How to Win 
|Condition| Displayed Character |
|--|--|
| 3 of a Kind | V |
| 2 pair | V |

