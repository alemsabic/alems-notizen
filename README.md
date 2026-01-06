---
draft: true
---


# alems-notizen (Content)

Dies ist das **Content-Repository** für [ale.ms](https://ale.ms).
Hier entstehen die Zettel, Notizen und Abbildungen.

## Architektur im Überblick

| Bereich | Repository | Beschreibung |
| :--- | :--- | :--- |
| **Content** (Hier) | [alems-notizen](https://github.com/alemsabic/alems-notizen) | Rohe Markdown-Dateien, Obsidian Vault. |
| **Presentation** | [alems-site](https://github.com/alemsabic/alems-site) | Quartz v4 Engine, Layout, Design. |
| **Factory** | [zettel-fabrik](https://github.com/alemsabic/zettel-fabrik) | *Privat*. Recherchen, Experimente. |

## Workflow

1.  **Schreiben:** Bearbeite Inhalte hier (Obsidian).
2.  **Pushen:** `git push` triggert den Prozess.
3.  **Live:** GitHub Actions synchronisiert den Inhalt zu `alems-site`, Cloudflare Pages baut die Seite.