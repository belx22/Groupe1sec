# Groupe1sec
Project de securites des systemes et des reseaux

# Description
On veut mener une étude sur la sécurité des applications de paiement mobile sous Android les plus utilisé au Cameroun.On va investiguer sur les vulnérabilités les plus populaires dans ces applications de paiement en procédant par une analyse statique et dynamique des ses applications et recenser les arnaques utilisé par les hacker au Cameroun.

# Installation

## Prérequis
-Installer apktool qui est utilisé pour decompiler les applications etudier par nos outils de detection
```bash
sudo apt install apktool
```
-Installer l'outil de detection QARK qui permet d'effectuer une analyse static des applications android 

```bash
sudo apt install python-pip python3-pip
sudo pip install --upgrade setuptools
git clone https://github.com/linkedin/qark
sudo cd qark
sudo pip install -r requirements.txt
sudo pip install . --user  # --user is only needed if not using a virtualenv
sudo qark --help
```
-Installer l'outil de detection mobile security framework-mobfs 
* Linux
```bash
Pour plus de detail https://mobsf.github.io/docs/#/

git clone https://github.com/MobSF/Mobile-Security-Framework-MobSF.git
cd Mobile-Security-Framework-MobSF
pip3 install virtualenv
virtualenv -p python3 venv
source venv/bin/activate
pip3 install -r requirements.txt
python3 manage.py runserver IP:PORT_NO
```
* Windows 
```bash
 - Install Git
 - Install Anaconda Python 3.7 (3.8 is not supported)
 - Install JDK 8+
 - Install Microsoft Visual C++ Build Tools
 - Install OpenSSL
 - Download & Install wkhtmltopdf as per the wiki instructions and add the folder that contains wkhtmltopdf binary to environment variable PATH.
- git clone https://github.com/MobSF/Mobile-Security-Framework-MobSF.git
- cd Mobile-Security-Framework-MobSF
- setup.bat
```
