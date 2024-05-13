# Ft_Irc
Créez votre propre serveur IRC, en suivant les RFC standards d'Internet. 
Ce projet, nommé ft_irc, est une implémentation d'un client IRC (Internet Relay Chat) et d'un serveur IRC en langage C. Il s'inspire du célèbre client IRC Irssi pour sa conception et ses fonctionnalités.
Objectif du Projet

L'objectif principal de ft_irc est de créer un système de chat en temps réel basé sur le protocole IRC. Le projet comprend deux parties distinctes :

    Client IRC : Un programme permettant à un utilisateur de se connecter à des canaux de discussion, d'envoyer et de recevoir des messages, et d'interagir avec d'autres utilisateurs sur un serveur IRC.

    Serveur IRC : Un serveur capable de gérer les connexions des clients, de distribuer les messages aux canaux appropriés, et de maintenir l'état du chat (utilisateurs connectés, canaux créés, etc.).

Fonctionnalités Principales

    Connexion à un serveur IRC en spécifiant un pseudonyme (nickname) et d'autres informations nécessaires.
    Rejoindre, quitter et créer des canaux de discussion.
    Envoyer des messages publics (sur un canal) ou privés (à un utilisateur spécifique).
    Recevoir et afficher des messages envoyés par d'autres utilisateurs.
    Gérer les différentes commandes IRC telles que JOIN, PART, PRIVMSG, etc.

Modèle de Référence : Irssi

Irssi est un client IRC populaire et hautement configurable, connu pour sa robustesse et ses fonctionnalités avancées. Il offre une interface en ligne de commande conviviale et supporte une variété de plugins et de scripts.

ft_irc s'inspire du modèle de conception d'Irssi en termes d'interface utilisateur, de gestion des canaux et des messages, ainsi que de l'architecture générale d'un client-serveur IRC.
Développement et Utilisation

Le développement du projet ft_irc implique la mise en œuvre des protocoles de communication IRC, la gestion des sockets réseau, la manipulation des messages IRC (encodage/décodage), et la gestion des commandes client/serveur.

Pour utiliser le projet :

    Clonez le dépôt GitHub du projet.
    Compilez le client et le serveur IRC en exécutant les commandes de compilation spécifiées.
    Lancez d'abord le serveur IRC, suivi du client IRC.
    Connectez-vous au serveur en spécifiant les paramètres de connexion (adresse, port, pseudonyme).
    Rejoignez des canaux de discussion, envoyez des messages, et interagissez avec d'autres utilisateurs.

Remarques Finales

ft_irc est un projet stimulant qui met en œuvre des concepts avancés de programmation réseau et de communication client-serveur. Il vise à fournir une expérience de chat IRC robuste et fiable, en s'appuyant sur les principes et les fonctionnalités éprouvés de clients IRC existants tels qu'Irssi.

Pour toute question ou suggestion, n'hésitez pas à contacter les contributeurs du projet.
