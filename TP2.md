
1) /usr/bin/
2)HOME
3)LANG=langue utilisée par les logiciels
PWD=repertoire courant
OLDPWD=repertoire courant precedent
SHELL=emplacement du bash
\_=printenv
4)MY_VAR="bonjour"
5)lorsque l'on fait bash la variable local disparait => ouvre un nouvel environnement. si l'on fait exit on retourne dans l ancien et my var reaparait
6)les variables d'environnement sont conservées
7)export NOMS="MORNEAU RIOUAL"
8)echo "Bonjour a vous deux, $NOMS !"
9)unset supprime la référence tandis que affecter une valeur vide ne le fait pas
10)echo '$HOME :' $HOME

1)
cd ~|mkdir script|echo 'PATH=$PATH:~/script'>> ~/.bashrc
exercice 2:
#!bin/bash
PASSWORD="TP"
read -s -p 'veuillez donner le mot de passe' passe
if [ \$pass=$PASSWORD ]; then
    echo 'bien vu'
else
  echo 'dommage'
fi
exercice 3:


exercice 4:
