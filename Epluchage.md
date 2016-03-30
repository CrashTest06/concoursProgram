# - Exercice Epluchage

  Le but est de compter le nombre d'occurences des chiffres de l'ensemble [1,9] qui apparaissent dans un nombre N et d'en faire un nouveau nombre M.
  M ne doit pas etre construit en fonction de l'ordre d'apparition des chiffres rencontrés, mais dans cette ordre numérique croissant 1,2,..,9.
    <br/> &nbsp;&nbsp;&nbsp; Exemple:
    <br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; input  -> 111112229 
    <br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; output -> 531
    <br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; input  -> 122121911 
    <br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; output -> 531
    <br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; input  -> 311 
    <br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; output -> 21
            
  1) Envoyer le resultat pour n = 685415111
  ```R
 #### Envoyer le resultat
 print("mon resultat") 
 ```
  2) Ecrire le code R qui renvoie M à partir du N récupérer en entrée
    <br/> &nbsp;&nbsp;&nbsp; Exemple:  
    <br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; input  -> 111112229 
    <br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; output -> 531
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
  3) Reprendre le code de la question 2, renvoyez M maintenant en comptant le nombre d'occurance du chiffre 0.
    <br/> M doit etre construire cette ordre numérique 1,2,..,9,0.
    <br/> &nbsp;&nbsp;&nbsp; Exemple:
    <br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; input  -> 1000111192229 
    <br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; output -> 5323
