# Fiche USAR PWA

Application PWA interactive pour la fiche technique de détachement USAR.

## Publication GitHub Pages

Le workflow `.github/workflows/deploy-pages.yml` publie automatiquement l'application sur GitHub Pages à chaque push sur `main`.

Après création du dépôt :
1. pousser le contenu de ce dossier sur la branche `main` ;
2. dans GitHub : **Settings → Pages** ;
3. dans **Build and deployment**, sélectionner **GitHub Actions** ;
4. attendre la fin du workflow.

L'application pourra ensuite être installée depuis un smartphone compatible PWA.


## Envoi par e-mail
- Saisir librement une ou plusieurs adresses e-mail dans la rubrique « Envoi par e-mail ».
- Cliquer sur « Imprimer / enregistrer en PDF » et enregistrer la fiche complétée.
- Revenir à la fiche, cliquer sur « Ouvrir la messagerie », puis joindre manuellement le PDF enregistré.
- Aucun destinataire n’est prédéfini et aucun service d’envoi externe n’est nécessaire.
- L’ouverture de la messagerie est préparée par un lien `mailto:` ; les navigateurs ne permettent pas à ce lien de joindre automatiquement un fichier local.
