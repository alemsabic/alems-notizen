# ale.ms – Zettelkasten

> **Füge Deiner Intelligenz eine Intelligenz hinzu.**

🌐 **Live Site**: [ale.ms](https://ale.ms)

## Was ist das?

Ein öffentlicher **Zettelkasten** zum Lernen und Lehren von Künstlicher Intelligenz – erstellt *mit* KI, strukturiert nach der Zettelkasten-Methode.

### Zettelkasten-Methode

Ein System vernetzter, atomarer Notizen. Entwickelt von Denkern wie Niklas Luhmann, ermöglicht es systematische Wissensentwicklung durch Verknüpfung von Ideen.

### KI lernen mit KI

Dieser Zettelkasten ist ein Experiment: Lernen über Künstliche Intelligenz zusammen mit Claude (KI) als Denkpartner.

## Inhalt

### [[_meta/|Meta-Bereich]]: Zettelkasten-Theorie

Verstehe die Methode:
- **[Prinzipien](https://ale.ms/_meta/prinzipien)** – Atomarität, Verknüpfung, Emergenz
- **[Workflow](https://ale.ms/_meta/workflow)** – Praktische Anleitung
- **[Mit KI arbeiten](https://ale.ms/_meta/mit-ki-arbeiten)** – KI als Denkpartner
- **[Pioniere](https://ale.ms/_meta/pioniere/luhmann)** – Luhmann, Blumenberg, Schmidt

### KI-Grundlagen (in Entwicklung)

Hier entstehen Notizen zu Künstlicher Intelligenz – der Zettelkasten wächst organisch.

## Technologie

**Struktur:**
- Geschrieben in [Obsidian](https://obsidian.md/)
- Veröffentlicht mit [Quartz v4.5.1](https://quartz.jzhao.xyz/)
- Markdown mit `[[Wikilinks]]`

**Architektur:**
1. **alems-zk** (dieses Repo): Zettelkasten-Inhalte
2. **[alems-site](https://github.com/alemsabic/alems-site)**: Präsentationsschicht (Quartz)

**Deployment:**
- Push → GitHub Action → Sync → Cloudflare Pages → Live (1-2 Min)

## Für Entwickler

### Repository klonen

```bash
git clone https://github.com/alemsabic/alems-zk.git
cd alems-zk
```

### Mit Obsidian nutzen

1. Obsidian öffnen → "Open folder as vault"
2. Diesen Ordner auswählen
3. Bearbeiten mit Obsidian-Features
4. Git commit & push

**Empfohlene Plugins:**
- Git (für Auto-Commit)
- Templater (für Content-Templates)
- Tag Wrangler (für Tag-Management)

### Markdown-Format

Alle Notizen mit YAML Frontmatter:

```yaml
---
title: "Titel der Notiz"
tags:
  - ki
  - zettelkasten
---

Inhalt hier...
```

### Verknüpfungen

Nutze Wikilinks: `[[andere-notiz]]`

Quartz erstellt automatisch bidirektionale Links und Backlinks.

## Zettelkasten-Prinzipien

- **Atomare Notizen**: Eine Idee pro Zettel
- **Verknüpfungen**: Zettel leben durch ihre Beziehungen
- **Eigene Sprache**: In eigenen Worten formulieren
- **Kontinuität**: Organisches Wachstum über Zeit

## Ressourcen

- **Live Site**: [ale.ms](https://ale.ms)
- **Quartz Repo**: [alemsabic/alems-site](https://github.com/alemsabic/alems-site)
- **Quartz Docs**: [quartz.jzhao.xyz](https://quartz.jzhao.xyz/)
- **Zettelkasten-Methode**: [zettelkasten.de](https://zettelkasten.de/)

## Kontakt

- Website: [alemsabic.com](https://alemsabic.com)
- X/Twitter: [@alemsabic](https://x.com/alemsabic)
- GitHub: [@alemsabic](https://github.com/alemsabic)

## Lizenz

Inhalte sind persönliche Notizen und frei nutzbar als Inspiration für eigene Zettelkasten.

---

**Start:** [ale.ms](https://ale.ms) → [Zettelkasten-Theorie entdecken](https://ale.ms/_meta/)
