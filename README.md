# Austrlian Lottery Ticket Generator
 

Idea:

- Each number is independent. 
- Hence, the total repetitions for each num will likely be equal in the long term.
- Find the relations between a number to the rest within each draw. 
  - For example, if number 1 is drawn, what are the chances for the other particular number to be drawn based on the previous draws.
  - So each number will have a dictionary of other 44 numbers while each number has two parameters: Winning and Supps.
Later, give more weights to those have higher chances when generating a random ticket number.
