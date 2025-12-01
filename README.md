# aoc2025
My Advent of Code 2025 attempt

Good luck to everyone trying!

# Notes

## Day 0
- I've put input.txt into my .gitignore to be a better AOC participant. In the past, I committed input data, but apparantly the creator of AOC doesn't want input data to be aggregatable (so putting it online in a repo isn't so great)
- I haven't decided what language for this year. I am noodling around with using multiple languages, whatever is easiest for the challenge of the day.
- I will be using [aocd](https://github.com/wimglenn/advent-of-code-data) for helping with fetching input data and example data. This simplifies the data wrangling - in the past I've coded crude data fetchers but this year, I'm just going to focus on the puzzles themselves.

## Day 1
### Part 1
- Decided to use excel
- new functions I encountered: flash fill, nested IF's, MOD, QUOTIENT
- trickiest part was to think in both 0 index and 1 index - the counting system of the problem is 0-99, but the number system that I'm used to is 1-100 so I had to do some trial and error to get the right overflow behaviour
- if I were programming it, I'd either use an array with bounds checking or a ring buffer. I had a ring buffer implementation in c from a previous course ELEX 8030, all I would need to do is to set the ring size, and let the "ring" mechanism take care of the looping/overflow
- using excel was a blessing in disguise because I had access to a bunch of easy to use built in functions so I don't have to code it all
### Part 2
- going to do this tomorrow.