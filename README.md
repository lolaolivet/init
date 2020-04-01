# init

## Objectifs
Ce premier projet, init vous permettera de découvrir les commandes de base système
et réseau ainsi que les nombreux services utilisés sur une machine serveur, ainsi que
quelques idées de scripts pouvant être utiles au quotidien d’un adminsys.

## Consignes générales
Toutes les questions sont à résoudre uniquement avec des commandes du terminal.
Il existe trois types de questions dans ce projet. Un code de couleurs permet d’identifier le type de la réponse attendue :
En bleu : une commande
En vert : une sortie de commande
En rouge : une déduction écrite avec vos propres mots
• Vous devez créer un dossier pour chaque partie de ce sujet à la racine de votre
dépot. Ces dossiers doivent s’appeler network, system et scripts. Vous devez
écrire la ou les réponses d’une question dans un fichier nommé comme le numéro
de la question, sur deux digits. Par exemple : la réponse à la question 01 de la
partie network doit se trouver dans le fichier network/01.
• Les scripts doivent être rendus exécutables.

## Partie obligatoire
### Soyons copains
Suivre Slash16 sur Facebook, Twitter et Linkedin.
### Network
1. Récupérez la liste des interfaces réseau de la machine sans afficher aucun détail
pour ces interfaces. Vraiment juste la liste des noms.
2. Identifiez et affichez les caractéristiques de l’interface Ethernet :
(a) Indiquez l’adresse de Broadcast
(b) Indiquez toutes les adresses IP qui font partie du même sous-réseau
3. Identifiez l’adresse MAC de la carte Wi-Fi
4. Identifiez la gateway par défaut dans la table de routage
5. Identifiez l’IP du serveur DNS qui répond sur le domaine suivant : slash16.org
6. Récupérez le path complet du fichier dans lequel est écrit l’adresse IP du serveur
DNS que vous utilisez
7. Interrogez un serveur DNS externe sur le nom de domaine slash16.org (ex :
google 8.8.8.8)
8. Trouver chez quel hébergeur est le site de Slash16
9. Trouver l’IP Publique de 42.fr
10. Identifiez les différents appareils réseaux entre votre poste et le domaine slash16.org 
11. Trouvez grâce au résultat de la commande précédente le nom et l’IP du matériel qui fait le lien entre vous (réseau local) et l’extérieur
12. Trouvez l’IP qui vous a été assignée par le serveur dhcp
13. Grâce a la question précédente et au reverse DNS retrouvez le nom de votre host
14. Quel est le fichier contenant les entrées locales DNS ?
15. Faites pointer intra.42.fr sur l’adresse suivante 46.19.122.85

### System
1. Dans quel fichier se trouve la version installée de votre Debian ?
2. Quelle commande permet de renommer votre système ?
3. Quel est le fichier à modifier pour rendre cela permanent ?
4. Quelle commande donne le temps depuis lequel votre système à été démarré la dernière fois ?
5. Donnez une commande qui détermine l’état du service SSH
6. Donnez une commande pour redémarrer le service SSH
7. Déterminez le PID du service SSHD
8. Quel fichier contient les clés RSA des machines autorisées à se connecter via SSH ?
9. Quelle commande permet de savoir quelles personnes sont connectées sur le système ?
10. Quelle commande permet de lister les tables de partitions des disques ?
11. Quelle commande permet d’afficher l’espace disponible et utilisé sur le système
d’une manière humainement compréhensible ? ?
12. Déterminez la taille exacte de chaque dossier de /var d’une manière humainement
compréhensible suivi du chemin de celui-ci.
13. Trouvez une commande qui permet, en temps réel, de trouver les processus en
cours d’exécution
14. Lancez en background la commande tail -f /var/log/syslog
15. Trouvez une commande qui permet de tuer le processus de la commande en background
16. Trouvez un service qui permet de lancer des tâches à horaires régulières
17. Trouvez une commande qui, en parallèle de la session graphique, permet de se
connecter en ssh sur la machine
18. Donnez une commande qui permet d’arrêter le service ssh
19. Listez les services qui se lancent automatiquement lorsque la machine boot et
indiquez le nom donné à ce type de service
20. Listez tout les utilisateurs existants sur la machine
21. Listez tout les utilisateurs réels de la machine
22. Quelle commande permet d’ajouter un utilisateur local supplémentaire ?
23. Expliquez comment se connecter en tant que ce nouvelle utilisateur. (En session
graphique et en session ssh)
24. Quelle commande permet de lister tout les packages INSTALLÉS sur la machine ?

### Scripting
1. Réalisez un script qui affiche seulement le login, le UID et le Path de chaques entrée du fichier /etc/passwd
2. Réalisez un script qui permet de supprimer un user LOGUÉ sur la machine
3. Jamais 2 sans 3. Réalise un script de ton choix. La qualité de ton script, devant ton évaluateur tu soutiendras.

## Note
100/100
