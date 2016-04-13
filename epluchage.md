# - Epluchage

Le but est de compter le nombre d'occurences des chiffres de l'ensemble [1,9] qui apparaissent dans un nombre positif N et d'en faire un nouveau nombre M.
  M ne doit pas etre construit en fonction de l'ordre d'apparition des chiffres rencontrés, mais dans cette ordre numérique croissant 1,2,..,9.
  
  
  
#### Exemple
```R
	input  -> 11449222
```
```R
	output -> 2321
```
car il y a **deux** occurences du nombre 1 , **trois** occurences de 2 , **deux** occurences de 4 , et enfin **une** occurence de 9 , ce qui donne bien : ```2321```

## - Entrée & sortie

+ **Entrée**:

    ```R
    flux=file("stdin","r")
    suiteNombre=scan(file=flux, what=integer(), nline=L, quiet=TRUE)
    ```
+ **Sortie**:

  ```R
  options("scipen"=100, "digits"=4)
  cat(vote_resultat)
  ```

## - Exercice


+ **1) Dans un premier temps calculez le résultat à la main et envoyez-le avec un code R utilisant la fonction```cat(arg)```.**
#### Exemple

	```R
	input  -> 111112229
	```
	```R
	Code R -> cat(531) 
	```
	```R
	output -> 531 
	```
 ***A vous de jouer avec cet input:***
	```R
	input -> 685415111
	```
	
<br/><br/>

+ **2) Ecrire le code R qui renvoie M à partir du N récupérer en entrée.**

> **aide**
> - aidez vous d'un tableau pour memoriser les occurences


```R
	#### Recuperation du nombre N en entrée
	flux=file("stdin","r")
	suiteNombre=scan(file=flux, what=integer(), nline=L, quiet=TRUE)
  
	#### ECRIRE 
	#### LE 
	#### CODE
   
	#### Affichage non scientifique 
	#### /!\ A UTILISER
	options("scipen"=100, "digits"=4)
   
	#### Envoyer le resultat
	print("mon resultat")
   
```
<br/><br/><br/>   
+ **3) Reprendre le code de la question 2, renvoyez M maintenant en rajoutant aussi le nombre d'occurance du chiffre 0. M doit etre construire cette ordre numérique 1,2,..,9,0.**

#### Exemple:
```R	
	input  -> 1000111192229
```
```R
   	output -> 5323 
```




**ce code la il faut que tu le place bien:**

```R
	input  -> 122121911
```
```R
	output -> 5311
```

```R
	input  -> 311
```
```R
	output -> 21
```
