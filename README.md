# DVWA Docker Compose Lab

Description

Ce projet met en place **DVWA (Damn Vulnerable Web Application)** à l’aide de **Docker Compose** dans un environnement local. Il est utilisé dans le cadre d’un **TP / Projet Final de Cybersécurité & Réseaux** afin de pratiquer :

* la reconnaissance
* l’exploitation de vulnérabilités web
* les tests d’intrusion (pentest)



---

Prérequis

* Docker
* Docker Compose
* Système d’exploitation : Windows / Linux / macOS

Vérification :

```bash
docker --version
docker-compose --version
```

---

#Installation et lancement

1. Cloner le dépôt :

```bash
git clone https://github.com/USERNAME/dvwa-compose-lab.git
cd dvwa-compose-lab
```

2. Lancer les conteneurs :

```bash
docker-compose up -d
```

3. Accéder à DVWA depuis le navigateur :

```
http://localhost:8080
```

---

Identifiants DVWA

* **Username** : admin
* **Password** : password

Après la première connexion :

* Aller dans **DVWA Security**
* Mettre le niveau de sécurité sur **Low** (pour les tests)

---

Structure du projet

```
dvwa-compose-lab/
│── docker-compose.yml
│── README.md
```

---

 Objectifs pédagogiques

* Comprendre l’architecture d’une application web vulnérable
* Identifier des vulnérabilités (SQLi, XSS, CSRF, etc.)
* Exploiter les failles en environnement contrôlé
* Appliquer les bases du pentesting web

---

 Contexte académique

* **Module** : Cybersécurité & Réseaux
* **Projet** : Audit de Sécurité et Pentest Web (DVWA)
* **Encadrant** : Prof. Azeddine KHIAT

---

Remarque importante

Ce dépôt **ne doit jamais être exposé sur Internet**.
Utilisation strictement locale et académique.

---

Lien GitHub à fournir dans le rapport** :

```
https://github.com/bertamianes-del/dvwa-compose-lab
```

bertamianes-del




