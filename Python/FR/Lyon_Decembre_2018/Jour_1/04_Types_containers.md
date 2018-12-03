## Les types "containers"

---

### Les listes (`list`)

Variable dans laquelle on peut mettre plusieurs variables ou valeurs

```bash
>>> liste = []
>>> liste
[]
>>> liste = [1, 2, 3]
>>> liste
[1, 2, 3]
```

---

### Ajouter une valeur à une liste

La méthode `append()`

```bash
>>> liste = []
>>> liste
[]
>>> liste.append(1)
>>> liste
[1]
>>> liste.append("OK")
>>> liste
[1, 'ok']
```

---

### Afficher une seule valeur d'une liste

Une liste peut être accédée grâce à son index. Il commence à `0`:
```bash
>>> liste = ["a","d","m"]
>>> liste[0]
'a'
>>> liste[2]
'm'
```

Il est d'ailleurs possible de modifier une valeur avec son index

```bash
>>> liste[2] = "z"
>>> liste
['a', 'd', 'z']
```

---

### Supprimer une entrée de la liste

Il est parfois nécessaire de supprimer une entrée de la liste àa partir de son index. Pour cela vous pouvez utiliser la fonction del .

```bash
>>> liste = ["a", "b", "c"]
>>> del liste[1]
>>> liste
['a', 'c']
```

 Il est possible de supprimer une entrée d'une liste avec sa valeur avec la méthode remove .

```bash
>>> liste = ["a", "b", "c"]
>>> liste.remove("a")
>>> liste
['b', 'c']
```

---

### Inverser les valeurs d'une liste

Vous pouvez inverser les items d'une liste avec la méthode reverse .

```bash
>>> liste = ["a", "b", "c"]
>>> liste.reverse()
>>> liste
['c', 'b', 'a']
```

---

## Compter le nombre d'items d'une liste

Il est possible de compter le nombre d'items d'une liste avec la fonction len .
```
>>> liste = [1,2,3,5,10]
>>> len(liste)
5
```

---

### Compter le nombre d’occurrences d'une valeur

Pour connaître le nombre d’occurrences d'une valeur dans une liste, vous pouvez utiliser la méthode count .

```
>>> liste = ["a","a","a","b","c","c"]
>>> liste.count("a")
3
>>> liste.count("c")
2
```

---

### Trouver l'index d'une valeur

La méthode index vous permet de connaître la position de l'item cherché.

```
>>> liste = ["a","a","a","b","c","c"]
>>> liste.index("b")
3
```

---

### Manipuler une liste

```bash
>>> liste = [1, 10, 100, 250, 500]
>>> liste[0]
1
>>> liste[-1] # Cherche la dernière occurrence
500
>>> liste[-4:] # Affiche les 4 dernières occurrences
[500, 250, 100, 10]
>>> liste[:] # Affiche toutes les occurrences
[1, 10, 100, 250, 500]
>>> liste[:] = [] # vide la liste
[]
```

---

### Transformer une string en liste

Parfois il peut être utile de transformer une chaine de caractère en liste. Cela est possible avec la méthode split .

```bash
>>> ma_chaine = "Olivier:ENGEL:Strasbourg"
>>> ma_chaine.split(":")
['Olivier', 'ENGEL', 'Strasbourg']
```

---

### Trouver un item dans une liste

Pour savoir si un élément est dans une liste, vous pouvez utiliser le mot clé `in` de cette manière:

```bash
>>> liste = [1,2,3,5,10]
>>> 3 in liste
True
>>> 11 in liste
False
```

<sub>Hint: Cela nous servira plus tard pour les conditions</sub>

---

### La fonction range

La fonction range génère une liste composée d'une simple suite arithmétique.

```bash
>>> range(10)
[0, 1, 2, 3, 4, 5, 6, 7, 8, 9]
```

---

### Agrandir une liste par une liste

Pour mettre bout à bout deux listes, vous pouvez utiliser la méthode ex tend

```bash
>>> x = [1, 2, 3, 4]
>>> y = [4, 5, 1, 0]
>>> x.extend(y)
>>> print x
[1, 2, 3, 4, 4, 5, 1, 0]
```

---

### Astuces

Vous pouvez additionner deux listes pour les combiner ensemble en utilisant l'opérateur + :

```bash
>>> x = [1, 2, 3]
>>> y = [4, 5, 6]
>>> x + y
[1, 2, 3, 4, 5, 6]
```

Vous pouvez même multiplier une liste:

```bash
>>> x = [1, 2]
>>> x*5
[1, 2, 1, 2, 1, 2, 1, 2, 1, 2]
```

Ce qui peut être utile pour initialiser une liste:
```bash
>>> [0] * 5
[0, 0, 0, 0, 0]
```

---

### Et les strings dans tout ça ?

Une string est en fait une liste déguisée! La preuve:
```bash
>>> chaine = "Hello"
>>> chaine[0]
'H'
>>> chaine[3]
'l'
>>> chaine[-1:]
'o'
>>>
```

---

### Exercices

- hackinscience.org
    - Exercices 1, 2, 3, 7, 9, 11, 12, 14, 17
