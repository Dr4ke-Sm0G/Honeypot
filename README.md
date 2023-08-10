# HoneyPot Projet

Ce projet vise à créer un HoneyPot simple en Python qui simule un service réseau et enregistre les tentatives de connexion à ce service. Un HoneyPot est un système de sécurité qui attire les attaquants potentiels, les désoriente et collecte des informations sur leurs méthodes et intentions. Dans ce cas, le HoneyPot simule un service en écoutant les connexions entrantes et en enregistrant les informations sur les tentatives de connexion.

## Fonctionnement

Le script `honeypot.py` crée un socket pour écouter les connexions entrantes sur le port 2222. Lorsqu'une connexion est établie, le script envoie un message de bienvenue au client, enregistre l'adresse IP et le port du client, puis affiche les données reçues du client. Après quoi, le script attend une entrée utilisateur pour continuer à écouter les connexions.

## Prérequis

- Python 3.x

## Utilisation

1. Clonez ce référentiel vers votre machine locale.
2. Naviguez vers le répertoire du projet.
3. lancer `pyhton3 honeypot.py`
