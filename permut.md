# 	Exercice Permutation

### ENONCÉ


Verifier si une suite de nombre L1 est une permutation ambigüe d'une autre liste L2 
  
  
  
### EXEMPLES
  
-	Exemple :
	-	input ligne 1  -> 2 3 4 5 1 
	-	input ligne 2 ->  5 1 2 3 4 
    -	output -> TRUE

*La ligne 1 correspond a la liste L1*

*La ligne 2 correspond a la liste L2*

### QUESTIONS


1.	 Envoyer le résultat pour les listes L1: 3 8 5 10 9 4 6 1 7 2 et L2: 8 10 1 6 3 2 9 7 5 4


  ```R
	#### Envoyer le resultat
	print("mon resultat") 
 ```
 
2.	 A partir du squelette suivant, écrire un code en R qui vérifie si une liste L1 est la liste renversée de L2.





	-	Exemple:
		-	input  -> 15 16 12 9 12 14
   		-	output -> 14 12 9 12 16 15




  ```R
	#### Recuperation des deux listes en entrée
	flux=file("stdin","r")
    L1=scan(file=flux, what=integer(), nline=1, quiet=TRUE)
    L2=scan(file=flux, what=integer(), nline=2, quiet=TRUE)

    #### ECRIRE 
    #### LE 
    #### CODE

	#### Envoyer le resultat
    print("mon resultat")
   
   ```
   
   
3.	 3) A partir du même squelette, vérifiez si une liste L1 est la permutation ambigüe de la liste L2

