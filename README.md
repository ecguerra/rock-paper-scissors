# Rock Paper Scissors

### Prerequisites
* javascript conditionals
* javascript functions

Create the rock paper scissors game for the console! [Rock paper scissors](https://en.wikipedia.org/wiki/Rock%E2%80%93paper%E2%80%93scissors) is a game of chance where two players throw out one of the three options, rock, paper, or scissors. To determine who wins, use the following guidelines: rock beats scissors, scissors beats paper, paper beats rock. 

**Below are suggested ideas for getting started:**

1. Write a function called `randomMove` that returns a randomly chosen move (rock, paper, or scissors). 
1. Then create a function called `rockPaperScissors` that runs one round of the game. It should accept two arguments, the computer's move and the user's move, and somehow compare the two to decide who the winner is and return who won. 


```
let computersMove = randomMove();
=> rock

let usersMove = randomMove();
=> paper 

rockPaperScissors(computersMove, usersMove);
=> computer chose rock
=> user chose paper
=> paper beats rock, user wins!
```

### Super bonuses for rock paper scissors 

Want to upgrade your mini rock paper scissors game? Consider the following!

1. Try to make [rock, paper, scissors, lizard, spock](http://bigbangtheory.wikia.com/wiki/Rock_Paper_Scissors_Lizard_Spock)
2. Instead of hardcoding the user input, let the user actually enter a choice in the console (check out [this repl.it](https://repl.it/@tmdarneille/prompt#index.js) for an example of catching user input!)


---

Adapted from [SEIR-MAE](https://git.generalassemb.ly/Software-Engineering-Immersive-Remote/SEIR-MAE-INSTRUCTORS/tree/master/unit_1/w02d3/homework/JS_Functions_Scope_Problem_Solving)
