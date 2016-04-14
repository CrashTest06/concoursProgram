# Epluchage to Int

L'epluchage consiste à compter le nombre d'occurence d'un chiffre dans un nombre N (exemple dans 131, le chiffre 1 apparait deux fois)

Le but de cet exercice est de manipuler ces occurences afin de former un nouveau nombre M. Pour former M, on ne concatenera pas les occurences (superieures à zero) selon l'ordre d'apparition du chiffre mais selon l'ordre croissant.

  
  
  
## Exemple


	+ **Input**
	
		```
		 21112129
		```

	+ **Output**
	
		```
		 431 
		```
		
	Dans cette exemple nous pouvons voir qu'il y a **quatre** occurences du chiffre 1, **trois** du chiffre 2 et **une** occurence de 9



## Entrée & sortie

	+ **Entrée**:
	
	    ```R
	    # On recupere un tableau de caracteres en entrée
	    stream <- file("stdin","r")
	    n <- scan(file=stream, what=character(), n=1, quiet=TRUE)
	    ```
	+ **Sortie**:
	
	    ```R
	    cat(vote_resultat)
	    ```

## - Exercice


+ **1) EPLUCHE1 - Dans un premier temps calculez le résultat à la main et envoyez-le avec un code R utilisant la fonction```cat(arg)```.**
##### Exemple

    ###input

    ```R
   1101112229
    ```
    ###code R    
    ```R
   cat(1531) 
    ```
    ###output
    ```R
   1531 
    ```
     ***A vous de jouer avec cet input:***
     ###input
    ```R
   685415111
    ```
 
+ **2) EPLUCHE2 - Ecrire le code R qui renvoie M à partir du N récupéré en entrée à partir du squelette suivant.**

	```R
    # On recupere un tableau de caracteres en entrée
    stream <- file("stdin","r")
    n <- scan(file=stream, what=character(), n=1, quiet=TRUE)
  
	#### CODE R
   
	#### Envoyer le resultat
	cat("mon resultat")
   
	```
   
+ **3) EPLUCHE3 - Reprendre le code de la question 2, renvoyez M maintenant en excluant cette fois-ci le nombre d'occurence du chiffre 0.**

    ##### Exemple:
    ###input
    ```R	
   1100011192229
    ```
    ###output
    ```R
   532 
    ```



