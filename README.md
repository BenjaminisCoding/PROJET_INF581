# PROJET_INF581

game_V1 is the first version of the Quarto game. It might not be optimized and it cannot yet support AiGYM en PyGAME environnement.

game_V2 and game_V3 are improved version where it is now possible to choose different strategies such as random one. It is possible to make fight random opponents and observe statistics during several games, such as the probability to win if the player begins, etc... Turns out that when played randomly chances of winning are less important when the player begins. Not very useful result tought.

The " " is a quatro game Aigym env friendly. The train and test file are used to train and than test RL algorithm on the game.

Reste à faire :

    env : changer certaines de ces propriétés pour mieux faire fonctionner les algos (ie mécanismes fct reward, fonction step pour enlever le random)
    tester différentes techniques de RL : Q-learning, PPO... et les faire s'affronter entre elles
    faire un bilan propre de ces techniques, des résultats
    faire un min-max (Bout)
    faire l'interface graphique (cc Gardies)
    faire le rapport, biblio (Celestin)
