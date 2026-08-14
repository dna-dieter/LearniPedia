# LearniPedia

**Das Wikipedia der Bildung — Manifest & Rahmenbedingungen**

Bildung ist kein Privileg und kein Marktplatz. Bildung ist ein unantastbares Grundrecht.

LearniPedia ist ein kostenfreies, unzensiertes und anonymes Bildungsangebot: gesteuert
durch lokal betriebene Open-Source-Sprachmodelle, validiert durch Pädagogen, betrieben
auf dezentraler Infrastruktur ohne Abhängigkeit von kommerziellen Cloud-Anbietern.

## Inhalt dieses Repositorys

| Datei | Beschreibung |
|---|---|
| `Konzept.tex` | Das vollständige Manifest als LaTeX-Quelle (Credo, Struktur, Aufruf) |
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

## Aufbau des Manifests

Das Konzept ist in sechs Teile plus Anhang gegliedert:

| Teil | Inhalt |
|---|---|
| I | **Credo** — sieben Sätze, die nicht verhandelbar sind |
| II | **Wikipedia-Grundstrukturen** — Belegpflicht, Versionsgeschichte, Rollen mit entziehbarer Macht, Schiedsverfahren, Trennung von Träger und Inhalt |
| III | **Die sieben Schichten** — Wissensmodell, Inhalts-Lebenszyklus, Didaktik, Bewertung, Nachweis, Technik, Institution |
| IV | **Anerkennung ohne Akkreditierung** — der Weg zu weltweit tragfähigen Nachweisen ohne staatliche Zulassung |
| V | **Was wir nicht gelöst haben** — Engstellen und Zielkonflikte |
| VI | **Aufruf** — adressatenspezifisch, mit je einem konkreten ersten Schritt |
| Anhang | Begründungen, Quellen und die Schwachstellen der Argumentation |

## Grundsätze

- **Unabhängigkeit von Big Tech** — frei verfügbare Sprachmodelle auf eigener Hardware
- **Datensparsamkeit als Bauweise** — keine Klarnamen, keine Speicherung von
  IP-Adressen, keine sitzungsübergreifenden Profile. Die Registrierungsadresse
  ist das einzige personenbezogene Datum und jederzeit löschbar
- **Infrastructure as Code** — vollständig containerisiert, an jedem Ort neu startbar
- **Frustrationsloses Lernen** — keine Noten, kein Zeitkorsett, selbstgesetzte Ziele
- **Spendenfinanzierung** — dauerhaft kostenfreie Nutzung, mit Deckelung des Anteils
  einzelner Geber und Ablehnungsrecht für Mittel mit inhaltlichen Erwartungen
- **Gewaltenteilung** — der Träger stellt Infrastruktur bereit und hat keine
  inhaltliche Weisungsbefugnis. Wer Server bezahlt, bestimmt nicht, was gelehrt wird
- **Belegpflicht** — keine Quelle, keine Lehraussage. Zugleich unser Gegenmittel
  gegen Halluzination
- **Anerkennung durch Nachprüfbarkeit** — wir bitten nicht um Vertrauen, sondern
  machen Nachprüfen billiger als Vertrauen

## Belegte Aussagen

Das Manifest stützt sich auf zitierte Quellen und benennt offene Punkte ausdrücklich.
Teil V listet sie gebündelt, darunter:

- Prüfungsintegrität unter KI-Bedingungen — ohne glaubwürdige Prüfung kein
  anerkannter Nachweis
- Anonymität gegen Zertifizierbarkeit — anonym lernen geht, anonym zertifizieren nicht
- die Einordnung von Bildungs-KI als Hochrisiko-System nach Anhang III der
  EU-KI-Verordnung und die Spannung zwischen Art. 12 und der Datensparsamkeit
- Anonymität gegen Kinder- und Jugendschutz
- Fairnessnachweis gegen Datensparsamkeit — ein Bias-Audit braucht genau die
  Merkmale, die die Architektur nicht erhebt
- Portabilität gegen Vergessen — Fortschritt ist exportierbar, nach Aufgabe
  eines Zugangs aber unwiederbringlich

Ausdrücklich außer Reichweite bleiben **reglementierte Berufe** (Medizin, Pharmazie,
Rechtsanwaltschaft, Lehramt, Pflege, prüfende Ingenieurtätigkeit, Luftfahrt). Diese
Fächer lassen sich hier lernen — den Berufszugang bescheinigt LearniPedia nicht.
Ebenso ist das Projekt **kein Ersatz für den Schulbesuch**.

Kritik und Korrekturen sind willkommen — bitte als Issue. Die wirksamste Form der
Mitarbeit ist der begründete Widerspruch zu Teil V.

## Mitwirken

Teil VI des Manifests nennt für jede Gruppe einen konkreten ersten Schritt:

- **Pädagogen und Fachwissenschaftler** — Didaktik-Lenker, Fachreviewer, Prüfer
- **Fachgesellschaften** — Mitzeichner eines gemeinsamen Kompetenzstandards,
  nicht Zulassungsstelle
- **Bildungsforschung** — Partner für die Wirksamkeitsmessung, mit der Freiheit,
  negative Befunde zu veröffentlichen
- **Technische Mitwirkende** — dezentrale Rechenknoten, Nachweisschicht auf offenen
  Standards, Barrierefreiheit, Offline-Fähigkeit
- **Vermittler** — Bibliotheken, Volkshochschulen, Schulen und Hilfsorganisationen
  als Orte für alle ohne Gerät, Anschluss oder digitale Vorerfahrung
- **Unterstützer** — unter den oben genannten Bedingungen
- **Kritiker** — wer eine Stelle aus Teil V zum Einsturz bringt, trägt mehr bei
  als jede zustimmende Weiterleitung

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
