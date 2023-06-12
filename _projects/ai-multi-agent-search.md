---

name: AI multi-agent search

description: >
    How to teach an AI agent to act on its own in an adverserial
    environment?

title: AI multi-agent search

img_loc: /assets/images/ai-multi-agent-search/page_intro.png

---

# Introduction

Pacman finds himself in a world filled with ghosts relentlessly
pursuing him. His objective is to evade his enemies by consuming all
the available food and reaching the final destination. To achieve
this, he requires a mechanism to devise a strategy. In this project, I
have implemented the reflex agent, minimax agent, and expectimax agent
algorithms for Pacman to employ and survive in this world.

# Final result

## Reflex agent

A reflex agent operates based on simple condition-action rules or
"reflexes." It takes the current percept, which represents the agent's
current state of the environment, and directly maps it to an action
without considering the history or future consequences. The following
demonstrates Pacman acting as such an agent.

![](/assets/images/ai-multi-agent-search/reflex_agent.gif)

## Minimax agent

This agent determines the optimal move by evaluating all potential
outcomes through recursive evaluation of the game tree. The following
demonstrates Pacman utilizing this algorithm with α-β pruning.

![](/assets/images/ai-multi-agent-search/minimax_wab_agent.gif)

## Expectimax agent

The minimax agent always acts optimally, assuming opponents
consistently act aggressively in an attempt to eliminate their foes.
In contrast, an expectimax agent considers the possibility that
adversaries may make mistakes or suboptimal moves. The following
demonstrates the expectimax agent, which takes a more cavalier
approach by assuming adversaries do not always choose their best
actions.

![](/assets/images/ai-multi-agent-search/expectimax_agent.gif)

<sub><a href="https://inst.eecs.berkeley.edu/~cs188/sp20/project2/"
target="_blank">Reference</a> to the stub code</sub>
