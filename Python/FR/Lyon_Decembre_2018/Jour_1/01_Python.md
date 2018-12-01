## Vue d'ensemble de Python

---

### L'intepreteur CLI Python - Mode interactif

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
Lancer un terminal, tester de faire des calculs dans l'interpreteur

---

#### Ecrire hello world

```bash
$ python3
Python 3.6.7 (default, Oct 22 2018, 11:32:17) 
[GCC 8.2.0] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> print("Hello world !")
Hello world !
```

---

### L'intepreteur CLI Python - Mode execution de scripts

```bash
$ python3 hello.py                                                                           [11:55:23]
python3: can't open file 'hello.py': [Errno 2] No such file or directory
FAIL
``` 

- Creez un fichier hello.py et ecrivez dedans `print('Hello World!')`
- Sauvegardez ce fichier
- Lancer le fichier avec `python3 hello.py`

---

```bash
 $ python3 hello.py                                                                            [11:58:46]
Hello World!
```

---

### Ce qui c'est passé :

- L'interpreteur Python a ouvert votre fichier `hello.py`
- L'a lu ligne par ligne (Comme dans le mode interactif)

---

### Exercises :

- Faire un fichier `ex0.py` qui écrit `Bonjour`
- Faire un fichier `ex1.py` qui écrit `42`
    - Deux facons de faire
