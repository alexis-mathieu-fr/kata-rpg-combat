Kata de combat RPG
================
Source : [[https://github.com/ardalis/kata-catalog](https://github.com/ardalis/kata-catalog)](https://github.com/ardalis/kata-catalog/blob/main/katas/RPG%20Combat.md)

# Contexte

Il s'agit d'un kata amusant qui permet au programmeur de construire des règles de combat simples, comme pour un jeu de rôle (RPG). Il est implémenté comme une séquence d'itérations. Le domaine n'inclut pas de carte ou d'autres compétences des personnages en dehors de leur capacité à s'infliger des dégâts et à se soigner les uns les autres.

# Instructions

1. Terminez chaque itération avant de lire la suivante.

1. Il est recommandé d'exécuter ce kata avec un partenaire de jumelage et en écrivant des tests.

## Itération 1 ##

1. Tous les personnages, lorsqu'ils sont créés, ont :
    - Santé, à partir de 1000
    - Niveau, à partir de 1
    - Peuvent être Vivants ou Morts, à partir de Vivants (Vivants peut être un vrai/faux)

1. Les personnages peuvent infliger des dégâts aux personnages.
    - Les dégâts sont soustraits des points de vie
    - Lorsque les dégâts reçus dépassent les points de vie, les points de vie deviennent 0 et le personnage meurt.

1. Un personnage peut soigner un personnage.
    - Les personnages morts ne peuvent pas être soignés
    - La guérison ne peut pas porter la santé à plus de 1000

## Deuxième tour

1. Un personnage ne peut pas s'infliger de dégâts à lui-même.

1. Un personnage ne peut que se soigner lui-même.

1. Lorsqu'il inflige des dégâts :
    - Si la cible est supérieure de 5 niveaux ou plus à l'attaquant, les dégâts sont réduits de 50%
    - Si la cible est de 5 niveaux ou plus en dessous de l'attaquant, les dégâts sont augmentés de 50%.

## Troisième tour

1. Les personnages ont une attaque à portée maximale.

1. Les combattants *Melee* ont une portée de 2 mètres.

1. Les combattants *à distance* ont une portée de 2 mètres.

Traduit avec DeepL.com (version gratuite)
