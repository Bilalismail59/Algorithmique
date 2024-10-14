# Algorithmique

> **une blague de dev :**
> calculer la myenne d'une liste de nombres et rechercher la valeur maximale
> dans cette liste

## Calcul de la moyenne

### Langage naturel

```text
Définir une liste de nombres
Initialiser une variable pour stocker la somme des nombres
Parcourir la liste et ajouter chaque nombre à la somme
Diviser la somme par le nopmbre d'elements dans la liste
```

### Pseudo-code

```text
Début
    list ← [1, 78, 2, 35]
    somme ← 0

    POUR CHAQUE nombre DANS liste
        somme ← somme + nombre
    FIN pour

    moyenne ← somme / nombre éléments de liste

    AFFICHER "la moyenne est : " + moyenne
FIN
``` 

## Recherche du maximum

```text
Définir une liste de nombres
Initialiser une variable pour stocker la nombre maximal (premier élément)
Parcourir la liste
Si l'élément actuel est plus grand que le nombre maximal, le remplacer par cette valeur
Afficher le nombre maximal
```

```text
Début
    list ← [1, 78, 2, 35]
    max ← liste[0]

    POUR CHAQUE nombre DANS liste
        Si nombre > max
            ALORS max ← nombre
        FIN SI
    FIN POUR

    AFFICHER *le nombre maximal est : " + max
FIN
```

## FUSION


```text
Début
    list ← [1, 78, 2, 35]
    max ← liste[0]

    POUR CHAQUE nombre DANS liste
        Si nombre > max
            ALORS max ← nombre
        FIN SI
    FIN POUR

    AFFICHER *le nombre maximal est : " + max
FIN
```

