# Permutation Inverse
 
Il y a permutation inverse sur une liste L1 si pour chaque élement i de cette liste, se retrouve à la i-éme position de la liste L2 crée par cette permutation.
Le but de cet exercice est de vérifier si une suite de nombre L1 est une permutation inverse d'une autre liste L2.



+ **Exemple**:

  + **Input**
  
     ```R
     2 3 4 5 1 
     5 1 2 3 4
     ```
    
  + **Output**
  
     ```R
     TRUE
     ```
 
*La ligne 1 correspond a la liste L1*
*La ligne 2 correspond a la liste L2*



## Entrée & sortie

+ **Entrée**:
  + **Exercice 2**
     Sur la première ligne du fichier d'entrée vous trouverez la liste L1 
     et sur la deuxième ligne L2.

    ```R
     flux=file("stdin","r")s
     L1=scan(file=flux, what=integer(), nline=1, quiet=TRUE)
     L2=scan(file=flux, what=integer(), nline=2, quiet=TRUE)
    ```
    
  + **Exercice 3**
     Sur la première ligne du fichier d'entrée vous trouverez la liste L1 
     et sur la deuxième ligne L2.
  
     ```R
     flux=file("stdin","r")
     L1=scan(file=flux, what=integer(), nline=1, quiet=TRUE)
     L2=scan(file=flux, what=integer(), nline=2, quiet=TRUE)
    ```
      A savoir que pour tous les exercices les fichiers d'entrées seront bien formés.

+ **Sortie**:

    ```R
    # TRUE : si L1 est une permutation inverse de L2
    # FALSE sinon
    cat(votre_resultat) # TRUE ou FALSE
    ```

## - Exercice


+ **1) PERMUT-1 - Dans un premier temps calculez le résultat à la main et envoyez-le avec un code R utilisant la fonction```cat(arg)```.**
	+ **Exemple**

		+ **Input**
		
			```R
			1 4 5 2 3 6
			1 2 3 4 5 6
			```
		
		+ **Code R**    
		
			```R
			cat(FALSE) 
			
			```
		+ **Output**
		
			```R
			FALSE 
			 ```
			 
	+ ***A vous de jouer avec cet input***
		
		+ **Input**
			
			```R
			3 8 5 10 9 4 6 1 7 2
			8 10 1 6 3 2 9 7 5 4
			```
 
+ **2) PERMUT-2 - Permutation renversée:
	Pour commencer ecrivez un code R à partir du squelette suivant, qui vérifie si la liste L1 est la liste renversée de la liste L2 toute deux récupérées en entrée.
    Renvoyez ```TRUE``` ou ```FALSE```**

	+ **Exemple**

		+ **Input**
		
			```R
			15 16 12 9 12 14
    			14 12 9 12 16 15
			```

		+ **Output**
		
			```R
			TRUE 
			 ```


+ **3)  PERMUT-3 - Permutation inversée:
	 Ecrivez le code R à partir du squelette précédent, qui verifie si la liste L1 est la liste L2 par permutation inversée, les deux listes sont récupérées en entrée.
     Renvoyez ```TRUE``` ou ```FALSE```**

    ### Exemple:
    ###input
    ```R	
   2 3 4 5 1 
   5 1 2 3 4 
    ```
    ###output
    ```R
   TRUE
    ```



