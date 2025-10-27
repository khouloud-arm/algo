Objectif

Dans ce checkpoint, l’objectif est d’écrire un algorithme qui lit une phrase terminée par un point, caractère par caractère, et qui détermine :

La longueur de la phrase (nombre de caractères, y compris le point).

Le nombre de mots dans la phrase (en supposant que les mots sont séparés par un seul espace).

Le nombre de voyelles dans la phrase.

Approche utilisée

La lecture de la phrase se fait caractère par caractère.

Le dernier caractère de la phrase est un point, ce qui permet de savoir quand s’arrêter.

Trois variables compteurs sont utilisées :

compteur_longueur pour la longueur totale de la phrase.

compteur_mots pour le nombre de mots.

compteur_voyelles pour le nombre de voyelles.

À chaque itération (chaque caractère lu) :

On incrémente compteur_longueur.

Si le caractère est un espace, on incrémente compteur_mots.

Si le caractère est une voyelle (a, e, i, o, u), on incrémente compteur_voyelles.

Une fois le point rencontré, on ajoute 1 au compteur de mots pour inclure le dernier mot si nécessaire et on affiche les résultats.Remarques

Chaque caractère est traité individuellement pour permettre une lecture séquentielle.

Cette méthode est simple et efficace pour des phrases de taille modérée.

On suppose que les mots sont séparés par un seul espace et que la phrase se termine toujours par un point.
