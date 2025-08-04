########

seed 1 = Ziyi
seed 100 = Mahdi
seed 19 = Hassrol
seed 1234 = Ruby

########

# seed19_testskipturn

Résultat attendu :
Faire lance, et voir "Aucun coup légal possible pour le joueur B. Le tour est passé."

# seed19_skipturn_1dicereamaning

Résultat attendu :
Faire move 21 22 (seul coup possible), et voir "Aucun coup restant possible pour le joueur B. Le tour est passé."

# seed19_sortie

Résultat attendu :
Faire move 23 25 ---> Pas de sortie de pions car ce n'est pas le meilleur coups.
Faire move 21 25 ---> Idem
Faire move 20 25 ---> Sortie de pions valide.

# seed19_nonmaxout

Résultat attendu :
Faire move 22 25 ---> Pas de sortie de pions car ce n'est pas le meilleur coups.
Faire move 21 25 ---> Dée de valeur 5 mouvement 4 est le plus proche de 5, donc coups valide mais non optimal.

# seed1_fullgame :

Résultat attendu :
Le jeu est censé se finir correctement avec une victoire de B.

# seed100_drawgame :

Résultat attendu :
Erreur produit en fin de game ou aucun des deux joueurs ne peut se déplacer.
(Piste : Epingle du pions mère en {0,24} Victoire spécial Mamas)

