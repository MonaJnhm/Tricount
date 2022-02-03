# Tricount
Pour ce projet, nous avons du réaliser un tricount de manière répartie. C'est à dire que nous pouvons utiliser ce programme de manière connecté entre plusieurs ordinateurs. 
Pour la compilation :
Se placer dans le dossier "services"
Compiler le code des services (Commande : javac *.java)
Copier les exécutables (fichiers .class) de l'interface InterTricount et son implémentation Tricount  ainsi que l'interface BalanceListener et l'exécutable de la classe Participant du dossier "services" au dossier "serveur"
Se placer dans le dossier "serveur"
Compiler le code du serveur (Commande : javac *.java)
Lancer le rmiregistry dans le terminale (Commande : rmiregistry&)
Copier les exécutables (fichiers .class) de l'interface InterTricount, de l'interface Balancelistener ainsi que l'exécutable de la classe Depense et l'exécutable de la classe Participant du dossier "services" au dossier "client"
Se placer dans le dossier "client"
Compiler le code du client (Commande : javac *.java)
Dans un terminal exécuter le serveur (Commande : java Serveur)
Pour chaque client ouvrir un nouveau terminal. Lancer le rmiregistry (Commande : rmiregistry&) et exécuter le client (Commande : java Client Prénom Nom Mdp)
