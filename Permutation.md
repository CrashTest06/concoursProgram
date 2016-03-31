# - Exercice Permutation

  Verifier si une suite de nombre L1 est une permutation ambigüe d'une autre liste L2
    <br/> &nbsp;&nbsp;&nbsp; Exemple:
    <br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; input  -> 2 3 4 5 1
    <br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;  5 1 2 3 4
    <br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; output -> TRUE
    
    1) Envoyer le resultat pour les listes L1: 3 8 5 10 9 4 6 1 7 2 et L2: 8 10 1 6 3 2 9 7 5 4
    ```
    R
    print("mon resultat")
    ```
    2) A partir du squellete suivant, ecrire un code en R qui verifie si une liste L1 est la liste renversée de L2.
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
    3) A partir du même squelette, verifiez si une liste L1 est la permutation ambigüe de la liste L2

