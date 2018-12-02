## Vue d'ensemble de Python

---

### Qu'est ce que Python?

Python est un langage de programmation, dont la première version est sortie en 1991.

Créé par Guido van Rossum, il a voyagé du Macintosh de son créateur, qui travaillait à cette époque au Centrum voor Wiskunde en Informatica aux Pays-Bas, jusqu'à se voir associer une organisation à but non lucratif particulièrement dévouée, la Python Software Foundation, créée en 2001.

Ce langage a été baptisé ainsi en hommage à la troupe de comiques les « Monty Python ».

---

### Interpréteur CLI Python - Mode interactif

```bash
$ python3
Python 3.6.7 (default, Oct 22 2018, 11:32:17) 
[GCC 8.2.0] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>>
```

---

```bash
$ python3
Python 3.6.7 (default, Oct 22 2018, 11:32:17) 
[GCC 8.2.0] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> 1 + 1
2
```

Notes:
Lancer un terminal, tester de faire des calculs dans l’interpréteur

---

#### Écrire hello world

```bash
$ python3
Python 3.6.7 (default, Oct 22 2018, 11:32:17) 
[GCC 8.2.0] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> print("Hello world !")
Hello world !
```

---

### Interpréteur CLI Python - Mode exécution de scripts

```bash
$ python3 hello.py                                                                           [11:55:23]
python3: can't open file 'hello.py': [Errno 2] No such file or directory
FAIL
``` 

- Créez un fichier hello.py et écrivez dedans `print('Hello World!')`
- Sauvegardez ce fichier
- Lancer le fichier avec `python3 hello.py`

---

```bash
 $ python3 hello.py                                                                            [11:58:46]
Hello World!
```

---

### Ce qui s'est passé :

- L’interpréteur Python a ouvert votre fichier `hello.py`
- L'a lu ligne par ligne (Comme dans le mode interactif)

L’interpréteur interactif est comme si on lançait un fichier mais en ligne par ligne manuellement

---

### Exercices :

- Faire un fichier `ex0.py` qui écrit `Bonjour`
- Faire un fichier `ex1.py` qui écrit `42`
    - Deux façons de faire

Notes:

Montrer la résolution en live coding