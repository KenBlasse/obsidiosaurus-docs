# Schnellstart ⏱️

Willst du Obsidiosaurus schnell in Aktion sehen? Folge dieser Anleitung — du nutzt dabei das Obsidiosaurus-Docs-Repo selbst als Demo.

### Schritt 1: Wichtige Tools installieren 🛠️

Stelle sicher, dass du Folgendes installiert hast:

- [ ] [Node.js](https://nodejs.org/en/download)
	- Prüfen mit: `node --version`
- [ ] [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
	- Prüfen mit: `git --version`
- [ ] [Obsidian.md](https://obsidian.md/)

### Schritt 2: Das `obsidiosaurus-docs` Repo klonen 📥

Klone das Demo-Repository auf deinen Rechner:

```
git clone https://github.com/KenBlasse/obsidiosaurus-docs.git
cd obsidiosaurus-docs
```

Das ergibt folgende Struktur:

```
obsidiosaurus-docs/
├── vault/        ← Obsidian Vault (die Quelle)
└── website/      ← Docusaurus-Installation (das Ergebnis)
```

### Schritt 3: Docusaurus-Entwicklungsserver starten 🚀

```
cd website
npm install
npm run start
```

Öffne deinen Browser unter `http://localhost:3000/obsidiosaurus-docs/` — du solltest diese Dokumentationsseite lokal sehen. Schließe das Terminal nicht.

### Schritt 4: Obsidiosaurus via BRAT installieren 🔌

Obsidiosaurus ist aktuell über [BRAT](https://github.com/TfTHacker/obsidian42-brat) verfügbar:

1. Öffne Obsidian → Einstellungen → Community Plugins → Durchsuchen
2. Suche nach **BRAT** und installiere es
3. Aktiviere BRAT
4. Öffne die BRAT-Einstellungen → „Add Beta plugin"
5. Gib ein: `KenBlasse/obsidiosaurus`
6. Aktiviere **Obsidiosaurus** in deiner Plugin-Liste

### Schritt 5: Den Vault öffnen 🔓

- Klicke in Obsidian auf `Open folder as vault`
- Wähle den `vault`-Ordner deines geklonten Repos aus: `.../obsidiosaurus-docs/vault`

### Schritt 6: Das Plugin konfigurieren ⚙️

Öffne Obsidian Einstellungen → Obsidiosaurus und setze:

- **Docusaurus Website Directory** — verweise auf deinen `website`-Ordner

### Schritt 7: Obsidiosaurus ausführen 📝

Klicke auf das `page with up arrow`-Icon in der linken Sidebar:

![](assets/obsidiosaurus_sidebar_icon.png)

Nach Abschluss erscheint eine Erfolgsmeldung:

![](assets/obsidiosaurus_run_sucess_notifaction.png)

Deine Änderungen sind nun konvertiert und im Docusaurus-Entwicklungsserver sichtbar.

>[!note]
>Der obsidiosaurus-docs-Vault ist als funktionierendes Beispiel eingerichtet.
>Bearbeite ruhig Notizen und führe die Konvertierung erneut aus, um zu sehen, wie es funktioniert.

Solltest du auf Probleme stoßen, eröffne ein [Issue auf GitHub](https://github.com/KenBlasse/obsidiosaurus/issues).

### (Schritt 8: Optional — Hinterlasse einen ⭐️ auf GitHub)

Wenn dir das Projekt gefällt, hinterlasse gerne einen Stern auf [GitHub](https://github.com/KenBlasse/obsidiosaurus), um die Entwicklung zu unterstützen.
