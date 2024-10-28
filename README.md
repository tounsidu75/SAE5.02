# SAE5.02

# Configuration d'un Réseau Virtuel avec MARIONET : Double Sous-Réseau et Sécurité avec DHCP et Firewall

## Description du Projet

Ce projet consiste à configurer un réseau virtuel double sous-réseau sur MARIONET, avec un accent sur la sécurité et la gestion des adresses IP. Le réseau comprend des services DHCP et un firewall pour contrôler les communications entre les sous-réseaux et la passerelle. Ce projet vise à démontrer la gestion d'un projet en utilisant des outils de versionnement (GitHub) et de gestion de tâches (Trello) tout en appliquant les concepts de l'agilité.

## Objectifs

- Créer deux sous-réseaux de 6 machines chacun.
- Configurer deux routeurs pour servir d’agents DHCP, attribuant les adresses IP à chaque sous-réseau.
- Paramétrer trois switchs pour séparer les communications entre les sous-réseaux.
- Mettre en place un routeur firewall pour sécuriser l'accès entre les sous-réseaux et la passerelle.

## Architecture Réseau

1. **Sous-réseaux** : Deux sous-réseaux de 6 machines chacun.
2. **Routeurs DHCP** : Attribution d'adresses IP par DHCP sur chaque sous-réseau.
3. **Switchs** : Trois switchs pour la gestion des communications.
4. **Firewall** : Un routeur jouant le rôle de firewall entre le DHCP et la Gateway.

## Outils Utilisés

- **MARIONET** : Plateforme de simulation pour configurer et tester le réseau.
- **GitHub** : Versionnement du code et des configurations `.mar`.
- **Trello** : Suivi des tâches et gestion de projet en méthode agile.
- **SSH** : Authentification pour accès sécurisé aux dépôts GitHub.
