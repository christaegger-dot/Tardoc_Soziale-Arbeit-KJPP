# Tarif-Kompass 2026 · Soziale Arbeit KJPP

Interaktiver Praxisleitfaden für die Tarifabrechnung nach TARDOC Kapitel EA.05 für Soziale Arbeit in der KJPP-Tagesklinik (Kinder- und Jugendpsychiatrie).

## Über das Projekt

Dieser Kompass richtet sich an nichtärztliche Fachpersonen (Soziale Arbeit) in der KJPP-Tagesklinik und erklärt praxisnah:

- **5 Grundregeln** für die tägliche Tarifabrechnung (OFFIZIELL / INTERN / PRAXIS jeweils markiert)
- **Mengengrenzen**: 4-Stunden-Regel und LAP-Topf (240 Min / 90 Tage)
- **Interaktiver Entscheidungsbaum** zur Leistungsziffer-Auswahl (Schritt-für-Schritt oder Vollansicht)
- **Alle relevanten EA.05-Positionen** mit Beschreibung und Dokumentationshinweisen
- **8 Alltagsszenarien** mit korrekter Buchungslogik
- **Kurzfassung** mit 7-Punkte-Spickzettel für hektische Tagesklinikmomente

## Schnellstart

Öffne `index.html` (oder `tarif-kompass-2026.html`) direkt im Browser – keine Installation nötig. Die Seite funktioniert vollständig offline.

```bash
# Einfach lokal öffnen:
open index.html
# oder in einem Verzeichnis mit einem lokalen Server starten:
npx serve .
```

## Druckseiten

Im Ordner `files/` befinden sich vier A4-optimierte Druckseiten:

| Datei | Inhalt |
|---|---|
| `entscheidungsbaum-print.html` | Visueller Entscheidungsbaum auf einer A4-Seite |
| `spickzettel-print.html` | Kompakter Spickzettel mit Kurzentscheiden und Limiten |
| `positionen-print.html` | Alle EA.05-Positionen mit Beschreibungen |
| `verlaufseintrag-print.html` | Checklisten für korrekte Verlaufseinträge |

Zum Drucken: Seite im Browser öffnen → `Datei → Drucken` (A4 Hochformat empfohlen).

## Navigation

- **Desktop (≥ 900 px):** Seitenleiste links
- **Tablet (600–900 px):** Horizontale Navigationsleiste oben
- **Mobil (≤ 600 px):** Floating-Button unten → Bottom-Sheet öffnet sich

## Begriffe

| Kürzel | Bedeutung |
|---|---|
| **OFFIZIELL** | Regelung gemäss TARDOC EA.05 |
| **INTERN** | KJPP-interne Steuerungsregel |
| **PRAXIS** | Dokumentationshilfe / Praxishinweis |
| **LAP** | Leistungen in Abwesenheit des Patienten |

## Technologie

Reine HTML/CSS/JavaScript-Einzeldatei ohne externe Abhängigkeiten (ausser Google Fonts).  
Kein Build-Prozess, keine Pakete – einfach öffnen und verwenden.

## Verwandte Ressourcen

- [Psychologinnen-Version (KJPP)](https://tardoc-psychologiekjpp.netlify.app/) – analoger Kompass für Psychologinnen

## Lizenz

Dieses Projekt ist für den internen Gebrauch in der KJPP-Tagesklinik Zürich vorgesehen.  
Referenz: TARDOC Kapitel EA.05 · Gültig ab 01.01.2026 · Stand: 16.03.2026