Prise en main de PC2
==================

> Ok alors je veux bien faire les exercices mais comment je fais pour vous envoyer mes productions ?

----------------


Lancement du client PC2
-----------------------------------

Nommé pc2team par ses concepteurs , cet outil vous permettra de soumettre vos productions , le juge se chargera du reste et vous notifiera si votre réponse est correcte ou non.

> **Comment lancer pc2team ?**

> - Ouvrez un terminal et entrez ```cd /usr/local/pc2Client/bin && ./pc2team```
> - Une fenêtre vous invitera à entrez votre identifiant et votre mot de passe communiqués en début de séance.

--------
#### <i class="icon-upload"></i> Soumettre une solution

Depuis l'onglet **Submit run** sélectionnez le problème que vous souhaitez résoudre , puis le langage de votre solution ('**R**' ici) , cliquez ensuite sur **select** et sélectionnez le fichier contenant votre solution en **R**.
Il ne vous restera plus que à cliquer sur **Submit**

---------
#### <i class="icon-pencil"></i> Tester votre solution

Il est imprudent de soumettre une solution non testée , un guide décrit ci-dessous la façon de faire pour tester votre production.

> **Comment tester **
> 
> -  Récupérez un fichier test proposé dans l'énoncé et déposez le sur votre bureau
> - Ouvrez un terminal , et déplacez vous sur le répertoire où est posé votre solution exemple , si votre solution se trouve sur votre Bureau entrez ceci :  <br/>  ```cd ~/Bureau```
> - Pour exécuter votre solution vous devez la rendre *executable* , entrez dans le terminal la commande suivante  : <br/> ```chmod +x nom_de_la_solution.R```
> - Derniere étape , toujours sur le terminal , entrez la commande : ```Rscript nom_de_la_solution.R < nom_du_fichier_test.in```

Voila , si vous avez tout suivi vous devriez voir sur le terminal le résultat de votre solution
