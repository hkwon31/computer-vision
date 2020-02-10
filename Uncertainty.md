# 13.Uncertainty 

## Why do we need Uncertainty?

Let action $A_t$= leave for airport __t__ minutes before flight. 

Will $A_t$ get me there on time??

Even if we correctly predict the action$A_t$, the action could be wrong depending on the situations. 

__Problems:__
1. partial observability(road state, other drivers' plans, etc...)
2. noisy sensors(wrong traffic sensors, etc...)
3. uncertainty in action outcomes(flat tire, running out of gas, etc...)
4. immense complexity of modeling

Hence, a pure logical approach has two risks. 

1. risk falshood : $A_{25}$ will get me there on time. 
2. leads to conclusions that are too weak for decision making:
-> "$A_{25}$ will get me there on time if there's no accident on the bridge and it doesn't rain and my tires remain intact etc..."

On the other hand, $A_{1440}$ might get me there on time but I'd have to stay overnight in the airpoty. 

#### So, Could we say that $A_{1440}$ is always a better action than $A_{25}$?

Issues : What assumptions are reasonable??

We don't exactly know which assumpstions are better. So, we represent outcomes with probability. 

For eaxmple:
* $A_{25}$ ->$_{0.3}$ $AtAirportOnTime$
* $Sprinkler$ ->$_{0.99}$ $WetGrass$
* $WetGrass$ ->$_{0.7}$ $Rain$

__Probability__

> Given the available probability, 
$A_{25}$ will get me there on time with probability 0.3

Probabilities relate propositions to one's own state of knowledge:
    $$P(A_{25}|No Reported Accidents) = 0.3$$

How about we get new evidence? It might change the outcome before.
    $$P(A_{25}|No Reported Accidents, 5a.m) = 0.4$$

## Why do we need Decision Theory?

Given the available evidence :
- P($A_{25}$ gets me there on time|...)=0.04
- P($A_{90}$ gets me there on time|...)=0.70
- P($A_{120}$ gets me there on time|...)=0.95
- P($A_{1440}$ gets me there on time|...)=0.9999

Which action to choose?

- Depends on my preferences for missing flight vs. airport cuisine

__Utility theory__ is used to represent and infer preferences

__Decision theory__ = utility theory + probability theory


## Probability basis

$\Omega$ is a sample points 














