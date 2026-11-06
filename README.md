# Polonais pas à pas

Site d’apprentissage du polonais (A1, début A2). Un seul fichier `index.html`, sans installation ni build.

## Déployer en 2 étapes

### 1. Mettre le code sur GitHub
1. Va sur github.com, clique sur **New repository**, nomme-le `polonais-pas-a-pas`, laisse-le en **Public**, puis **Create repository**.
2. Clique sur **uploading an existing file**, glisse les 3 fichiers (`index.html`, `render.yaml`, `README.md`), puis **Commit changes**.

### 2. Créer le lien avec Render
1. Va sur render.com et connecte-toi avec ton compte GitHub.
2. Clique sur **New +** puis **Static Site**.
3. Choisis ton dépôt `polonais-pas-a-pas`.
4. Réglages :
   - **Build Command** : laisse vide
   - **Publish Directory** : `.`
5. Clique sur **Create Static Site**. Au bout d’une minute, Render te donne un lien du type `https://polonais-pas-a-pas.onrender.com`.

Pour modifier le site plus tard, change `index.html` sur GitHub : Render redéploie automatiquement.

## À savoir
- Le site marche en **HTTPS** (fourni par Render), ce qui est nécessaire pour l’enregistrement de la voix.
- La voix polonaise vient de l’appareil. Sur iPhone : Réglages › Accessibilité › Contenu énoncé › Voix › Polonais. Sur Android : Réglages › Synthèse vocale.
- La progression est enregistrée dans le navigateur de chaque personne (pas de compte, pas de base de données).
- Les polices viennent de Google Fonts. Sans connexion, le site utilise des polices de secours.
