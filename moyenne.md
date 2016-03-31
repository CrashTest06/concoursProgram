# - Exercice Moyenne Pondérée
Calculer la moyenne pondéré à partir deux listes, celle des notes et celle des coefficients.
<br/> &nbsp;&nbsp;&nbsp; Exemple:

<br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; input  -> 8 12 10 10 10
<br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;  4 3 1 1 1
<br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; output -> 9.8
       
1) Calculez la moyenne pondérée des notes : 18 18 12 11 7
avec leur coefficients respectives : 6 2 4 4 1
    
```
R
print("mon resultat")
```
      
2) A partir du squelette suivant, calcule la moyenne non pondérées d'une liste de notes récupérée en entré.
      
```
R
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
      
3) A partir du squelette suivant, calculez la moyenne pondérée d'une suite de notes, </br> 
les note se trouvant sur la première ligne de l'entrée et leur coefficient respectives se trouvant sur la deuxième.
      
```
R
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
