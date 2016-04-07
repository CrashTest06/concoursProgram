# 	Exercice Moyenne Pondérée

### ENNONCÉ


Calculer la moyenne pondéré à partir deux listes, une contenant les notes et une les coefficients de celles-ci. 
  
  
  
### EXEMPLES
  
-	Exemple :
	-	input ligne 1  -> 15 10 20 5 2 10
	-	input ligne 2 -> 42 8 1 6 5 3 
    -	output -> 8

*La ligne 1 correspond a la liste contenant les notes*

*La ligne 2 correspond a la liste contenant les coefficient*

### QUESTIONS


1.	 Calculez la moyenne pondérée des notes: 18 18 12 11 7 avec leur coefficients respectives: 6 2 4 4 1


  ```R
	#### Envoyer le resultat
	print("mon resultat") 
 ```
 
2.	 A partir du squelette suivant, calcule la moyenne non pondérées d'une liste de notes récupérée en entré.




	-	Exemple:
		-	input  -> 15 16 12 9 12 14
   		-	output -> 13 




  ```R
    #### Recuperation de la liste des notes
    flux=file("stdin","r")
    notes=scan(file=flux, what=integer(), nline=1, quiet=TRUE)

    #### ECRIRE 
    #### LE 
    #### CODE

    #### Affichage non scientifique 
    #### /!\ A UTILISER
    options("scipen"=100, "digits"=4)

    #### Envoyer le resultat
    print("mon resultat")
   
   ```
   
   
3.	 A partir du squelette suivant, calculez la moyenne pondérée d'une suite de notes, les note se trouvant sur la première ligne de l'entrée et leur coefficient respectives se trouvant sur la deuxième.

  ```R
      #### Recuperation de la liste des notes
    flux=file("stdin","r")s
    notes=scan(file=flux, what=integer(), nline=1, quiet=TRUE)
    coeff=scan(file=flux, what=integer(), nline=2, quiet=TRUE)

    #### ECRIRE 
    #### LE 
    #### CODE

    #### Affichage non scientifique 
    #### /!\ A UTILISER
    options("scipen"=100, "digits"=4)

    #### Envoyer le resultat
    print("mon resultat")
   
   ```
