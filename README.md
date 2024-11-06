# SAE5.02

## Configuration d'un Réseau Virtuel avec MARIONET : Double Sous-Réseau et Sécurité avec DHCP et Firewall

### Description du Projet

Ce projet consiste à configurer un réseau virtuel composé de deux sous-réseaux sur MARIONET, avec un accent sur la sécurité et la gestion des adresses IP. Le réseau inclut un serveur DHCP central pour la distribution des adresses IP et un firewall pour contrôler les communications entre les sous-réseaux et la passerelle. Ce projet met également en avant la gestion de projet en utilisant des outils de versionnement (GitHub) et de gestion de tâches (Trello), tout en appliquant les concepts de l'agilité.

### Objectifs

- Créer deux sous-réseaux avec 3 machines chacun.
- Configurer un serveur DHCP central pour attribuer les adresses IP aux deux sous-réseaux.
- Configurer deux switches pour séparer les communications entre les sous-réseaux.
- Mettre en place un firewall pour sécuriser l'accès entre les sous-réseaux et la passerelle.

### Architecture Réseau

1. **Sous-réseaux** : Deux sous-réseaux de 3 machines chacun.
2. **Serveur DHCP** : Serveur central pour attribuer les adresses IP aux deux sous-réseaux.
3. **Switches** : Deux switches, un pour chaque sous-réseau.
4. **Firewall** : Gère la sécurité et le routage entre les sous-réseaux et la passerelle.
5. **Gateway** : Point d'accès pour la connexion au réseau externe.

### Configuration des Sous-Réseaux

#### Sous-réseau 1
- **Adresse réseau** : `192.168.10.0/24`
- **Plage d'adresses IP** : `192.168.10.10` à `192.168.10.50`
- **Passerelle** : `192.168.10.1` 
- **Masque** : `255.255.255.0`

#### Sous-réseau 2
- **Adresse réseau** : `192.168.20.0/24`
- **Plage d'adresses IP** : `192.168.20.10` à `192.168.20.50`
- **Passerelle** : `192.168.20.1` 
- **Masque** : `255.255.255.0`

### Outils Utilisés

- **MARIONET** : Plateforme de simulation pour configurer et tester le réseau.
- **GitHub** : Versionnement du code et des configurations `.mar`.
- **Trello** : Suivi des tâches et gestion de projet en méthode agile.
- **SSH** : Authentification pour accès sécurisé aux dépôts GitHub.

### Configuration et Déploiement

1. **Installation et configuration du serveur DHCP** pour attribuer des adresses IP aux deux sous-réseaux.
2. **Mise en place des règles de firewall** pour permettre ou restreindre la communication entre les sous-réseaux et la passerelle.
3. **Tests de connectivité** pour vérifier l'attribution des adresses IP et le bon fonctionnement des règles de sécurité.