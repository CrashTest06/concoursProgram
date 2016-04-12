# - Découpage binaire

  Déchiffrez le message qui se cache derriere cette suite de 0 et 1...
  Sur la première ligne du fichier vous trouverez le nombre de binaire à couper.
  A savoir que pour tous les exercices les fichiers d'entrées seront bien formés.
  
```
input  -> 0 1 0 0 0 1 1 1 0 1 0 0 1 1 1 1 0 1 0 0 1 1 1 1 0 1 0 0 0 1 0 0
```

```
output -> [1] "GOOD"
```

  
## - Exercices
  
1) **Ecrire sur une feuille la représentation décimal, héxadécimal ou octal du binaire que vous avez coupé en morceau de 8 au préalable.**

2) ** Ecrire un code R qui récupre le nombre binaire, qui le coupe en morceaux de longueur 8. Convertissez en décimal les plusieurs représentation binaires que vous avez découpé. Obtenez avec ces nombres décimaux le caractère ascii correspondant en utilisa **

3) **Nouveauté: le fichier contient désormais sur la deuxième ligne un suite d'entier positif. Ces entiers vont vous permettre de découper la binaire.** 
En effet, vous ne découperez plus par morceau de 8, mais par des morceaux de taille qui est indiqué par la suite d'entier présente sur la deuxième ligne du fichier.
Ecrivez un code R, qui découpe et traduit en ascii la suite de binaire selon la suite d'entier se trouvant sur la deuxième ligne du fichier.

```
input  -> 1 0 1 0 0 0 1 1 1 1 0 1 0 1 0 1 0 1 0 1 1 0 0 0 0 1 1 0 1 0 0 1
```

```
output -> [1] "(z*a)"
```
