# Markov Decision Processes
A sequential decision problem for a fully observable, stochastic environment with a Markovian transition model and additive rewards is called a Markov decision process, or MDP, and consists of a set of states (with an initial state); a set ACTIONS(s) of actions in each state; a transition model P (s  | s, a); and a reward function R(s). A solution must specify what the agent should do for any state that the agent might reach. A solution of this kind is called a policy. This project implements value iteration, for calculating an optimal policy. The basic idea is to calculate the utility of each state and then use the state utilities to select an optimal action in each state.

## Usage

`python mdp.py transition_file reward_file gamma epsilon`

**transition_file** contains tuple *(state, action, result-state, probability)*

**reward_file** contains tuple *(state, reward)*

**gamma** is *discount factor*

**epsilon** is *max error* in utility
