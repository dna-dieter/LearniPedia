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
| `Konzept.pdf` | Gesetzte Fassung, direkt lesbar ohne TeX-Installation |

Zusätzlich liegt jede veröffentlichte Fassung als
[Release](https://github.com/dna-dieter/LearniPedia/releases) bereit.

## Mitarbeiten ohne lokale TeX-Installation

Niemand muss LaTeX installieren, um am Text mitzuarbeiten. Ein Klick öffnet das
Manifest in Overleaf im Browser, fertig eingerichtet und direkt kompilierbar:

[![In Overleaf öffnen](https://img.shields.io/badge/In%20Overleaf%20%C3%B6ffnen-47A141?logo=overleaf&logoColor=white)](https://www.overleaf.com/docs?snip_uri=https://github.com/dna-dieter/LearniPedia/archive/refs/heads/main.zip)

Overleaf lädt dabei den aktuellen Stand des `main`-Branches als Projektkopie.

**Wichtig zum Rückweg:** Overleaf kann Änderungen nicht kostenfrei nach GitHub
zurückschreiben, denn die Git- und GitHub-Anbindung ist eine
[Premium-Funktion](https://cs.overleaf.com/learn/how-to/Overleaf_premium_features).
Der Weg zurück läuft daher so:

1. In Overleaf bearbeiten und Ergebnis prüfen.
2. `Konzept.tex` herunterladen (Menü → Download).
3. Datei hier im Browser über *Edit* einfügen und einen Pull Request öffnen —
   oder den Vorschlag als [Issue](https://github.com/dna-dieter/LearniPedia/issues)
   einreichen.

Wer nur Text ändern will, kann `Konzept.tex` auch direkt in der GitHub-Weboberfläche
bearbeiten. Das erzeugt sofort einen Commit, zeigt aber keine Vorschau.

## Lokal erzeugen

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

**[CC BY-SA 4.0](LICENSE)** — Creative Commons Namensnennung, Weitergabe unter
gleichen Bedingungen.

Du darfst den Text kopieren, verändern, übersetzen und weitergeben, auch
kommerziell. Zwei Bedingungen: Nennung der Quelle, und Bearbeitungen müssen unter
derselben Lizenz stehen. Damit bleibt jede Weiterentwicklung dieses Manifests
gemeinfrei zugänglich und kann nicht in ein geschlossenes Produkt überführt werden.

Dies ist dieselbe Lizenz, unter der die Texte der Wikipedia stehen — dem Vorbild,
auf das sich dieses Projekt beruft.

> **Hinweis für später:** CC-Lizenzen sind für Prosa gedacht, nicht für Quellcode.
> Sobald dieses Repository Software enthält (Container-Definitionen, Skripte,
> System-Prompts), erhält diese eine eigene Lizenz. Empfehlung dafür: AGPL-3.0,
> damit auch serverseitig betriebene Abwandlungen ihren Quellcode offenlegen
> müssen.
