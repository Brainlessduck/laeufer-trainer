# Läufer-Trainer

Interaktiver Trainer für das 5:1 Läufersystem im Volleyball. Position wählen → Rotation lernen (Läufer 1–6) → im Quiz testen.

Einzelne, abhängigkeitsfreie `index.html` (kein Build-Prozess nötig).

## Deployment auf GitHub Pages (gleicher Account wie brainlessduck)

1. Neues Repository anlegen, z. B. `laeufer-trainer`.
2. `index.html` (und optional dieses `README.md`) ins Repo-Root pushen:
   ```
   git init
   git add index.html README.md
   git commit -m "Läufer-Trainer: initial version"
   git branch -M main
   git remote add origin https://github.com/<dein-account>/laeufer-trainer.git
   git push -u origin main
   ```
3. Im Repo unter **Settings → Pages** als Source `main` / `/ (root)` auswählen.
4. Nach kurzer Zeit ist die Seite erreichbar unter:
   `https://<dein-account>.github.io/laeufer-trainer/`

## Einbindung bei brainlessduck (Volleyball-Kategorie)

Snippet für die Volleyball-Kategorieseite, das kurz erklärt worum es geht und deutlich als externer Link markiert ist:

```html
<div class="external-project-card">
  <p class="tag">Externes Projekt · öffnet in neuem Tab</p>
  <h3>Läufer-Trainer: 5:1 System lernen</h3>
  <p>
    Ein interaktives Lern-Tool, mit dem du für jede Position (Zuspieler, Mittelblocker,
    Außen, Diagonal) Schritt für Schritt die Rotationen des 5:1 Läufersystems lernst
    und dich anschließend im Quiz testen kannst.
  </p>
  <a href="https://<dein-account>.github.io/laeufer-trainer/" target="_blank" rel="noopener">
    Zum Läufer-Trainer →
  </a>
</div>
```

Passe `<dein-account>` an deinen tatsächlichen GitHub-Usernamen an, sobald das Repo online ist.
