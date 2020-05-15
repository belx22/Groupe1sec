# Groupe1sec
Project de securites des systemes et des reseaux

# Description
On veut mener une étude sur la sécurité des applications de paiement mobile sous Android les plus utilisé au Cameroun.On va investiguer sur les vulnérabilités les plus populaires dans ces applications de paiement en procedant par une analyse statique et dynamique des ses applications et recenser les arnaques utilisé par les hacker au Cameroun.

# Installation

## Prérequis
-Installer apktool qui est utilisé pour decompiler les applications etudier par nos outils de detection
```bash
sudo apt install apktool
```
-Installer l'outil de detection QARK qui permet d'effectuer une analyse static des applications android 
``bash
sudo apt install python-pip python3-pip
sudo pip install --upgrade setuptools
git clone https://github.com/linkedin/qark
sudo cd qark
sudo pip install -r requirements.txt
sudo pip install . --user  # --user is only needed if not using a virtualenv
sudo qark --help
```
