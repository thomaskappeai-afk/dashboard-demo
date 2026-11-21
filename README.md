# DT Admin dashboard demo

Publieke demosite met uitsluitend fictieve gegevens.
Live: https://thomaskappeai-afk.github.io/dashboard-demo/

GitHub Pages deployt vanaf de branch `main` (root van de repo).

## Mappen

| Pad | Inhoud |
| --- | --- |
| `/` | Originele single-file dashboard van Thomas (`index.html`). Deze file niet wijzigen. |
| `/preview/` | Gebouwde DT Admin dashboard v14 (Vite + React). |
| `/preview-v2/` | Gebouwde DT Admin dashboard v15 (Vite + React). |
| `/preview-robin/` | Extra v14-build in huisstijlkleuren; redundant ten opzichte van `/preview/`. |

## Werkwijze

Afgerond werk wordt altijd in `main` gemerged. Feature-branches en preview-mappen zijn tussentijdse publicaties; als een versie live of klaar is, hoort die op `main` te staan, zodat de publieke site en de default branch hetzelfde zijn.
