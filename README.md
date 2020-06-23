**French Version follows**

# Environment Manifest file for C-19 Benefit Finder

This repository is used to deploy to our staging environment and acts as a way to see what version is currently running in production. It is also used as an audit log to track releases of the application.

## How to deploy to staging.

1. Create a new branch
1. Update the manifest.json with the version yo wish to deploy
1. Create a Pull Request, the description should outline the new features you wish to release
1. Get approval from the individual with the delegated authority to release to production.

Upon Merging to the mainline code branch the version of the application will be deployed to the staging environment where you can perform a final smoke test before releasing to production.

---------------------------------------------------------------------------------

# Fichier Manifeste d'environnement pour l'outil de recherche de prestations C-19

Ce repertoire est utilisé pour déployer dans notre environnement de test et permet de voir quelle version est actuellement operationelle en production. Cet environnement est aussi utilisé comme un journal d'audit pour suivre les differentes versions livrées de l'application. 

## Comment deployer dans l'environnement test.

1. Creer une nouvelle branche
2. Mettre à jour manifest.json avec la version que vous souhiatez deployer
3. Créer une Pull Request, la description devrait souligner les nouvelles fonctionnalités que vous souhaitez publier
4. Obtenir l'approbation d'un inidividu qui dispose de l'authorité deleguée pour publier en production. 

Au moment de fusionner la branche principale du code, la version de l'application sera deployée dans l'environnement de test où vous pourrez effectuer un test de fumee avant de publier en production. 
