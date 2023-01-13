# Lecture 2
## Going through the basic jargon
   1. State
   2. Reward
   3. Value
   4. Policy
      1. Greedy
      2. $\epsilon$-Greedy

## Tic-tac-toe Example

Represent the state:

[(First Row)(Second)(Third)] \\\Representation of the state

#Configurations $<= 3^9$
       
        
$\large{*}$--->[Agent] -- (a) -> [Environment (Opponent)] --(s) + (r)---> $\large{*}$

***Note:*** 

A reward is also returned by the environment at the end of the process


The game proceeds is discrete time steps

$s \in \{All possible states\}$ \
$a \in \{Set-of-all-actions\}$\
$r \in \{Set-of-all-rewards\}$\
$t \in Time$


Policy is denoted by $\pi(S_{t-1})=a_t$

$\pi:S\rightarrow A$

Markov Property: The Markov property means that evolution of the Markov process in the future depends only on the present state and does not depend on past history.


There is a learning algorithm running in the agent. 

### Thinking Time:
    Why is the markov property is relevant here?  