# last-marble
A simulation to draw marbles from a bag and determine color of last marble left.

## What is this project about?
A programming exercise in C#, ASP.NET, and Visual
Studio Community Edition 2015.

### Description
An exercise to help develop proficiency in C# and experience with Visual Studio 2015 Community Edition.  

Problem is from _Algorithmic Puzzles_, Anany Levitin, Maria Levitin, Oxford Univ Press, 2011. 

I have a bag containing 20 black marbles and 16 white marbles. I withdraw marbles from the bag
two at a time.  If both marbles are same color, add a black marble to the bag.  If both
marbles are different colors, add a while marble to the bag.  

What is the color of the last marble in the bag?
If I start with 20 black marbles and 15 while marbles, what is the color of the last marble in
the bag?

Plan: 
I can't answer this question by logic or math, so I'll develop a brute force simimulation - run it 1000 times 
and find the color.  Since the process has randomness built in, I expect the last marble will not always be
the same color, so I'll have come up with a frequency distrbution to characterize the results of the simulation.

### Version 1.0
4/26/2016 - It works!
