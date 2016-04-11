# - TEST - Life, the Universe, and Everything
Your program is to use the brute-force approach in order to find the Answer to Life, the Universe, and Everything. More precisely... rewrite small numbers from input to output. Stop processing input after reading in the number 42. All numbers at input are integers of one or two digits.

### -Example

<pre><code>Input:
1
2
88
42
99
</code></pre>


<pre><code>Output:
1
2
88
</code></pre>

### - Exercices

+ 1) Ecrire sur feuille le resultat donné avec cette suite de nombres donnée: 1 2 8 41 20 42 1 9 5 3

+ 2) Ecrire cette fois ci le programme en R qui traitera le probleme


Pour récuperer la suite de nombres , employez ce bout de code:
```R
flux=file("stdin","r")
suiteNombre=scan(file=flux, what=integer(), nline=L, quiet=TRUE)
```

A chaque iteration vous devez afficher sur la sortie standard à l'aide de print le nombre à afficher.
```R
while (length(suiteNombre) >= i)
{
...
print(nombre_a_afficher); # exemple
...
}
```

+ 3) Plus dur , à present on souhaite afficher 42 lorsque la somme des 3 derniers elements lus fait 42.

Exemple:

<pre><code>Input:
1
3
5
7
1
1
40
9
8
</code></pre>


<pre><code>Output:
1
3
5
7
1
1
42
42
42
</code></pre>
