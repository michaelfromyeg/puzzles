# Today&#39;s Puzzle (by [Puzzles](https://github.com/michaelfromyeg/vscode-puzzles))

Created: 7&#x2F;4&#x2F;2023

Source: reddit

ID: latest

## Puzzle

\# Background A \*practical number\* is a positive integer N such that all smaller positive integers can be represented as sums of distinct divisors of N. For example, 12 is a practical number because all the numbers from 1 to 11 can be expressed as sums of the divisors of 12, which are 1, 2, 3, 4, and 6. (\[Wikipedia.\](https://en.wikipedia.org/wiki/Practical\_number)) However, 10 is not a practical number, because 4 and 9 cannot be expressed as a sum of 1, 2, and 5. For more detailed explanation and examples, see \[this recent Numberphile video\](https://www.youtube.com/watch?v=IlZOLwf87gM). # Challenge Write a function that returns whether a given positive integer is a practical number. practical(1) => true practical(2) => true practical(3) => false practical(10) => false practical(12) => true You should be able to handle numbers up to 10,000 efficiently. The sum of all practical numbers up to 10,000 inclusive is 6,804,107. Test your code by verifying this value. # Optional bonus challenge Consider the numbers X in the range 1 to 10,000 inclusive. The sum of all X such that 10^19 + X is a practical number is 1,451,958. Find the sum of all X such that 10^20 + X is a practical number. I found the section \[Characterization of practical numbers\](https://en.wikipedia.org/wiki/Practical\_number#Characterization\_of\_practical\_numbers) in the Wikipedia article useful here. \*I do not have any plans to resume posting here regularly. I just saw the Numberphile video and thought it would make a good challenge.\*
