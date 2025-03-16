
Ce document décrit l'installation et la configuration d'un système de stockage attaché au réseau (NAS) sous Debian 12, avec divers services comme sftp , webdav et leurs configuration.
pour la completude nous documentons également une installation de webmin, open media vault et Sigma Nas.

Projet

Notre objectif principal est de mettre en place un serveur NAS robuste et
flexible en utilisant le système d'exploitation Debian, privilégiant une approche
sans interface graphique pour optimiser les ressources. Ce serveur offrira une
palette complète de fonctionnalités, notamment le transfert de fichiers via
SFTP, l'accès sécurisé via WebDAV, et la création d'un espace partagé avec un
Dossier Public.
Pour aller plus loin, vous pouvez faire de la virtualisation dans votre serveur,
de la sauvegarde (rsync et création d’un deuxième serveur), et du RAID (raid
5, 6 ou 10).

Au cours du déploiement, des tests approfondis seront effectués pour
s'assurer de la fiabilité de chaque fonctionnalité. Ces tests comprendront la
vérification de la connectivité, la stabilité des transferts de fichiers, la gestion
des sessions et la modification des autorisations.

Enfin, une documentation exhaustive sera élaborée pour guider les
utilisateurs et les administrateurs à travers la configuration et l'utilisation du
serveur NAS Debian. Cette documentation détaillée couvrira chaque aspect
du projet, de l'installation initiale à la gestion quotidienne, fournissant ainsi
une ressource précieuse pour une utilisation continue et évolutive du serveur
NAS.


Pour assurer une expérience utilisateur personnalisée, chaque session
utilisateur sera associée à un dossier dédié sur le serveur NAS. Cela permettra
une organisation efficace des fichiers et la création d’un espace privé.

Un aspect central de ce projet est la mise en place d'une gestion
multisessions, offrant ainsi la possibilité à plusieurs utilisateurs d'accéder
simultanément au serveur NAS. Chaque session sera attribuée de manière

_1

distincte, garantissant ainsi une confidentialité et une sécurité des données
pour chaque utilisateur.
Un point clé de votre démarche sera la création d'une session administrateur,
bénéficiant de privilèges étendus pour superviser l'ensemble du système.
Cette session administrateur sera cruciale pour la maintenance du serveur, la
gestion des sessions utilisateur, et la modification des autorisations d'accès
aux dossiers.



Pour aller plus loin

Pour faciliter l'administration globale du serveur NAS, vous développerez une
interface de gestion intuitive. Cette interface permettra à l'administrateur
d'avoir une vue d'ensemble des sessions utilisateurs, de modifier les
autorisations de manière centralisée, et de garantir un contrôle complet sur
le serveur.

Rendu

Le rendu se ferra sur un document PDF mis sur GitHub et une présentation.
Le projet est à rendre sur votre github à l’adresse suivante :
https://github.com/prenom-nom/nas_debian. Pensez à mettre votre
repository en public !

