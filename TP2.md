                                # Compte rendu TP2
  # Exercice 1
 
1) Les commandes sont cherchés dans les fichiers contenus dans le **PATH**

2) Le chemin absolu de notre répertoire ourant est stocké dans le **HOME**

3) Quelques variables d'environnement bien utiles :
* **LANG** : langue utilisée par les logiciels
* **PWD** : repertoire courant
* **OLDPWD** : repertoire courant precedent
* **SHELL** : emplacement du bash
* **\_** : printenv

4) Une variable locale est crée ainsi : `MY_VAR="bonjour"`

5) Lorsque l'on tape `bash` dans le shell, la variable local disparait => Cette commande permet d'ouvrir un nouvel environnement bash. si l'on tape `exit` on retourne dans l ancien environnement et **MY_VAR** réaparait.

6) Pour transformer notre variable **MY_VAR** en une variable d'environnement  : `export MY_VAR`. Cette fois ci la commande `bash`conserve dans son environnement la référence de la variable : on peut accéder à sa valeur.

7) Pour créer et afficher une variable d'environnement, le code est le suivant : `export NOMS="MORNEAU RIOUAL|echo $NOMS`"

8) Pour afficher la variable dans une phrase on effectue la commande suivant : `echo "Bonjour a vous deux, $NOMS !"`

9) La commande `unset` supprime la référence tandis que affecter une valeur vide ne le fait pas

10) La commande est la suivante : `echo '$HOME :' $HOME`

## Exercice 2

Avant de taper nos scripts, nous créons un dossier de travail et nous l'ajoutons à la variable **PATH** avec la commande suivante : 
`cd ~|mkdir script|echo 'PATH=$PATH:~/script'>> ~/.bashrc`. Ce qui a pour conséquence d'ajouter le chemin ~/script dans la variable **PATH** à chaque démarrage.

1) 
```
#!bin/bash
PASSWORD="TP"
read -s -p 'veuillez donner le mot de passe' passe
if [ \$pass=$PASSWORD ]; then
    echo 'bien vu'
else
  echo 'dommage'
fi
```

## Exercice 3:
```


```

## Exercice 4:
```



```
## Exercice 5:
```

```

## Exercice 6:
```


```
## Exercice 7:
```

```
