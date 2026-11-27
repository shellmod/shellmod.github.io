# Mon blog

Hugo (extended ≥ 0.141) + thème [Blowfish](https://blowfish.page) en sous-module git, déployé sur GitHub Pages.

## Commandes

```bash
git clone --recurse-submodules <repo>     # ou : git submodule update --init
hugo server -D                            # aperçu local sur http://localhost:1313
hugo new content posts/mon-article/index.md   # nouvel article (draft: true)
```

Images d'un article : les déposer dans le dossier de l'article. Une image nommée
`featured.png` (ou .jpg) sert automatiquement de vignette / bannière.

## Configuration

- `config/_default/languages.fr.toml` : nom, bio, avatar, liens sociaux
- `config/_default/params.toml` : apparence (couleurs, page d'accueil, articles)
- `config/_default/menus.fr.toml` : menu
- `assets/img/profile.jpg` : photo de profil
- `static/img/background.svg` : fond d'écran

## Déploiement (GitHub Pages)

1. Créer un repo `shellmod.github.io` et pousser sur `main`.
2. Settings → Pages → Source : **GitHub Actions**.
3. Le workflow `.github/workflows/hugo.yml` construit et publie à chaque push.
