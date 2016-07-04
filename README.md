# Checklist de mise en ligne d'un projet

## Serveur / Base de données
- [ ] Importer la base de données
- [ ] Transférer les fichiers sur le serveur

OU


- [ ] Configurer le déploiement via DeployHQ
- [ ] Préciser les fichiers de config (wp-config.php et .htaccess pour Wordpress)


## Site web (général) 

- [ ] Générer les favicons (<a href="realfavicongenerator.net" target="_blank">Real Favicon Generator</a>)
- [ ] Corriger les erreurs de la console
- [ ] Vérifier le responsive du site
- [ ] Ajouter html5.js et Outdated Browser
- [ ] Faire les redirections 301 si c'est une refonte

## Wordpress

### Général 

- [ ] Corriger les permaliens
- [ ] Décocher la non-indexation du site par les moteurs de recherche
- [ ] Designer la page WP-login
- [ ] Créer les notifications de formulaire (admin + client)
- [ ] Créer un compte utilisateur pour le client
- [ ] Masquer la barre d'édition Wordpress
- [ ] Supprimer les rôles inutiles
- [ ] Créer un rôle spécifique au client pour masquer ce qui n'est pas nécessaire sur le back-office

### Thème

- [ ] Modifier le css pour mettre les bonnes infos du theme
- [ ] Rajouter le screenshot.png du thème

### Plugins

- [ ] Utiliser WP Smush pour optimiser la taille de toutes les images
- [ ] Installer WP3 Total Cache pour la mise en cache des pages

## Optimisation du site (ergonomie, chargement...)

- [ ] Passer toutes les images du dossiers /uploads dans ImageOptim
- [ ] Vérifier l'ergonomie et le pagespeed ([Test My Site](https://testmysite.thinkwithgoogle.com))
- [ ] Vérifier que le site utilise bien gzip (<a href="https://varvy.com/tools/gzip/" target="_blank">Gzip Compression Test</a>)

## Analytics
- [ ] Installer Google Analytics
- [ ] Relier Google Analytics à Search Console (webmaster tools)
- [ ] Générer le sitemap du site et le soumettre à Google

### [Spam Referrals](http://help.analyticsedge.com/spam-filter/definitive-guide-to-removing-google-analytics-spam/)
- [ ] Utiliser une propriété -2 pour limiter les spams
- [ ] Ajouter le filtre de l'hostname
- [ ] Ajouter les 4 filtres de Spam Referrals
- [ ] Créer un segment personnalisé
- [ ] Activer l'option de filtrage des bots connus

