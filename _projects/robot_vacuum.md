---

name: Robot vacuum simulation

description: >
    Exploring two strategies to measure the performance of a robotic
    vacuum cleaner...

title: Robot vacuum simulation

img_loc: /assets/images/robot_vacuum/page_intro.png

---

# Motivation

Robot vacuums can apply different strategies while cleaning the floor.
I wanted to compare two strategies adopted by a robot vacuum to find
out which one is optimal in terms of time.

# Implementation

Two strategies were simulated for this study. The first strategy
involves a robot vacuum cleaning the floor tiles in the direction it
is facing until it encounters a boundary—let's refer to this as the
standard strategy. The second strategy involves the robot choosing a
random direction whenever it needs to clean a new tile—let's call this
the random walk strategy.

## Standard strategy

The following demonstrates multiple runs of this strategy employed by
a robot vacuum. A cleanliness threshold of 40% is selected as the
cutoff point for the room.

![](/assets/images/robot_vacuum/standard.gif)

## Random walk strategy

On the contrary, a random walk strategy is illustrated below for
multiple iterations. Once again, a cleanliness ratio of 40% is chosen
as the cutoff point.

![](/assets/images/robot_vacuum/random.gif)


# Final results

## Multiple robot vacuums

Now, I want to compare the time it takes to clean 80% of the room
using an increasing number of robots, ranging from 1 to 10. As shown
below, a robot vacuum employing the standard strategy takes less time
than the one using the random walk strategy, particularly when the
number of robot vacuums is low.

![](/assets/images/robot_vacuum/inc_time.gif)


## Aspect ratio's impact on cleaning time

How would different heights and widths of the room impact the cleaning
time for the different strategies? The following provides the answer to
this question.

![](/assets/images/robot_vacuum/time_ratio.gif)

Once again, it is evident that a robot vacuum utilizing the standard
strategy outperforms the other strategy, particularly when the aspect
ratio is high. The sizes of the rooms are as follows.

|Width|Height|Aspect ratio|
|:--:|:--:|:--:|
|10|30|![\frac{1}{3}](https://latex.codecogs.com/svg.latex?\frac{1}{3})|
|20|15|![\frac{4}{3}](https://latex.codecogs.com/svg.latex?\frac{4}{3})|
|25|12|![\frac{25}{12}](https://latex.codecogs.com/svg.latex?\frac{25}{12})|
|50|6|![\frac{25}{3}](https://latex.codecogs.com/svg.latex?\frac{25}{3})|
