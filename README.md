# Dystopia Saint-Étienne · Timetable

Timetable du festival Dystopia (4 et 5 décembre 2026, Saint-Étienne) : les scènes Hard Music et Techno de chaque nuit, les sets en cours, les favoris et les styles de chaque artiste, aux couleurs de l'affiche.

- Page statique, sans build : `index.html` contient le style, les données et le script.
- Installable sur l'écran d'accueil et consultable hors ligne (`manifest.webmanifest`, `sw.js`).
- Fond (`bg.jpg`) généré à partir de la DA de l'affiche : jungle, grille néon, lumière du cube.
- Les tags de style viennent de sources publiques (bios d'artistes, Resident Advisor, Wikipedia, presse hard music) ; un artiste sans source fiable n'a pas de tag.
- « Tester une autre heure », en bas de page, simule une heure de la soirée.

Pour la lancer en local :

```bash
python3 -m http.server 8000
```
