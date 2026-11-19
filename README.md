# SAP CP Controlling – Lern-App

Lern-App für die Prüfung SAP Competence Pass, Teil CT (Controlling Tasks), bei Digicomp am 20.11.2026.

## Funktionen

- **Quiz** mit 178 Multiple-Choice-Fragen (94 mit einer, 84 mit mehreren richtigen Antworten), davon 12 zu den Kursaufgaben 1–7 (Teil K) und 30 zu Kurs-Mitschnitt und Skript-Fallstudie Aufgaben 8–20 (Teil L); 22 Fragen sind als «laut Trainer prüfungsrelevant» (blaue Smileys auf seinen Folien) markiert und separat übbar; automatisch ausgewertet, mit Musterantwort und Skript-Kapitel bzw. -Seite; falsch beantwortete Fragen kommen öfter
- **Karteikarten** mit 54 Transaktionscodes und Befehlen (neu SU3 und KA01 aus dem Kurs) sowie 14 Tastaturkürzeln, in beide Richtungen
- **Prüfungssimulation**: 40 zufällige Multiple-Choice-Fragen in 60 Minuten, Ergebnis erst am Ende in Prozent (bestanden ab 60 %, Auszeichnung ab 80 %); eine Frage zählt nur, wenn alle richtigen und keine falschen Antworten angekreuzt sind
- **Lösungen**: alle 20 Skript-Aufgaben mit Werten und Schritt-für-Schritt-Anleitung für SAP GUI und Fiori (umschaltbar), mit anklickbaren Skript-Seiten
- **Suche und Skript-Ansicht**: Stichworte oder ganze Fragen (Füllwörter werden ignoriert, Wortanfänge zählen, beste Treffer zuerst) zuerst in Fragen und Karteikarten (direkt öffnen mit «Frage öffnen» bzw. «Karte öffnen», zurück mit «Zurück zur Suche»), danach in Skript-Inhaltsverzeichnis und, nach einmaligem Laden des eigenen Skript-PDFs, in allen Skript-Seiten; jede Seite lässt sich in der App ansehen (Reiter «Skript», Knopf «Seite ansehen», anklickbare Seitenzahlen in den Musterantworten). Das PDF wird nur im eigenen Browser gespeichert (IndexedDB) und liegt nicht in diesem Repository. Anzeige mit pdf.js (Ordner pdfjs, Apache License 2.0)
- **Fortschritt** wird nur im eigenen Browser gespeichert (localStorage), nichts wird ins Internet übertragen

## Quelle der Inhalte

Fragen und Antworten stammen aus dem Katalog „Prüfungsfragen mit Musterantworten SAP CP Controlling“, am 16.11.2026 mit dem Skriptum SAP CP CT (Version 1.0 CH, bizConsult 2024) abgeglichen. Die Kapitel stehen in Klammern. Es sind keine echten Prüfungsfragen. Die falschen Antwortmöglichkeiten sind selbst formulierte typische Verwechslungen.

## Bedienung

Die App ist eine einzige Datei `index.html` und läuft über GitHub Pages im Browser, auch auf dem Handy.
