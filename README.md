# Dystopia Saint-Étienne · Timetable

Timetable du festival Dystopia (5 et 6 décembre 2025, Saint-Étienne) : les scènes Techno et Hard Music de chaque nuit, les sets en cours, les favoris et les styles de chaque artiste, aux couleurs de l'affiche.

- Page statique, sans build : `index.html` contient le style, les données et le script.
- Installable sur l'écran d'accueil et consultable hors ligne (`manifest.webmanifest`, `sw.js`).
- Fond (`bg.jpg`) généré à partir de la DA de l'affiche : jungle, grille néon, lumière du cube.
- Les tags de style viennent de sources publiques (bios d'artistes, Resident Advisor, Wikipedia, presse hard music) ; un artiste sans source fiable n'a pas de tag.
- « Tester une autre heure », en bas de page, simule une heure de la soirée.

Pour la lancer en local :

```bash
python3 -m http.server 8000
```
