# Life, the Universe, and Everything

Votre programme va adopter une approche force brute pour trouver la réponse à *the Life, the Universe, and Everything*.
Plus précisément, vous devez réécrire des petits nombres lus depuis l'entrée standard vers la sortie standard.
Vous arrêterez ce traitement à la lecture du nombre 42.
Tous les nombres sont des entiers écrits avec un ou deux chiffres.

+ **Exemple**

  + **Input**
  
    ```
    1 2 88 42 99
    ```

  + **Output**
  
    ```
    1
    2
    88
    ```

## Entrée & sortie

+ **Entrées**
  
  ```R
  flux=file("stdin","r")
  suiteNombre=scan(file=flux, what=integer(), nline=1, quiet=TRUE)
  ```
+ **Sortie**

  ```R
  cat(le_chiffre_a_afficher,'\n')
  ```  

## Exercices

+ **1) PTEST - Question préliminaire**

  Sur une feuille , résolvez la questions
  Vous soumettrez un programme R affichant , avec le code fourni dans la section **Sortie** , le résultat obtenu avec cette suite de nombres :
    ```
    1
    2
    8
    41
    20
    42
    1
    9
    5
    3
    ```
    
Le résultat affiché doit respecter le format attendu presenté dans la section **Output**


+ **2) TEST -  Life, the Universe, and Everything**

  Écrivez le programme en R.


  + **Exemple**
    + **Input**
    
      ```
      1 2 88 42 99
      ```
    + **Output**
    
      ```
      1
      2
      88
      
      ```

+ **3) STEST - Sum of Life, the Universe, and Everything**

  Plus difficile, à présent on souhaite s'arrêter lorsque la somme des 3 nombres suivants est égale à 42.
  
  + **Exemple**
  
    + **Input**
    
      ```
      1 3 5 7 1 1 40 9 8
      ```
    
    + **Output**
    
      ```
      1
      3
      5
      7
      
      ```
