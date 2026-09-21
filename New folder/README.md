# Buget zilnic — pachet pentru publicare

Conținut: index.html (aplicația), manifest.webmanifest + sw.js (o fac instalabilă și funcțională fără internet), iconițe PNG.

## Varianta 1 — Netlify Drop (cea mai simplă)
1. Dezarhivează acest pachet.
2. Deschide https://app.netlify.com/drop și trage folderul dezarhivat peste pagină.
3. Creează un cont gratuit când ți se cere, ca site-ul să rămână online permanent.
4. Primești un link de forma https://nume-random.netlify.app (îl poți redenumi din Site settings).

## Varianta 2 — GitHub Pages
1. Creează un cont gratuit pe github.com și un repository nou (public), de ex. "buget".
2. Apasă "uploading an existing file" și trage toate fișierele (nu folderul), apoi "Commit changes".
3. Settings → Pages → la "Build and deployment": Source = Deploy from a branch, Branch = main, folder = / (root) → Save.
4. După 1-2 minute, aplicația e la https://UTILIZATOR.github.io/buget/

## Pe telefon
- iPhone (Safari): deschide link-ul → Partajare → Adaugă pe ecranul principal.
- Android (Chrome): deschide link-ul → meniul ⋮ → Instalează aplicația / Adaugă pe ecranul de pornire.
Deschide apoi mereu aplicația de pe iconiță. Datele se salvează în acel browser/aplicație.

## Dacă modifici index.html mai târziu
În sw.js schimbă `buget-zilnic-v1` în `buget-zilnic-v2` ca telefonul să ia versiunea nouă.
