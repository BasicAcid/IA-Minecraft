# Reinforcement learning with Minecraft/Malmo

## Introduction / theorie
Beyond the agent and the environment, one can identify four main
subelementsof a reinforcement learning system:  apolicy, areward
signal, avalue function,and, optionally, amodelof the environment.

### Dynamic Programming
La programmation dynamique a pour but de réduire un problème a
plusieurs sous-problèmes, cette méthode n'est pas applicable a tous
les domaines.

=> require optimal sub-structure

| Breakable        | not breakable |
|------------------|---------------|
| Shortest pass    | TSP           |
| Knapsack problem | Longest pass  |
|                  | Vertex cover  |
|                  |               |

### Markov Decision Process (MDP)
https://en.wikipedia.org/wiki/Markov_decision_process
Un MDP est décrit par quatre caractéristiques:
- S : un ensemble finit d'états
- A : un ensemble finit d'actions
-   : la probabilité qu'une action a d'un état s à l'instant t résulte
    sur l'état s' à l'instant t+1
-   : immediate reward (or expected immediate reward) après transition
    sur un nouvel état.

### Q-Learning

### Alternatives au Q-Learning
- Deep Q Networks (DQNs)
  Ne traite que des valeurs discrèters dans des espaces de dimensions faible.
- Deep DeterministicPoling (DDPG)
  Peut traiter de espaces de dimensions forte.
- Policy Gradient
