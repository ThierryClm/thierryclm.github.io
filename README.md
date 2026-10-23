# thierryclm.github.io

Ce dépôt ne sert qu'à rediriger les anciennes adresses GitHub Pages vers [tracflux.com](https://tracflux.com/).

Avant le passage au domaine tracflux.com et le renommage du dépôt en TraCflux (24 août 2026), l'application était publiée sur `thierryclm.github.io/Diagramme_Feux/`. GitHub Pages ne redirige pas les anciens chemins d'un dépôt renommé : sans ce dépôt, ces liens répondaient 404, et Google avait retiré l'application de son index.

- `Diagramme_Feux/index.html` : redirection immédiate vers tracflux.com, en conservant les paramètres (`?example=carrefour`…).
- `404.html` : même chose pour les liens profonds.
- `index.html` : la racine renvoie aussi vers tracflux.com.

Ne pas recréer de dépôt nommé `Diagramme_Feux` : cela casserait la redirection automatique de GitHub vers le dépôt [TraCflux](https://github.com/ThierryClm/TraCflux).
