# S02E01 - Algorithique > introduction

## Enoncé 

### Objetif

Écrire un algorithme en pseudo-code qui effectue un compte à rebours à partir d’un nombre donné jusqu’à zéro, en affichant chaque nombre.

### Etapes

- Initialisation :
    - Créer une liste de blagues de développeurs.

- Sélection : 
    - Choisir une blague aléatoire dans la liste et l'afficher.

## Correction

```text
DÉBUT

    // Étape 1 : Initialisation
    Afficher "Entrer un nombre entier positif : "
    Lire nombre

    // Étape 2 : Vérification du nombre
    Si nombre < 0 ALORS
        Afficher "Le nombre doit être positif."
        Fin du programme
    Fin Si

    // Étape 3 : Boucle de compte à rebours
    Pour i allant de nombre à 0 avec un pas de -1 FAIRE
        Afficher i
    Fin Pour
 FIN SI

FIN
```
## Bonus

Redemander la saisie utilisateur si erreur → TANT QUE









