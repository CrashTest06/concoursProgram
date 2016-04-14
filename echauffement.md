# Equation du second degrès

Réaliser un simple programme évaluant la fonction ax² + bx + c

L'idée est que vous récupériez en entrée quatres paramètres (a,b,c,x) et appliquiez l'équation.

## - Exemple:

input : ```x = 1 ; a = 2 ; b = 4 ; c = 6```

output : ```14``` => (2 * 1)² + (4 * 1) + 6

## - Entrée & Sortie

+ *Entrée*

Pour récuperer les paramètres , employez ces lignes de code au debut de votre solution
```R
flux=file("stdin","r");
listeParametres=scan(file=flux, what=integer(), nline=1, quiet=TRUE)
x <- listeParametres[1];
a <- listeParametres[2];
b <- listeParametres[3];
c <- listeParametres[4];
```

+ *Sortie*

Vous afficherez le résultat de votre solution avec l'instruction ``` cat ```
```R
#exemple

cat(resultat);
```

## - Exercices

+ 1) **EQUA-1 - Réaliser un programme en R évaluant l'équation en fonction des paramètres mentionnés plus haut.**

Voici une amorce pour votre solution:

```R
flux=file("stdin","r");
listeParametres=scan(file=flux, what=integer(), nline=1, quiet=TRUE)
x <- listeParametres[1];
a <- listeParametres[2];
b <- listeParametres[3];
c <- listeParametres[4];

##ICI VOTRE CODE

cat(votre_resultat)
```

+ 2) **EQUA-2 - Produisez un programme en R calculant le discrimant de l'équation du second degrès**

> - **indication**
> - la formule du discrimant : b² - (4*a*c)

Voici une amorce pour votre solution:

```R
flux=file("stdin","r");
listeParametres=scan(file=flux, what=integer(), nline=1, quiet=TRUE)
a <- listeParametres[1];
b <- listeParametres[2];
c <- listeParametres[3];

##ICI VOTRE CODE

cat(votre_resultat)
```

