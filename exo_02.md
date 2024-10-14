# S02E01 - Algorithique > introduction

## Énoncé 

### Objetif

Écrire un algorithme qui choisit aléatoirement une blague de développeur à afficher.

### Étapes

- Initialisation
    -Créer une liste de blagues de développeurs.

- Sélecction :
    - Choisir une blague aléatoire dans la liste et l'afficher.

## Correction

```text
DÉBUT

    // Étape 1 : Initialisation
    Créer une liste de blagues :
        blagues ← ["Pourquoi les programmeurs préfèrent-ils le noir ? Parce que c'est plus rapide.",          "Il y a 10 types de personnes dans le monde : ceux qui comprennent le binaire et ceux qui ne le comprennent pas.",                  "Un programmeur entre dans un bar et commande 1 bière... puis 10 bières, puis 111 bières."]
    
    // Étape 2 : Sélection d'une blague aléatoire
    longueur ← longueur de la liste blagues
    index_aleatoire ← Générer un nombre aléatoire entre 0 et longueur - 1
    
    // Étape 3 : Affichage de la blague sélectionnée
    Afficher blagues[index_aleatoire]
FIN
```

