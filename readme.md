# Operators

## M4 - EX3-EXTRA - Stone, Paper, Scissors

This line of code:
   let numRandom = Math.floor (Math.random () * (4 - 1)) + 1

Returns a random number between min included (1) and max excluded (4).
https://developer.mozilla.org/en/docs/Web/JavaScript/Reference/Global_Objects/Math/random

Write a program that allows you to play stone, paper, or scissors with your computer.

To do this, the computer must generate a random number between 1 and 3 representing stone, paper or scissors respectively, and the user must answer in turn with a number between 1 and 3 after show the following screen:

Let's play stone, paper or scissors:

1. Stone

2. Paper

3. Scissors

Third (1-3):


If the user indicates a number other than the requested number, the following message should appear:

“Entenc que no vols jugar. Adéu"

Otherwise, indicate the winner as follows:

Jo xxx i tu xxx. He guanyat! o Has guanyat!!

as the case may be.

Example:

“Jo paper i tu tisora. Has guanyat!”


** Paper wins the stone because it wraps it; the scissors win the paper because they cut it, and the stone wins the scissors because they break it.

GOAL:

- Practice create a program that works with object dictionary to resolve diferent options.
