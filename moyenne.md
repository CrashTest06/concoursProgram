# Moyenne Pondérée

  Le but de cet exercice est de calculer la moyenne pondérée à partir d'une liste de notes et d'une liste de coefficients.

  
+ **Exemple**

	+ **Input**
		
		```R
	 	15 10 20 5 2 10
	 	4 8 1 6 5 3 
		```
	
	+ **Output**
	
		```R
 		8.000
		```

## Entrée & sortie

+ **Entrée**

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
     flux=file("stdin","r")
     notes=scan(file=flux, what=integer(), nline=1, quiet=TRUE)
     coeff=scan(file=flux, what=integer(), nline=2, quiet=TRUE)
    ```
      A savoir que pour tous les exercices les fichiers d'entrées seront bien formés.

+ **Sortie**
	
	```R
  cat(res);
  ```
  **/!\ Le résultat doit être arrondi à 3 chiffres après la virgule (voir exemple)**
  
## Exercices
  
+ **1) MOY1 - Calculer à la main la moyenne pondérée. Envoyez le résultat avec un code R utilisant la fonction ```cat(arg)```**
   **/!\ Le résultat doit être arrondi à 3 chiffres après la virgule (voir exemple)**

	+ **Exemple**
  	
		+ **Input**
			
			
			```R
		  	12 15 6 4
			 2 4 1 3
			```
				
		+ **Output**
		
			```R
	   		9.500
	   		```

	+ ***A vous de jouer avec cet input***
	
		
		+ **Input**
		
			```R
			15 13 12 12
			2 4 1 3
			`````

+ **2) MOY2 -  Pour commencer vous allez calculer la moyenne non pondérée:
Ecrire le code R en utilisant le squelette suivant qui renvoie la moyenne non pondérée à partir de la liste de notes récupérée en entrée .**
   **/!\ Le résultat doit être arrondi à 3 chiffres après la virgule (voir exemple)**
   
  + **Exemple**
  	
		+ **Input**
			
			```R
		  	10 12 8
			```
			
		+ **Output**
		
			```R
   			10.000
			```


+ **3) MOY3 -  Calculez maintenant la moyenne pondérée: 
Ecrire le code R en utilisant le squelette suivant qui renvoie la moyenne pondérée à partir de la liste de notes et de la liste des coefficients récupérées en entrée .**
 **/!\ Le résultat doit être arrondi à 3 chiffres après la virgule (voir exemple)**
    
	+ **Exemple**
	
		+ **Input**
			```R
			15 10 20 5 2 10
			42 8 1 6 5 3 
			```
		
		+ **Output**
			
			```R
   			8.000
			```

