# Reinforcement Learning

[![License](http://img.shields.io/:license-mit-blue.svg)](LICENSE)

## Description

Homeworks and labs of the [Reinforcement Learning](http://studiegids.uva.nl/xmlpages/page/2018-2019/zoek-vak/vak/63460) course of the MSc in Artificial Intelligence at the University of Amsterdam. Joint work with [Gabriele Bani](https://github.com/Hiryugan).

Both homeworks and labs are heavily based on [Reinforcement Learning: An Introduction, 2nd Edition](https://mitpress.mit.edu/books/reinforcement-learning-second-edition) by Richard S. Sutton and Andrew G. Barto and [A Survey on Policy Search for Robotics](https://www.nowpublishers.com/article/Details/ROB-021) by Marc Peter Deisenroth, Gerhard Neumann and Jan Peters.

## Homeworks

#### Tabular Solution Methods 

[Problem statement](https://github.com/askliar/reinforcement-learning/blob/master/homeworks/homework1/homework1.pdf) - [Solution](https://github.com/askliar/reinforcement-learning/blob/master/homeworks/homework1/homework1_sol.pdf)

Main topics: **Bandits**, **Dynamic Programming**, **Monte Carlo methods**, **TD-methods** (TD, SARSA, Q-Learning), **Model-based Learning** (Dyna, Monte Carlo Tree Search).
 
#### Approximate Solution Methods

[Problem statement](https://github.com/askliar/reinforcement-learning/blob/master/homeworks/homework2/homework2.pdf) - [Solution](https://github.com/askliar/reinforcement-learning/blob/master/homeworks/homework2/homework2_sol.pdf)

Main topics: **Value-function approximation** (Semi-gradient methods, Linear value-function approximation, Neural Networks); **Policy Gradient methods** (REINFORCE, Compatible Function Approximation Theorem, Natural Gradient)

## Labs

#### Tabular Solution Methods 

[Problem statement and Solution](https://github.com/askliar/reinforcement-learning/blob/master/labs/lab1/lab1_sol.ipynb)

<p align="center">
  <img src="https://lh3.googleusercontent.com/6Bz-RxrhW3J_hupoexFBLfoOzGXx2Kc1VvvFsFWC4i3xBw5NIDwYGeA4a_v_YREqv1C47H5EbWx3ZOqd_7PumPXFyENpCS6UMi7pmomDlscYlpUtg2l12AyZiyWqIP2-bhQ9kcEVgTc=w2400" width="500" /><br />
  <b>Figure: </b><i>Performance of Every-visit Monte Carlo on <a href src="http://www0.cs.ucl.ac.uk/staff/d.silver/web/Teaching_files/Easy21-Johannes.pdf">Easy21</a></i>
  <br />
  <br />
  <img src="https://lh3.googleusercontent.com/8_AkYTsjkN04zibiFhiaxoutNt1tpP-mSGtJgpAinIbn8CP9Wlfhx-QMAq_FtyEXAAJb7VSvLFf8gW9bvPxcD-1s0Nrgz_DAJ-qaYrLTjpVraTPY1nu_GP3MtxFyxUA4k-6TWrtPSw4=w2400" width="500" /><br />
  <b>Figure: </b><i>Performance of Sarsa and Q-learning on <a href src="http://www0.cs.ucl.ac.uk/staff/d.silver/web/Teaching_files/Easy21-Johannes.pdf">Easy21</a></i>
</p>

#### Approximate Solution Methods


[Problem statement and Solution](https://github.com/askliar/reinforcement-learning/blob/master/labs/lab2/lab2_sol.ipynb)

<p align="center">
  <img src="https://lh3.googleusercontent.com/hSxpIu3jzT1zvFF1zl7utrCFOvhLpbLfE6vOqIzZmtR5alThixhB5Cftw3B-e4YZgeSvo52G6K1IYOi7cVmsSSmTJdp-r_nx3adCexEGYKeeItyLbbOIkCwRsCo7VcM6acm0-Tp9wK0=w2400" width="900" /><br />
  <b>Figure: </b><i>Performance of A2C (left), DQN (middle) and REINFORCE (right) on <a href src="https://gym.openai.com/envs/CartPole-v0/"> CartPole </a></i>
</p>

## Running

Refer to each notebook name and run Jupyter notebook with a following command:
``` 
jupyter notebook #notebook#.ipynb
```

## Copyright

Copyright © 2018 Andrii Skliar.

<p align=“justify”>
This project is distributed under the <a href="LICENSE">MIT license</a>. This was developed as part of the Reinforcement Learning course taught by Herke van Hoof at the University of Amsterdam. Please follow the <a href="http://student.uva.nl/en/content/az/plagiarism-and-fraud/plagiarism-and-fraud.html">UvA regulations governing Fraud and Plagiarism</a> in case you are a student.
</p>
