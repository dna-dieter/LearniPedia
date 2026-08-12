# LearniPedia

**Das Wikipedia der Bildung — Manifest & Rahmenbedingungen**

Bildung ist kein Privileg und kein Marktplatz. Bildung ist ein unantastbares Grundrecht.

LearniPedia ist ein kostenfreies, unzensiertes und anonymes Bildungsangebot: gesteuert
durch lokal betriebene Open-Source-Sprachmodelle, validiert durch Pädagogen, betrieben
auf dezentraler Infrastruktur ohne Abhängigkeit von kommerziellen Cloud-Anbietern.

## Inhalt dieses Repositorys

| Datei | Beschreibung |
|---|---|
| `Konzept.tex` | Das vollständige Manifest als LaTeX-Quelle |

Das PDF ist ein Build-Artefakt und wird nicht versioniert. Es erscheint als
Release-Asset.

## Dokument erzeugen

Voraussetzung ist eine TeX-Distribution (z. B. TeX Live oder MacTeX):

```bash
pdflatex Konzept.tex
pdflatex Konzept.tex   # zweiter Durchlauf für Fußnoten- und Link-Referenzen
```

## Grundsätze

- **Unabhängigkeit von Big Tech** — frei verfügbare Sprachmodelle auf eigener Hardware
- **Zero-Knowledge-Datenschutz** — keine Klarnamen, keine IP-Adressen, keine Profile
- **Infrastructure as Code** — vollständig containerisiert, an jedem Ort neu startbar
- **Frustrationsloses Lernen** — keine Noten, kein Zeitkorsett, selbstgesetzte Ziele
- **Spendenfinanzierung** — dauerhaft kostenfreie Nutzung

## Belegte Aussagen

Das Manifest stützt sich auf zitierte Quellen und benennt offene Punkte ausdrücklich,
darunter die Einordnung von Bildungs-KI als Hochrisiko-System nach Anhang III des
EU-KI-Acts und die Spannung zwischen Protokollierungspflichten und der
Zero-Knowledge-Architektur. Kritik und Korrekturen sind willkommen — bitte als Issue.

## Mitwirken

Gesucht sind pädagogische Pioniere für das didaktische Regelwerk, Tech-Aktivisten für
dezentrale Rechenknoten und Multiplikatoren für die Reichweite.

## Lizenz

MIT — siehe [LICENSE](LICENSE).
