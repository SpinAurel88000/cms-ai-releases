CMS AI Releases
Dépôt public de distribution des mises à jour officielles du CMS.
Le code source du CMS reste privé dans le dépôt SpinAurel88000/cms-ai.
Contenu de ce dépôt
Ce dépôt ne doit contenir aucun code source PHP du CMS en clair et aucun secret.
Les mises à jour officielles seront publiées dans GitHub Releases avec, selon le protocole retenu :
- un descripteur de version et de compatibilité ;
- une signature cryptographique Ed25519 ;
- un paquet de mise à jour machine chiffré ;
- les notes de version publiques.
Le CMS peut consulter ce dépôt public sans authentification afin de détecter les nouvelles versions disponibles.
Sécurité
Ne jamais publier ici :
- le dépôt source du CMS ;
- des fichiers .env ;
- des jetons GitHub ;
- des clés privées de signature ou de chiffrement ;
- des sauvegardes de base de données ;
- des données de production ;
- un paquet contenant le code PHP du CMS en clair.
Les métadonnées et paquets publiés doivent être générés par le processus de release du dépôt privé, puis vérifiés et signés avant publication.
Installation
Une publication dans ce dépôt ne déclenche jamais automatiquement une installation sur un site.
Le CMS peut détecter une mise à jour disponible, puis un administrateur doit explicitement lancer son installation depuis l'administration du CMS.
Le mécanisme manuel de secours reste géré depuis le dépôt privé.
