# - Exercice Epluchage

  Le but est de compter le nombre d'occurences des chiffres de l'ensemble [1,9] qui apparaissent dans un nombre n et d'en faire un nouveau nombre m.
  Ce nombre m ne doit pas etre construit en fonction de l'ordre d'apparition des chiffres rencontrés, mais l'ordre numérique croissant 1,2,..,9.
    <br/> &nbsp;&nbsp;&nbsp; Exemple:
    <br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; input  -> 111112229 
    <br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; output -> 531
    <br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; input  -> 122121911 
    <br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; output -> 531
    <br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; input  -> 311 
    <br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; output -> 21
            
  1) Envoyer le resultat pour n = 685415111
 <br/> ``` print("mon resultat") ```<br/>
  2) Ecrire le code R qui renvoie le tableau d'occurences des chiffres d'un nombre récupérer en entré grâce au code INPUT-A1 .
  <br/>
  #### Recuperation de l'entrée
  <br/>``` flux=file("stdin","r")``` 
  <br/>``` suiteNombre=scan(file=flux, what=integer(), nline=L, quiet=TRUE)``` 
  
  <br/> ``` print("mon resultat") ```<br/>
  3) Ecrire le code R qui renvoie le nombre créé à l'aide du nombre d'occurences des chiffres d'un nombre récupérer grâce au code INPUT-A1.
