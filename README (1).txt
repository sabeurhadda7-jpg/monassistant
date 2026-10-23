Mon Assistant — première version
=================================
Fichiers:
- index.html : application
- manifest.json : métadonnées d'installation PWA
- sw.js : cache hors ligne de base

Fonctions:
- Interface arabe/français (bouton en haut)
- Enregistrer interventions de maintenance
- Enregistrer revenus, dépenses et remboursements
- Notes de projets
- Ouvrir ChatGPT (sans synchronisation automatique)
- Exporter/importer une sauvegarde JSON

Données:
Stockées localement dans le navigateur de l'appareil. Exportez régulièrement une sauvegarde.
Cette version n'est pas un APK Android natif. Pour l'installer comme application via Chrome,
il faut héberger ces fichiers sur un site HTTPS qui permet les PWA, puis choisir
Chrome > menu ⋮ > Installer l'application / Ajouter à l'écran d'accueil.
Pour générer un APK natif, une étape de build Android supplémentaire est nécessaire.
