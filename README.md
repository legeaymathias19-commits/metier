# GoRP — Répertoire de serveurs RP

## Tester le site
Ouvre `index.html` dans un navigateur. Le site est responsive et fonctionne sans installation.

## Publication gratuite avec GitHub Pages
1. Crée un compte sur https://github.com/
2. Clique sur **New repository** et donne-lui un nom, par exemple `gorp`.
3. Choisis **Public**, puis crée le dépôt.
4. Dans le dépôt, clique sur **Add file > Upload files**.
5. Dépose `index.html` à la racine du dépôt, puis clique sur **Commit changes**.
6. Ouvre **Settings > Pages**.
7. Dans **Build and deployment**, choisis **Deploy from a branch**, sélectionne `main` et `/ (root)`, puis **Save**.
8. Attends quelques minutes et ouvre l’adresse affichée dans la section Pages (souvent `https://TON-PSEUDO.github.io/gorp/`).

La documentation officielle : https://docs.github.com/en/pages/quickstart

## À personnaliser avant publication
- Dans `index.html`, remplace les serveurs d’exemple dans le tableau `servers`.
- Les notes sont fictives et les compteurs de joueurs affichent `—` : aucune donnée en direct n'est connectée.
- Remplace `contact@example.com` par une adresse de contact que tu contrôles.
- Pour les vrais avis, comptes et joueurs en ligne, il faudra ajouter une source de données/API et éventuellement un backend. GitHub Pages héberge des fichiers statiques et ne fournit pas à lui seul de base de données.
- Le dépôt et le site seront publics : ne publie pas d’informations privées ni de clés secrètes.
