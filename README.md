# Site RH Pro Chantier

Site web responsive pour une société de chantier et de maintenance industrielle.

## Ouvrir le site

Ouvrir directement le fichier :

```text
index.html
```

## Fonctions visibles

- Tableau de bord RH avec statistiques.
- Graphiques pour chantiers et évaluations.
- Gestion des salariés avec recherche instantanée.
- Bouton d'ajout salarié avec formulaire.
- Export CSV compatible Excel.
- Modules absences, pointage, documents, discipline, évaluations, formations, EPI, rapports et traçabilité.
- Connexion administrateur avant l'accès au site.

## Comptes administrateur

- `yassine khamer` / `yassine666kh`
- `mehdi karim` / `mehdi777kh`
- `abdllilah el arjioui` / `abdo888kh`

## Modifier les comptes

Les comptes se trouvent dans `script.js`, au début du fichier, dans le tableau `admins`.
Pour ajouter ou changer un compte, modifiez une ligne comme ceci :

```js
{ username: 'nom utilisateur', password: 'motdepasse', role: 'Administrateur' }
```

Cette version est une interface web statique prête à présenter. Pour connecter les données réelles, il faut la relier ensuite à une base MySQL avec PHP/Laravel, Django ou Node.js.

Important : comme le site est statique, les identifiants sont visibles dans `script.js`. Pour une vraie mise en production, l'authentification doit être faite côté serveur avec mots de passe hachés.
