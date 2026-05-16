# Repository einrichten

## Schritt 2: Ein `git`-Repository einrichten

> [!note]
>Wir empfehlen dringend, ein Git-Repository für effiziente Versionierung zu nutzen. Du kannst jeden
>Git-Anbieter verwenden — in diesem Tutorial nutzen wir GitHub. GitHub ist nicht nur die
>beliebteste Wahl, sondern bietet zusätzlich Website-Hosting über GitHub Pages und eine
>automatisierte Release-Pipeline.

### 1) Einen GitHub-Account registrieren

Falls du noch keinen GitHub-Account hast, kannst du dich [hier registrieren](https://github.com/join).

### 2) Ein neues Repository erstellen

Lege anschließend ein neues Repository für deine Docusaurus-Website und deinen Obsidian-Vault an.

> [!danger] Öffentliches vs. privates Repository
> Beachte: Mit einem kostenlosen GitHub-Abo kannst du GitHub Pages nur nutzen, wenn dein **Repository öffentlich und damit für jeden im Internet einsehbar ist.** Das heißt, dein **Vault inklusive aller Dateien und Einstellungen — auch Notizen im Draft-Modus — wird vollständig offengelegt.** Wenn dein Repository privat bleiben soll, musst du entweder dein GitHub-Konto upgraden, um GitHub Pages auf einem privaten Repo nutzen zu können, oder eine alternative Deployment-Methode wählen.

### 3) Das Repository auf deinen Rechner klonen

Um das Repository zu klonen, öffne ein Terminal und führe folgenden Befehl aus:
- `git clone https://github.com/{USERNAME}/{REPOSITORY}.git`

### 4) Eine `.gitignore`-Datei im Root anlegen

Obsidiosaurus erstellt im Root deines Repos JSON-Dateien, um die Konvertierung zu tracken.
Das ermöglicht eine smarte Konvertierung — es wird nur konvertiert, was sich tatsächlich geändert hat.

Trage in deine `.gitignore` ein:
```
allSourceAssetsInfo.json
allFilesInfo.json
assetInfo.json
```

### 5) Den Repository-Ordner mit VSCode öffnen

Sobald du das Repository lokal geklont hast, kannst du den Ordner mit Visual Studio Code (VSCode) öffnen.

### 6) Eine neue Terminal-Session in VSCode starten

Falls noch nicht geschehen, starte eine neue Terminal-Session in VSCode.

![|400](assets/vs-code_new_terminal.png)

Deine Terminal-Session sollte nun im Root-Ordner deines Repositories laufen.
