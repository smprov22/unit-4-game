# Infinity Stones Counter

https://smprov22.github.io/Infinity-Stones-Counter/

![Infinity-Stones-Counter](/assets/images/screenshot/Infinity-stones-screenshot.PNG)

For this project we were tasked with creating a variation on the "Crystal Collector" game.  I themed my game after the Infinity stones from the Avengers universe.  There are actually 6 infinity stones, but for simplicity sake, I only used 4. Each stone has a random value between 0 and 12, but that value is hidden from the player (and changes each round).  The only way to find the value is to click on each stone.  Each time you click on a stone, the value of that stone is added to the "Stone Counter" tally. There is also a randomly generated number  , between 19 and 120 (that changes each round).  The object of the game is to have the total of the stone counter equal the randomly generated number.  If you match the number, you win, if you go over the total, you lose.

I created this game using HTML 5, CSS 3, and jQuery.  I initially figured out how to make this work pretty quickly.  I generated a number for each stone and a number for the random number.  I got the clicks to work and the score counters to work right away.  The problem was my code was very repetitive.  Once the game worked, I went back through and tried to clean it up.  I used a loop to generate the value for the stones instead of using the math.floor function 4 different times.  I had a small blocker where the loop was generating the same number for all 4 stones, but once I got that worked out I was good to go.
