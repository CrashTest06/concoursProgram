# - Moyenne Pondérée

  Le but de cet exercice est de calculer la moyenne pondérée à partir d'une liste de notes et d'une liste de coefficients.

  
####  Exemple:
###input
```R
 15 10 20 5 2 10
 4 8 1 6 5 3 
```
###output
```R
 8
```

## - Entrée & sortie

+ **Entrée**:
  + **Exercice 2**
     Sur la première ligne du fichier d'entrée vous trouverez la liste des notes   

    ```R
     flux=file("stdin","r")
     notes=scan(file=flux, what=integer(), nline=1, quiet=TRUE)
    ```
    
  + **Exercice 3**
     Sur la première ligne du fichier d'entrée vous trouverez la liste des notes 
     et sur la deuxième ligne celle des coefficients.
  
     ```R
     flux=file("stdin","r")s
     notes=scan(file=flux, what=integer(), nline=1, quiet=TRUE)
     coeff=scan(file=flux, what=integer(), nline=2, quiet=TRUE)
    ```
      A savoir que pour tous les exercices les fichiers d'entrées seront bien    	   formés.

+ **Sortie**:

    ```R
    cat(sprintf("%f",res));
    ```
  
## - Exercices
  
+ **1) Calculer à la main la moyenne pondérée. Envoyez le résultat avec un code R utilisant la fonction ```cat(arg)```**
  
  #### Exemple:
  ###input
	```R
   12 15 6 4
   2 4 1 3
	```
    ###code R
	```R
   cat(sprintf("%f",9.5));
	```
    ###output
	```R
   9.5 
	```
 ***A vous de jouer avec cet input:***
    ###input
	```R
   15 13 12 12
   2 4 1 3
	```

+ **2) Pour commencer vous allez calculer la moyenne non pondérée:
	Ecrire le code R en utilisant le squelette suivant qui renvoie la moyenne non pondérée à partir de la liste de notes récupérée en entrée .**
  
    #### Exemple:
    ###input
    ```R
   10 12 8
	```
   ###output 
    ```R
   10
	```
    
    ```R
    # On recupere un tableau d'integer en entrée
    flux=file("stdin","r")
    notes=scan(file=flux, what=integer(), nline=1, quiet=TRUE)
  
	#### CODE R
   
	#### Envoyer le resultat
    cat(sprintf("%f","mon resultat"));
   
	```

+ **3) Calculez maintenant la moyenne pondérée: 
	 Ecrire le code R en utilisant le squelette suivant qui renvoie la moyenne pondérée à partir de la liste de notes et de la liste des coefficients récupérées en entrée .**
     
######Exemple:

    ###input
    ```R
   15 10 20 5 2 10
   42 8 1 6 5 3 
    ```
    ###output
    ```R
   8
    ```

    ```R
    # On recupere deux tableaux d'integer en entrée
    flux=file("stdin","r")
    notes=scan(file=flux, what=integer(), nline=1, quiet=TRUE)
    coeff=scan(file=flux, what=integer(), nline=2, quiet=TRUE)  
    
	#### CODE R
   
	#### Envoyer le resultat
    cat(sprintf("%f","mon resultat"));
   
	```


