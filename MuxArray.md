# MuxArray

Ce problème demande la réalisation du produit de deux tableaux passés dans l'entrée standard:
<br/>

+ **Exemple**

![Alt text](/ressources/exemple2MuxArray.PNG)

<br/><br/><br/>

###Entrée & sortie

+ **Entrée pour les exercices MUXA2 et MUXA3**

```R
flux=file("stdin","r")
tableau1=scan(file=flux, what=integer(), nline=1, quiet=TRUE)
tableau2=scan(file=flux, what=integer(), nline=2, quiet=TRUE)
```

+ **Sortie pour les exercices MUXA2 et MUXA3**

```R
cat(tableau_resultat)
```


## Exercices

+ **1) MUXA1 - Faire sur feuille , le produit des deux tableaux suivants:**
<br/><br/>
![Alt text](/ressources/exempleExo1MuxArray.PNG) <br/>
Envoyez un code R affichant simplement le contenu du résultat , vous ferez un cat en séparant chaque nombre par un espace:
```R
# exemple
cat("9 16 21 24 25 24");
```

<br/><br/>
+ **2) MUXA2 - Ecrivez un algorithme en R prenant en entrée les deux tableaux , et affichant le résultat.
On considère que les tableaux passés en paramètre ne sont jamais vides et ont strictement la meme taille.**

  + **Exemple**
    + **Input**
      
      ```R
      1 2 3 4
      4 3 2 1
      ```
      
    + **Output**
      ```R
      1 4 9 16
      ```

> *aide*
> - Deux tableaux de meme taille facilite la tache au niveau des indices


<br/><br/>
+ **3) MUXA3 - Plus dur , si vous avez reussi le 2 , on vous demandera d'afficher les élements pairs du tableau TableauRes.
Attention les tableaux peuvent être vides !**

Vous afficherez le tableau contenant le resultat

  + **Exemple**
    + **Input**
      
      ```R
      1 2 3 4
      4 3 2 1
      ```
      
    + **Output**
      ```R
      4 16
      ```


Attention , si un des tableaux est vide ,le programme doit **seulement** afficher ```VIDE```
```R
cat("VIDE");
```


