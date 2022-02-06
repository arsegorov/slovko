SLOVKO
===
a WORDLE clone in Russian

Rules
---
The game selects s random 5-letter word, but doesn't show it to the player. The goal is to guess the word in 6 or fewer attempts.

On each attempt, the player types in their guess into the grid, and then clicks `Enter`. After the attempt, the game provides feedback on each letter in the attempt:

+ If the letter is present in the correct answer and is in the correct position, it's highlitghted green.
+ If the letter is present in the correct answer, but is not in the correct position, it's highlighted yellow.
+ All other letters remain unhighlighted.

The prior attempts and feedback remain visible to the player.

### Russian-specific rules

+ The selected word is a nominative case singular noun.
+ The Russian letter `Ё` is shown as `Е` and is like `Е` in the correct answer and in the feedback.  
For example, if the game selects the word `ёршик`,
 which would be displayed by the game as `ЕРШИК`,
 and if the player guesses `ПЕРЕЦ`,
 the game will highlight the both `Е`s and the `Р` yellow.
