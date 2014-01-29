# Kata Reversi

Traduit de: http://codingdojo.org/cgi-bin/wiki.pl?KataReversi

Difficulté: Facile

## Description du problème

Reversi est un jeu de plateau à deux joueurs. Plus d'informations peuvent être trouvées sur [Wikipedia](https://fr.wikipedia.org/wiki/Othello_%28jeu%29). Ce Kata consiste à écrire un programme qui prend la position courrante sur le plateau ainsi que le joueur dont c'est le tour, et revoie une liste de coups autorisés pour ce dernier. Un coup n'est légal que si au moins l'un des pions adverse est retourné.

## Cas d'utilisation Suggérés

```
. . . . . . . .
. . . . . . . .
. . . . . . . .
. . . B W . . .
. . . W B . . .
. . . . . . . .
. . . . . . . .
. . . . . . . .
B
```

(Un "." indique une case vide. Un "B" indique une pièce noire et un "W" représente une pièce blanche. Le "B" terminal indique que c'est au tour de noir de jouer)

Vous pouvez afficher au choix les coups possibles sous forme de coordonées (les
colones vont de A à H, les lignes de 1 à 8 en partant du coin gauche supérieur)
comme ça:

```
[C5, D6, E3, F4]
```

ou graphiquement comme ça:

```
. . . . . . . .
. . . . . . . .
. . . . 0 . . .
. . . B W 0 . .
. . 0 W B . . .
. . . 0 . . . .
. . . . . . . .
. . . . . . . .
B
```
