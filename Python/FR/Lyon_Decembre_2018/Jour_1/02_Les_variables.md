## Variables et premiers éléments de syntaxe

---

### Qu'est ce qu'une variable ?

C'est une donnée de votre programme, stockée dans votre ordinateur.

C'est un code alpha-numérique que vous allez lier à une donnée de votre programme,
afin de pouvoir l'utiliser à plusieurs reprises et faire des calculs un peu plus intéressants avec.

---

### Comment ca marche ?

Le plus simplement du monde. Vous allez dire à Python :

« je veux que, dans une variable que je nomme `age`, tu stockes mon âge, pour que je puisse le retenir (si j'ai la mémoire très courte), l'augmenter (à mon anniversaire) et l'afficher si besoin est ».

---

### Comment utiliser une variable en Python

En Python, pour donner une valeur à une variable, il suffit d'écrire `nom_de_la_variable = valeur`.

---

### Qu'est ce que on peux faire avec ?

On peux y stocker:

- Des `str`
    - `str` en Python, ou `string` en anglais, signifie une chaine de charactere (ce qui est entre `'` ou `"`)
- Des `int`
    - `int` en Python, ou `integer` en anglais, corresponds a un nombre entier
- Et bien d'autres que nous allons découvrir par la suite

---

### Comment stocker dans une variable une string ?

```bash
$ python3 
Python 3.6.7 (default, Oct 22 2018, 11:32:17) 
[GCC 8.2.0] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> ma_variable = "Hello World"
>>> ma_variable
'Hello World'
>>> ma_variable = "Bonjour"
>>> ma_variable
'Bonjour'
```

---

### Comment stocker dans une variable un integer ?

```bash
$ python3 
Python 3.6.7 (default, Oct 22 2018, 11:32:17) 
[GCC 8.2.0] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> ma_variable = 42
>>> ma_variable
42
>>> ma_variable = 21
>>> ma_variable
21

```

---

### Affichier une variable

```bash
$ python3 
Python 3.6.7 (default, Oct 22 2018, 11:32:17) 
[GCC 8.2.0] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> ma_variable = "Hello World"
>>> print(ma_variable)
Hello World
>>>
>>>
>>> ma_variable = 42
>>> print(ma_variable)
42
```

---

### Note sur l'interpreteur Python et l'affichage des variables

Dans l'interpreteur en mode interactif, ecrire juste le nom de la variable affichera sa valeur.

Essayez

---

### Note sur l'interpreteur Python et l'affichage des variables

Maintenant faites la meme chose dans un fichier `.py` et executez le

---

### Note sur l'interpreteur Python et l'affichage des variables

L'interpreteur Python en mode interactif est un outil de `débug` et permets de tester des choses.
Pour afficher une variable dans un script, il **faut** utiliser `print()`

Sinon rien ne ce passera. 

---

### Petite note sur les opérateurs

- `+` -> Addition
- `-` -> Soustraction
- `/` -> Division
- `*` -> Multiplication
- `%` -> Modulo (Reste d'une division)


---

### Exercices

- Créer une variable qui contiens une `string` et l'ecrire
- Créer une variable qui contiens un `int` et l'ecrire
- Créer une variable qui contiens un `int` et ecrire le resultat de cette variable soustrait à `42`
- Créer une variable qui contiens une `string` et ecrire le resultat de cette variable ajoutée à `"OK"`

---

### Exercices

- Décrivez le plus clairement et le plus complètement possible ce qui se
passe à chacune des trois lignes de l'exemple ci-dessous :
    - `>>> largeur = 20`
    - `>>> hauteur = 5 * 9.3`
    - `>>> largeur * hauteur` -> `930`

- Assignez les valeurs respectives 3, 5, 7 à trois variables a, b, c.
    - Effectuez l'opération a - b/c.
Notes:
Montrer `var +=1` et `var = var - 1`

Expliquer `+= -= /= *=`