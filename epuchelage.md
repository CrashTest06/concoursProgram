# - Epluchage

Le but est de compter le nombre d'occurences des chiffres de l'ensemble [1,9] qui apparaissent dans un nombre positif N et d'en faire un nouveau nombre M.
  M ne doit pas etre construit en fonction de l'ordre d'apparition des chiffres rencontrés, mais dans cette ordre numérique croissant 1,2,..,9.
  
  
  
#### Exemple
```R
	input  -> 111112229
```
```R
	output -> 531 
```

## - Entrée & sortie

+ **Entrée**:

    ```R
    flux=file("stdin","r")
    suiteNombre=scan(file=flux, what=integer(), nline=L, quiet=TRUE)
    ```
+ **Sortie**:

  ```R
  res=intToUtf8(mon_vecteur)
  cat(res)
  ```

## - Exercice


+ **1) Envoyer le résultat pour n = 685415111.**

	```R
	cat("mon resultat") 
	```
 
+ **2) Ecrire le code R qui renvoie M à partir du N récupérer en entrée.**

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
