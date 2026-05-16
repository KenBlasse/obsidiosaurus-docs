# Vault-Einrichtung

## Schritt 4: Den Vault konfigurieren

### 1) Einen Ordner anlegen

Erstelle einen neuen Ordner namens `vault` im Root deines Repositories.

Deine Verzeichnisstruktur sollte nun so aussehen:
```js
{REPOSITORY}/
├── vault/
│   └── (hier liegt der Obsidian Vault)
└── website/
    └── (hier liegt die Docusaurus-Installation)
```

### 2) Den Vault öffnen

Starte deine Obsidian-Anwendung. Öffne den `vault`-Ordner in deinem Repository.
Du solltest nun einen leeren Obsidian-Vault namens „vault" sehen.

### 3) Einen Anhänge-Ordner anlegen

Lege einen Ordner für deine Anhänge an.

![|500](assets/obsidian_create_attachment_folder.png)

>[!caution] Anhänge-Ordner
>Alle Bilder und Dokumente müssen in diesem speziellen Ordner liegen. Wenn du einen anderen Namen für den Ordner wählst, vergiss nicht, ihn auch in den Obsidiosaurus-Plugin-Einstellungen zu aktualisieren.

### 4) Files & Links-Einstellungen anpassen

>[!caution]
>Mehrere Einstellungen für deinen Vault und deine Plugins müssen angepasst werden, damit Obsidiosaurus zuverlässig funktioniert.
>Halte dich genau an die Anleitung, um Fehlverhalten zu vermeiden.

Gehe zu den Obsidian-Einstellungen ⚙️ unten links und passe deine Files & Links-Einstellungen wie gezeigt an:

![](assets/obisidan_settings_files_and_links.png)

### 5) Plugin-Installation

- Aktiviere Community Plugins.

#### Obsidiosaurus (erforderlich)

**Installation via BRAT** (bis das Plugin im Community Plugin Store verfügbar ist):

1. Installiere [BRAT](https://github.com/TfTHacker/obsidian42-brat) aus dem Community Plugin Store
2. Öffne die BRAT-Einstellungen → „Add Beta plugin"
3. Gib ein: `KenBlasse/obsidiosaurus`
4. Aktiviere Obsidiosaurus in deiner Plugin-Liste

Passe die Plugin-Einstellungen nach Bedarf an.
Das sind die Default-Einstellungen:

![](assets/obsidiosaurus_plugin_settings.png)
>[!caution] Anhänge-Ordner
>Wenn du den Namen deines Anhänge-Ordners geändert hast, musst du das Feld `Obsidian Asset Folder` in den Plugin-Einstellungen ebenfalls anpassen.


#### Excalidraw (optional)

Obsidiosaurus kann deine Excalidraw-Skizzen für Docusaurus konvertieren und unterstützt dabei Light- und Dark-Mode-Versionen. Damit das funktioniert, müssen deine Einstellungen denen unten entsprechen:

![](assets/excalidraw_plugin_settings_folders.png)
>[!note]
> Der `Excalidraw folder` sollte derselbe wie dein Anhänge-Ordner in Obsidian sein.

![](assets/excalidraw_plugin_settings_filename.png)

>[!danger] Datum im Dateinamen:
>Zusätzliche Punkte (`.`) im Dateinamen stören die Konvertierung. Nutze am besten nur
>`YYYY-MM-DD`, ersetze Punkte durch Bindestriche (`-`), oder lass dieses Feld leer.

![](assets/excalidraw_plugin_settings_export.png)

>[!note] PNG-Support
>Aktuell ist der PNG-Export nicht möglich — das wird in einer zukünftigen Version ergänzt.
>Dann kannst du auch deine Excalidraw-Zeichnungen in der Größe anpassen.

#### Diagrams.net (optional)

Keine Einstellungen zu ändern.

>[!note]  Light- und Dark-Mode
>Wenn deine Website sowohl Light- als auch Dark-Mode unterstützen soll, beachte: Die
>aktuelle Version exportiert nur im Light-Mode. Farben wie weiß und schwarz können
>im Dark-Mode falsch wirken.
