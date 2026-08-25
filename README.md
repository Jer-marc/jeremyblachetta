# Portfolio — Jere

Minimalistische Portfolio-Website, gebaut mit reinem HTML/CSS/JS (kein Framework, kein Build-Schritt).

## Struktur

- `index.html` — Inhalt der Seite
- `style.css` — Design/Layout
- `script.js` — Scroll-Animation der Projektkarten

## Inhalte anpassen

1. In `index.html` die Platzhalter ersetzen:
   - `Projektname 1/2/3`, Tags und Beschreibungstexte
   - `href="#"` bei "Case Study lesen" durch echte Links/Unterseiten ersetzen
   - `mailto:hallo@example.com`, LinkedIn- und GitHub-Links im Kontaktbereich eintragen
2. Statt der Platzhalter-Boxen (`.project-media`) eigene Bilder einbinden, z. B.:
   ```html
   <div class="project-media">
     <img src="images/projekt1.jpg" alt="Screenshot Projekt 1">
   </div>
   ```
   und in `style.css` bei `.project-media img { width:100%; height:100%; object-fit:cover; }` ergänzen.

## Mit GitHub Pages veröffentlichen (kostenlos)

1. Neues Repository auf GitHub anlegen, z. B. `dein-username.github.io` (dann ist die Seite direkt unter dieser Adresse erreichbar) oder einen beliebigen Namen wie `portfolio`.
2. Diese drei Dateien (`index.html`, `style.css`, `script.js`) in das Repository hochladen (per Drag & Drop im Browser oder per `git push`).
3. Im Repository zu **Settings → Pages** gehen.
4. Unter "Build and deployment" als Quelle **Deploy from a branch** wählen, Branch `main` und Ordner `/ (root)` einstellen, speichern.
5. Nach ein bis zwei Minuten ist die Seite live unter `https://dein-username.github.io/repository-name/` (bzw. direkt unter `https://dein-username.github.io/`, falls du den Repo-Namen aus Schritt 1 gewählt hast).
