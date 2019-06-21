# Reinforcement learning with Minecraft/Malmo

## Introduction / theorie
Beyond the agent and the environment, one can identify four main
subelementsof a reinforcement learning system:  apolicy, areward
signal, avalue function,and, optionally, amodelof the environment.

### Dynamic Programming
La programmation dynamique a pour but de r�duire un probl�me a
plusieurs sous-probl�mes, cette m�thode n'est pas applicable a tous
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
Un MDP est d�crit par quatre caract�ristiques:
- S : un ensemble finit d'�tats
- A : un ensemble finit d'actions
-   : la probabilit� qu'une action a d'un �tat s � l'instant t r�sulte
    sur l'�tat s' � l'instant t+1
-   : immediate reward (or expected immediate reward) apr�s transition
    sur un nouvel �tat.

### Q-Learning

### Alternatives au Q-Learning
- Deep Q Networks (DQNs)
  Ne traite que des valeurs discr�ters dans des espaces de dimensions faible.
- Deep DeterministicPoling (DDPG)
  Peut traiter de espaces de dimensions forte.
- Policy Gradient
