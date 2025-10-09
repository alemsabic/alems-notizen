# alems-zk

> **Zettelkasten für [ale.ms](https://ale.ms)** - Markdown-basierte Wissenssammlung

🌐 **Live Site**: [ale.ms](https://ale.ms)

## 🎯 Über dieses Repository

Dieses Repository ist ein **Zettelkasten** - eine Sammlung von vernetzten Notizen und Wissen in Markdown-Format. Jeder Push synchronisiert automatisch mit der Quartz-Präsentationsschicht und deployt zu Cloudflare Pages.

### Zwei-Repository-Architektur:

1. **alems-zk** (dieses Repo): Zettelkasten-Inhalte (Markdown)
   - https://github.com/alemsabic/alems-zk
2. **alems-site**: Präsentationsschicht (Quartz Static Site Generator)
   - https://github.com/alemsabic/alems-site

**Automatische Synchronisation**: Änderungen hier werden automatisch zur Site deployed.

## 📝 Inhalte Bearbeiten

### Quick Start

```bash
# Repository klonen
git clone https://github.com/alemsabic/alems-zk.git
cd alems-zk

# Markdown-Dateien bearbeiten
# (Beliebiger Editor: VS Code, Obsidian, etc.)

# Commit und Push
git add .
git commit -m "content: deine Beschreibung"
git push

# Warte 1-2 Minuten → Live auf https://ale.ms
```

### Content-Struktur

```
alems-zk/
├── index.md              # Homepage
├── about.md             # About-Seite
└── Projekte/            # Projekte und Themen
    ├── project-one.md
    └── project-two.md
```

### Markdown-Richtlinien

Alle Content-Dateien sollten YAML Frontmatter enthalten:

```yaml
---
title: "Dein Seitentitel"
tags:
  - ai
  - learning
---

Dein Inhalt hier...
```

## 🔄 Auto-Deployment-Pipeline

```
1. Bearbeiten & Push zu diesem Repo
   ↓
2. GitHub Action triggert
   ↓
3. Sync zum Quartz-Repository
   ↓
4. Cloudflare Pages Build & Deploy
   ↓
5. Live auf https://ale.ms (1-2 Min)
```

## 🤖 Nutzung mit Obsidian

Dieses Repository funktioniert perfekt als Obsidian-Vault:

1. Obsidian öffnen
2. "Open folder as vault"
3. Diesen Repository-Ordner auswählen
4. Mit vollen Obsidian-Features bearbeiten
5. Commit & Push wie gewohnt

**Empfohlene Plugins**:
- Git (für Auto-Commit)
- Templater (für Content-Templates)
- Tag Wrangler (für Tag-Management)

## 🛠️ Technische Details

- **Static Site Generator**: [Quartz v4.5.1](https://quartz.jzhao.xyz/)
- **Quartz Repository**: [alemsabic/alems-site](https://github.com/alemsabic/alems-site)
- **Hosting**: Cloudflare Pages
- **Auto-Sync**: GitHub Actions
- **Live Site**: [ale.ms](https://ale.ms)

## 📚 Dokumentation

- **[CLAUDE.md](./CLAUDE.md)** - Detaillierter Kontext für KI-Assistenten
- **[SETUP-TOKEN.md](./SETUP-TOKEN.md)** - GitHub Token Setup Guide
- **[Quartz Docs](https://quartz.jzhao.xyz/)** - Offizielle Quartz-Dokumentation
- **[Live Site](https://ale.ms)** - Die veröffentlichte Website

## 🗂️ Zettelkasten-Prinzipien

Dieser Zettelkasten folgt grundlegenden Prinzipien:

- **Atomare Notizen**: Jede Notiz behandelt eine einzelne Idee
- **Verknüpfungen**: Notizen sind über Wikilinks verbunden `[[andere-notiz]]`
- **Tags**: Kategorisierung über Frontmatter-Tags
- **Kontinuierliche Entwicklung**: Notizen werden laufend erweitert und verfeinert

## 📄 Lizenz

Inhalte in diesem Repository sind persönliche Notizen und Kursunterlagen.

---

**Fragen?** Siehe [CLAUDE.md](./CLAUDE.md) für vollständige Dokumentation.
