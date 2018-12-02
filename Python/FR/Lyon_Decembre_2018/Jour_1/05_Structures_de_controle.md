## Structures de contrôle

---

### Conditions

```bash
>>> a = 10
>>> if a > 5:
...     a = a + 1
... 
>>> a
11
```

Que se passe-t-il si la valeur était inférieure à 5?

```bash
>>> a = 3
>>> if a > 5:
...     a = a + 1
... 
>>> a
3
```

Note:
 Cette notion est l'une des plus importante en programmation. L'idée est de dire que si telle variable a telle valeur alors faire cela sinon cela.

Prenons un exemple, on va donner une valeur à une variable et si cette valeur est supérieur à 5, alors on va incrémenter la valeur de 1 

On remarque que si la condition n'est pas remplie, les instructions dans la structure conditionnelle sont ignorées.

---

### Condition if else

```bash
>>> a = 20
>>> if a > 5:
...     a = a + 1
... else:
...     a = a - 1
... 
>>> a
21
```

Changeons uniquement la valeur de la variable a :

```bash
>>> a = 3
>>> if a > 5:
...     a = a + 1
... else:
...     a = a - 1
... 
>>> a
2
```

Note:
 Il est possible de donner des instructions quelque soit les choix possibles avec le mot clé else . 

---

## Condition elif

```bash
>>> a = 5
>>> if a > 5:
...     a = a + 1
... elif a == 5:
...     a = a + 1000
... else:
...     a = a - 1
... 
>>> a
1005
```

Note:
Il est possible d'ajouter autant de conditions précises que l'on souhaite en ajoutant le mot clé elif , contraction de "else" et "if", qu'on pourrait traduire par "sinon". 
 
 Dans cet exemple, on a repris le même que les précédent mais nous avons ajouté la conditions "Si la valeur est égale à 5" que se passe-t-il? Et bien on ajoute 1000.

---

### Les boucles

---

### La boucle `while`

Note:
 En anglais " while " signifie "Tant que". Pour créer une boucle , il faut donc utiliser ce mot clé suivi d'une indication qui dit quand la boucle s'arrête.

Un exemple sera plus parlant:

On désire écrire 100 fois cette phrase:

" Je ne dois pas poser une question sans lever la main "

Écrire à la main prend beaucoup de temps et beaucoup de temps x 100 c'est vraiment beaucoup de temps, et peu fiable, même pour les chanceux qui connaissent le copier-coller. Et un bon programmeur est toujours un peu fainéant perfectionniste, il cherchera la manière la plus élégante de ne pas répéter du code. 

---

### Un exemple de la boucle while

```bash
>>> i = 0
>>> while i < 10:
...     print("Je ne dois pas poser une question sans lever la main")
...     i = i +1
...
Je ne dois pas poser une question sans lever la main
Je ne dois pas poser une question sans lever la main
Je ne dois pas poser une question sans lever la main
Je ne dois pas poser une question sans lever la main
Je ne dois pas poser une question sans lever la main
Je ne dois pas poser une question sans lever la main
Je ne dois pas poser une question sans lever la main
Je ne dois pas poser une question sans lever la main
Je ne dois pas poser une question sans lever la main
Je ne dois pas poser une question sans lever la main
```

---

### La boucle `for`

```bash
>>> v = "Bonjour toi"
>>> for lettre in v:
...     print(lettre)
...
B
o
n
j
o
u
r

t
o
i
```
Note:
La boucle for permet de faire des itérations sur un élément, comme une chaine de caractères par exemple ou une liste .

---

### `for` avec `range()`

Il est possible de créer une boucle facilement avec range :

```bash
for i in range(0,100):
  print(i)
```

---

### Stopper une boucle avec break

```bash
>>> liste = [1,5,10,15,20,25]
>>> for i in liste:
...     if i > 15:
...             print("On stoppe la boucle")
...             break
...     print(i)
...
1
5
10
15
On stoppe la boucle
```

---

## Exercices
- hackinscience.org
    - 4, 5, 6 

---

### Exercices

- Écrivez un programme qui affiche les 20 premiers termes de la table de multiplication par 7
- Écrivez un programme qui affiche une table de conversion de sommes d'argent exprimées en euros, en dollars canadiens. La progression des sommes de la table sera « géométrique », comme dans l'exemple ci-dessous :

```
1 euro(s) = 1.65 dollar(s)
2 euro(s) = 3.30 dollar(s)
4 euro(s) = 6.60 dollar(s)
8 euro(s) = 13.20 dollar(s)
```
etc. (S'arrêter à 16384 euros)

---

### Exercices

- Écrivez un programme qui affiche une suite de 12 nombres dont chaque terme soit égal au triple du terme précédent.