## Les Dictionnaires

---

### Un dict, kesako ?

Note:
Un dictionnaire en python est une sorte de liste mais au lieu d'utiliser des index , on utilise des clés , c'est à dire des valeurs autres que numériques.

---

### Comment créer un dictionnaire?

```bash
>>> a = {}
```

Note:
Pour initialiser un dictionnaire , on utile la syntaxe suivante:

---

### Comment ajouter des valeurs dans un dictionnaire ?

```bash
>>> a = {}
>>> a["nom"] = "engel"
>>> a["prenom"] = "olivier"
>>> a
{'nom': 'engel', 'prenom': 'olivier'}
```

Notes:
Pour ajouter des valeurs à un dictionnaire il faut indiquer une clé ainsi qu'une valeur:

Vous pouvez utiliser des clés numériques comme dans la logique des listes .

---

### Récupérer une valeur dans un dictionnaire

```bash
>>> data = {"name": "Olivier", "age": 30}
>>> data.get("name")
'Olivier'
>>> data.get("adresse", "Adresse inconnue")
'Adresse inconnue'
```

Note:
La méthode get vous permet de récupérer une valeur dans un dictionnaire et si la clé est introuvable, vous pouvez donner une valeur à retourner par défaut:

---

### Vérifier la présence d'une clé dans un dictionnaire

```bash
>>> a.has_key("nom")
True
```

Note:
Vous pouvez utiliser la méthode haskey pour vérifier la présence d'une clé que vous cherchez:

---

### Supprimer une entrée de dictionnaire

```bash
>>> del a["nom"]
>>> a
{'prenom': 'olivier'}
```

Note:
Il est possible de supprimer une entrée en indiquant sa clé, comme pour les listes:

---

### Récupérer les clés par une boucle

```bash
>>> fiche = {"nom":"engel","prenom":"olivier"}
>>> for cle in fiche.keys():
...     print cle
... 
nom
prenom
```

Notes:
Pour récupérer les clés on utilise la méthode keys

---

### Récupérer les valeurs par une boucle

```bash
>>> fiche = {"nom":"engel","prenom":"olivier"}
>>> for valeur in fiche.values():
...     print valeur
... 
engel
olivier
```

Note:
Pour cela on utilise la méthode values


---

### Récupérer les clés et les valeurs par une boucle

```bash
>>> fiche = {"nom":"engel","prenom":"olivier"}
>>> for cle,valeur in fiche.items():
...     print cle, valeur
... 
nom engel
prenom olivier
```

Note:
Pour récupérer les clés et les valeurs en même temps, on utilise la méthode items qui retourne un tuple.
