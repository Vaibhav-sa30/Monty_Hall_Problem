# Monty Hall problem

Here is the problem taken from the [Wiki page](https://en.wikipedia.org/wiki/Monty_Hall_problem).

> Suppose you're on a game show, and you're given the choice of three doors: Behind one door is a car; behind the other two doors, goats. You pick a door, say No. 1, and the host, who knows what's behind the doors, opens another door, say No. 3, which has a goat. He then says to you, "Do you want to pick door No. 2?" 

> Is it to your advantage to switch your choice?

The assumptions (also taken from [Wiki](https://en.wikipedia.org/wiki/Monty_Hall_problem)) are as follows:
1. Car and goats are placed at random behind the doors.
2. Host always picks a door not chosen by contestant.
3. Host always reveals a goat and not a car.
4. Host always offers a choice to switch from the original door to the other closed door.

Under the above assumptions, here are the probabilities of winning.

P(win if contestant chooses to switch) = 2/3

P(win if contestant does not switch) = 1/3

You can see the Wiki page for the computation. Let us simulate and find the probability of winning under switch by Monte Carlo.
