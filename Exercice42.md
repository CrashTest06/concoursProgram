# Life, the Universe, and Everything

Votre programme va adopter une approche force brute pour trouver la réponse à *the Life, the Universe, and Everything*.
Plus précisément, vous devez réécrire des petits nombres lus depuis l'entrée standard vers la sortie standard.
Vous arrêterez ce traitement à la lecture du nombre 42.
Tous les nombres sont des entiers écrits avec un ou deux chiffres.

### Exemple

#### Input
```
1
2
88
42
99
```

#### Output
```
1
2
88
```

## PTEST - Question préliminaire

Soumettre un fichier texte contenant le résultat obtenu avec cette suite de nombres :
```
1
2
8
41
20
42
1
9
5
3
```


## TEST -  Life, the Universe, and Everything

Écrire un programme R respectant les spécifications ci-dessus.

### Conseils et éléments de code

Pour récupérer la suite de nombres, employez ce bout de code:
```R
flux=file("stdin","r")
suiteNombre=scan(file=flux, what=integer(), nline=L, quiet=TRUE)
```
À chaque itération, vous pouvez afficher sur la sortie standard à l'aide de `print` le nombre à afficher.
```R
while (length(suiteNombre) >= i)
{
...
print(suiteNombre[i]); # exemple
...
}
```


## STEST - Sum of Life, the Universe, and Everything

Plus difficile, à présent on souhaite s'arrêter lorsque la somme des 3 nombres suivants est égale à 42.

### Exemple

#### Input

```
1
3
5
7
1
1
40
9
8
```

#### Output

```
1
3
5
7
```
