---

name: Neural Networks

description: >
    Leveraging neural networks for digit classification, regression,
    and language identification.

title: Neural Networks

---

# Introduction

Inspired by the human brain, neural networks represent a computational
model composed of interconnected nodes organized into three layers:
input, hidden, and output. In this project, I have implemented three
models for digit classification, regression, and language
identification.

# Final result

## Non-linear regression for <math><mi>sin</mi></math> function prediction

The following shows the implemented non-linear regression predicting
the value of <math>
     <mi>sin(x)</mi>
     <mspace width="5px"></mspace>
     <mi>over [-2&pi;, 2&pi;]</mi>
</math> interval.


![](/assets/images/neural-networks/regression.gif)

## Digit classification

The following demonstrates the usage of the MNIST dataset, which
contains 28 <math><mo>&times;</mo></math> 28 grayscale images, to
train the implemented network for the classification of handwritten
digits.

![](/assets/images/neural-networks/digit.gif)

## Language identification

Language identification is the task of determining the language in
which a piece of text is written. For instance, your browser might be
capable of detecting if you've accessed a webpage in a foreign
language and offer to translate it. Using a dataset that includes five
different languages, the following demonstrates the training of the
implemented neural network for language identification, analyzing one
word at a time.

![](/assets/images/neural-networks/lang.gif)

<sub><a
href="https://inst.eecs.berkeley.edu/~cs188/sp20/project5/" target="_blank">Reference</a> to the stub code</sub>
