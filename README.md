# Representation-of-a-Real-World-Problem-as-a-Markov-Decision-Process


## Aim


The aim of this project is to represent a smart waste collection system as a Markov Decision Process (MDP) and use the Value Iteration algorithm to determine the optimal time to collect garbage. The system aims to reduce unnecessary collection trips, save fuel and time, and prevent garbage bins from overflowing by choosing the best action based on the current bin's fill level.


---

## Problem Statement

### Problem Description

Waste management is a major challenge in urban areas due to the varying fill levels of garbage bins.
Collecting garbage at fixed intervals can waste fuel, time, and resources.
Delaying collection from nearly full bins may cause overflow and unhygienic conditions.
To solve this problem, a Smart Waste Collection System is represented using a Markov Decision Process (MDP).
The system considers four states: Low, Medium, High, and Overflow.
It has two possible actions: Collect and Wait.
Transition probabilities represent the uncertainty in waste accumulation and changes in bin levels.
A reward function encourages efficient collection and penalizes unnecessary trips and overflowing bins.
The Value Iteration algorithm is used to determine the optimal action for each state.
The goal is to reduce unnecessary collection trips, use resources efficiently, and prevent garbage overflow.


---

## MDP Components

A Markov Decision Process is represented as:

$$
MDP = (S, A, P, R, \gamma)
$$

Where:

| Symbol | Meaning |
|---|---|
| $S$ | Set of states |
| $A$ | Set of actions |
| $P$ | Transition probability function |
| $R$ | Reward function |
| $\gamma$ | Discount factor |

---

## State Space


The state space represents the different fill levels of a garbage bin. The system has four possible states:

Example format:

```text
S = {
    State 0 - Low,
    State 1 - medium,
    State 2 - high,
    State 3 - overflow
}
Therefore, the state space is:

S = {Low, Medium, High, Overflow}
```



---

## Sample State

Write your answer here.

A sample state is one specific example from the state space.



---

## Action Space

Write your answer here.

The action space should list all possible actions available to the agent.

Example format:

```text
A = {
    Action 1,
    Action 2,
    Action 3,
    ...
}
```


---

## Sample Action

Write your answer here.

A sample action is one action selected from the action space.



---

## Transition Probability

Write your answer here.

The transition probability explains how the environment moves from one state to another after an action is taken.

General form:

$$
P(s' \mid s,a)
$$

This means:

> Probability of reaching next state $s'$ after taking action $a$ in current state $s$.


---

## Reward Function

Write your answer here.

The reward function defines the feedback received by the agent after taking an action.

General form:

$$
R(s,a,s')
$$



---

## Graphical Representation

Write your answer here.

Draw the MDP graph.

The graph should include:

1. States as nodes.
2. Actions as arrows.
3. Rewards on transitions.
4. Transition probabilities if applicable.


---

## Python Representation

Write your code here.

Use Python dictionaries to represent the MDP.


```python
# MDP Representation using Python
# print("Name:       ")
# print("Register Number:     ")

```
---
## Output

Write your Python output here.


---

## Result

Write your result here.



---

