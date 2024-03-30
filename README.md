# DiscordMassDM - Envoi de messages automatisés

Ce script permet d'envoyer des messages automatisés à tous vos amis Discord, en prenant en compte les limitations de l'API et en évitant les blocages. Il offre également la possibilité d'ignorer certains utilisateurs et de personnaliser le message à envoyer.

## Fonctionnalités

- Connexion à un compte Discord
- Vérification de l'état du compte (e-mail et numéro de téléphone vérifiés)
- Liste des amis et filtrage des bots et des utilisateurs ignorés
- Calcul du temps estimé pour envoyer tous les messages
- Envoi de messages avec un délai aléatoire pour éviter les blocages
- Gestion des échecs d'envoi et des limitations de l'API
- Affichage de l'avancement et du temps restant estimé
- Menu principal pour gérer les options du script

## Utilisation

1. Installez les dépendances : `npm install discord.js-selfbot-v13 chalk readline-sync clear`
2. Remplacez `'VOTRE_TOKEN_ICI'` par le token de votre compte Discord.
3. Exécutez le script : `node index.js`
4. Suivez les instructions du menu principal pour envoyer des messages, gérer la liste des ignorés et modifier le message à envoyer.

5. Si vous rencontrez des problèmes d'affichage de caractères spéciaux dans la console, essayez de changer l'encodage de la console en UTF-8.
	* Dans Windows :
		1. Ouvrez l'invite de commandes.
		2. Tapez `chcp 65001` et appuyez sur Entrée.
		3. Exécutez votre script.
	* Dans Linux :
		1. Ouvrez le terminal.
		2. Tapez `export LC_ALL=en_US.UTF-8` et appuyez sur Entrée.
		3. Exécutez votre script.
## Remarques

- Ce script est destiné à un usage personnel et éducatif. L'utilisation abusive de cette application peut entraîner la suspension de votre compte Discord.
- L'utilisation de ce script est à vos risques et périls. Les auteurs ne sauraient être tenus responsables des conséquences liées à son utilisation.

## Licence

Ce projet est sous licence MIT. Consultez le fichier [LICENSE](LICENSE) pour plus de détails.
