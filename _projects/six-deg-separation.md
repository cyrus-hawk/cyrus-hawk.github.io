---

name: Six Degrees of Separation

description: >
    How far could you be away from any other person in the world?

title: Six Degrees of Separation

---

# Introduction

Six degrees of separation is a concept that hypothesizes that any two
people in the world are connected together with no more than six
number of intermediate connections in between. Inspired by this
concept, I was motivated to implement its algorithm and apply it to a
small portion of the IMDb database that contains sufficient
information about movies and their cast.

# Implementation

We are interested in finding the shortest path between two actors by
selecting a sequence of movies that connects them. This can be
formulated as a search problem to be solved using the breadth-first
search algorithm. Therefore, actors are considered as states, and
movies serve as the actions that lead us from one state to another in
this search strategy.

# Final result

I tried to find out about the degree of separation between the
following actors:

* Mandy Patinkin & Gerald R. Molen

![](/assets/images/six-dgrees-of-separation/mandy_gerald.gif)
![](/assets/images/six-dgrees-of-separation/mandy_gerald.png){: width="50%" height="50%"}

* Jack Nicholson & Cary Elwes


![](/assets/images/six-dgrees-of-separation/jack_cary.gif)
![](/assets/images/six-dgrees-of-separation/jack_cary.png){: width="50%" height="50%"}


* Robin Wright & Demi Moore

![](/assets/images/six-dgrees-of-separation/robin_demi.gif)
![](/assets/images/six-dgrees-of-separation/robin_demi.png){: width="50%" height="50%"}

<sub><a href="https://cs50.harvard.edu/ai/2020/projects/0/degrees/" target="_blank">Reference</a> for the stub code</sub>
