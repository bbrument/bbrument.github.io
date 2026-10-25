# bbrument.github.io : site perso (template Jon Barron) + CV, servi par GitHub Pages

## Contraintes
- Push sur main autorisé (le push met le site en ligne). Toujours `git pull` avant de modifier : un clone peut être en retard.
- `cv/` est dans .gitignore mais `cv/main_english.tex` et `cv/main_francais.tex` sont suivis : `git add -f`, jamais `git add -A`.
- Toute modif de publication se reporte dans les deux CV (EN et FR).

## Commandes
- CV : dans `cv/`, `pdflatex main_english.tex` (×2), puis copier vers `images/cv_english.pdf` (idem `francais`).
  L'erreur xcolor `lastnamecolor` est connue et sans effet.

## Conventions
- Publication : vignette `images/<venue><année><mot>.(png|jpg)`, BibTeX `data/<auteur><année><mot>.bib`.
- Sources des papiers : `~/dev/overleaf_projects/<projet>` (git pull avant de lire).
- News : environ 6 dans `news-recent`, les plus anciennes passent dans `news-older`. Mettre à jour « Last updated » en bas de page.

## Passation
- État et prochaines étapes : `docs/STATUS.md`.
