---

name: AI Minesweeper

description: >
    Playing Minesweeper can become frustrating when you are on the
    verge of winning, and suddenly, boom!

title: AI Minesweeper

img_loc: /assets/images/ai-minesweeper/page_intro.png

---

# Motivation

You've been playing Minesweeper, and suddenly, Boom! You make a
blunder and lose all the progress you've made so far. That's not what
you wanted. How can you improve your gameplay to increase your chances
of winning? This is the motivation behind this project.

# Nuts and bolts

Propositional logic is an effective approach to improving the chances
of winning the game by enabling the AI agent to make inferences based
on acquired knowledge. In propositional logic, statements are
formulated in terms of propositions, which can be either true or false
but not both.

There are five essential operators in propositional logic:

- And (conjunction)
- Or (disjunction)
- Not (negation)
- If-then (implication)
- If and only if (biconditional)

Leveraging these logical operations in computers makes it possible to
implement such logic for the AI agent. In Minesweeper, each number
displayed on the board represents the count of mines in the
surrounding tiles. Utilizing these numbers, I constructed a knowledge
base for the agent. If the agent is certain that a tile is not a mine,
it will make that move. Otherwise, it will randomly select a tile to
play and update its knowledge based on the newly obtained information.

# Final result

The following demonstrates the game in action. The game can be played
either solo or with the assistance of the AI agent. It should be noted
that even with the AI agent's help, there are instances where it is
uncertain which tile contains the mine. In such cases, when no safe
move is known, the AI agent will choose a tile randomly. However,
during this random selection, there is a possibility that the chosen
tile contains a mine, resulting in a loss of the game.

![](/assets/images/ai-minesweeper/demonstration.gif)

<sub><a
href="https://cs50.harvard.edu/ai/2020/projects/1/minesweeper/"
target="_blank">Reference</a> to the stub code</sub>
