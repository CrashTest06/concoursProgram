# - Exercice Découpage binaire

  Déchriffer le message qui se cache cette suite de 0 et 1 ...
  Vous serez informé de votre réussite selon le message que vous trouverez.
  
  Sur la première ligne du fichier vous trouverez le nombre de binaire à couper.
  Il faut découper cette suite de 0 et de 1 par morceaux de longueur 8.
  Ensuite il vous faudra convertir cette suite en hexadécemial, en octal ou en décimal afin de trouver la correspondance dans la table Ascii.
  
  
  
  <br/> &nbsp;&nbsp;&nbsp; Exemple:
    <br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; input  -> 0 1 0 0 0 1 1 1 0 1 0 0 1 1 1 1 0 1 0 0 1 1 1 1 0 1 0 0 0 1 0 0
    <br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;
    <br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; output -> [1] "GOOD"
  
  
  
  1) Ecrire sur une feuille la représentation décimal, héxadécimal ou octal du binaire que vous avez coupé en morceau de 8 au préalable.
  
  2) Ecrire un code R qui récupère le nombre binaire, qui le coupe en morceau de longueur 8.
     Convertissez en décimal les plusieurs représentations binaires que vous avez découpé.
     Obtenez avec ces nombres décimaux le caractère ascii correspondant en utilisant: ```IntToUtf8(arg)```
     
  3) Nouveauté: le fichier contient désormais sur la deuxième ligne un suite d'entier positif. Ces entiers vont vous permettre de découper la binaire.
     En effet, vous ne decouperez plus par morceau de 8, mais par des morceaux de taille qui est indiqué par la suite d'entier présente sur la deuxième ligne du fichier.
     Ecrivez un code R, qui decoupe et traduit en ascii la suite de binaire selon la suite d'entier se trouvant sur la deuxième ligne du fichier.
  
  <br/> &nbsp;&nbsp;&nbsp; Exemple:
    <br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; input  -> 1 0 1 0 0 0 1 1 1 1 0 1 0 1 0 1 0 1 0 1 1 0 0 0 0 1 1 0 1 0 0 1
    <br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp; 6 13 19 26 32
    <br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; output -> [1] "(z*a)"
    
    Bonne chance !
