# Reinforcement Learning

[![License](http://img.shields.io/:license-mit-blue.svg)](LICENSE)

## Description

Homeworks and labs of the [Reinforcement Learning](http://studiegids.uva.nl/xmlpages/page/2018-2019/zoek-vak/vak/63460) course of the MSc in Artificial Intelligence at the University of Amsterdam. Joint project of [Andrii Skliar](github.com/askliar) and [Gabriele Bani](https://github.com/Hiryugan).

Both homeworks and labs are heavily based on [Reinforcement Learning: An Introduction, 2nd Edition](https://drive.google.com/file/d/1opPSz5AZ_kVa1uWOdOiveNiBFiEOHjkG/view) by Richard S. Sutton and Andrew G. Barto and [A Survey on Policy Search for Robotics](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=1&ved=2ahUKEwiEn6n1wLbfAhVKDiwKHV80BdEQFjAAegQIDhAC&url=https%3A%2F%2Fwww.nowpublishers.com%2Farticle%2FDownloadSummary%2FROB-021&usg=AOvVaw3voyHaGYfgkIFMNbolULeK) by Marc Peter Deisenroth, Gerhard Neumann and Jan Peters.

## Homeworks

##### Tabular Solution Methods 

[Problem statement](https://github.com/askliar/reinforcement-learning/blob/master/homeworks/homework1/homework1.pdf) - [Solution](https://github.com/askliar/reinforcement-learning/blob/master/homeworks/homework1/homework1_sol.pdf)

Main topics: **Bandits**, **Dynamic Programming**, **Monte Carlo methods**, **TD-methods** (TD, SARSA, Q-Learning), **Model-based Learning** (Dyna, Monte Carlo Tree Search).
 
##### Approximate Solution Methods

[Problem statement](https://github.com/askliar/reinforcement-learning/blob/master/homeworks/homework2/homework2.pdf) - [Solution](https://github.com/askliar/reinforcement-learning/blob/master/homeworks/homework2/homework2_sol.pdf)

Main topics: **Value-function approximation** (Semi-gradient methods, Linear value-function approximation, Neural Networks); **Policy Gradient methods** (REINFORCE, Compatible Function Approximation Theorem, Natural Gradient)

## Labs

##### Tabular Solution Methods 

[Problem statement and Solution](https://github.com/askliar/reinforcement-learning/blob/master/labs/lab1/lab1_sol.ipynb)

<p align="center">
  <img src="https://cdn.pbrd.co/images/HT5RuUH.png" width="500" /><br />
  <b>Figure: </b><i>Performance of Monte Carlo method on <a href src="http://www0.cs.ucl.ac.uk/staff/d.silver/web/Teaching_files/Easy21-Johannes.pdf">Easy21</a></i>
  <br />
  <br />
  <img src="https://cdn.pbrd.co/images/HT5TUSD.png" width="500" /><br />
  <b>Figure: </b><i>Performance of Sarsa and Q-learning on <a href src="http://www0.cs.ucl.ac.uk/staff/d.silver/web/Teaching_files/Easy21-Johannes.pdf">Easy21</a></i>
</p>

##### Approximate Solution Methods


[Problem statement and Solution](https://github.com/askliar/reinforcement-learning/blob/master/labs/lab2/lab2_sol.ipynb)

<p align="center">
  <img src="https://cdn.pbrd.co/images/HT61qOY.png" width="900" /><br />
  <b>Figure: </b><i>Performance of A2C (left), DQN (middle) and REINFORCE (right) on <a href src="https://gym.openai.com/envs/CartPole-v0/"> CartPole </a></i>
</p>

## Running

Refer to each notebook name and run Jupyter notebook with a following command:
``` 
jupyter notebook #notebook#.ipynb
```

Note, that you can also launch all of the labs in Google Colab using link button in the beginning of the notebook with *colab* suffix.
