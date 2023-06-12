---

name: Ghost busters

description: >
    Pacman has temporarily gone blind due to eye surgery. The ghosts
    want to scare him, unaware that Pacman has learned from his father
    the power of probabilistic inference to...

title: Ghost busters

img_loc: /assets/images/ghost_busters/page_intro.png

---

# Prelude

Ghosts have been trying to hunt down Pacman for ages, but things are
different now. Pacman has undergone eye surgery, and the ghosts have
decided to give him a break and ridicule him instead of continuing
their pursuit. They believe they can unsettle him by creating phantom
sounds around him. However, they are unaware that Pacman possesses
knowledge of probabilistic inference to aid him during this
challenging period.

# Probabilistic inference

Bayes nets and particle filters are two concepts used in the field of
probability for drawing inference. A Bayes net is a probabilistic
graphical model that represents probabilistic relationships between
variables using a Directed Acyclic Graph (DAG). It enables efficient
inference by utilizing conditional probability distributions to
capture dependencies among variables. On the other hand, particle
filters are estimation techniques employed for state estimation in
non-linear and non-Gaussian dynamic systems. They approximate the
posterior distribution by representing it with a set of particles,
which are sequentially updated based on measurements to provide an
estimate of the true state.

# Final result

Pacman is equipped with both Bayes nets and particle filters in this
project. The following demonstrates Pacman hunting down the ghosts
using the sounds they make near him. In the demo, Pacman is utilizing
particle filters for faster computation instead of Bayes nets due to
the computational cost associated with exact state calculations.

![](/assets/images/ghost_busters/hunter_pacman.gif)

The blocks of color indicate the possible positions of each ghost,
based on the noisy distance readings provided to Pacman. The numbers
at the bottom of the screen display the noisy distances, which are
within 7 units of the true distance. Pacman employs a greedy strategy
to hunt down the ghosts, assuming that each ghost is in its most
likely position.

**Note:** Pacman cannot see the ghosts. The ghosts are only visible to us.

**Note:** Although the recorded demo utilizes particle filters for state
estimation, the entire game took approximately 30 minutes to complete
on my computer. The provided demo has been fast-forwarded multiple
times.

<sub><a href="https://inst.eecs.berkeley.edu/~cs188/sp22/project4/"
target="_blank">Reference</a> to the stub code</sub>
