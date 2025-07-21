# Hundedatenbank – Mein Lernprojekt als angehender Anwendungsentwickler

## Motivation

Ich befinde mich aktuell in der **Umschulung zum Fachinformatiker für Anwendungsentwicklung**. Dieses Projekt ist Teil meines Lernprozesses. Es hilft mir, grundlegende Konzepte der Programmierung – besonders in Python – besser zu verstehen und praktisch anzuwenden.

Ich wollte ein Thema wählen, das mir Spaß macht und gleichzeitig nicht zu abstrakt ist. So entstand die Idee einer kleinen **interaktiven Hundedatenbank**, bei der man durch gezielte Fragen passende Hunderassen finden kann.

---

## Lernziele

Mit diesem Projekt verfolge ich folgende Ziele:

- **Verständnis für verschachtelte Datenstrukturen** wie Dictionaries und Listen vertiefen
- Den **Umgang mit Benutzereingaben** und deren Validierung lernen
- Erste **Erfahrungen mit funktionaler Strukturierung** (z. B. durch eigene Funktionen) sammeln
- **Klaren, verständlichen Python-Code** schreiben, den ich später leicht erweitern oder erklären kann

---

## Projektaufbau

Das Herzstück dieses Projekts ist ein verschachteltes Dictionary namens `hunde_info`, das Hunderassen nach folgenden Eigenschaften sortiert:

- **Farbe** (`braun`, `schwarz`, `weiß`, `golden`, `grau`, `rot`, `mehrfarbig`)
- **Größe** (`klein`, `mittel`, `groß`)
- **Körperbau** (`kräftig`, `schmal`)

### Hauptfunktionen

- `sichere_eingabe(frage, erlaubt_werte)`:  
  Eine Helferfunktion zur Eingabeprüfung. Sie stellt sicher, dass der Benutzer nur gültige Optionen eingibt.

- `hunde_finden()`:  
  Diese Funktion fragt interaktiv Farbe, Größe und Körperbau ab und gibt dann passende Hunderassen aus der Datenbank zurück.

### Beispielhafte Benutzereingabe

```text
Welche Farbe hat der Hund? braun
Welche Größe hat der Hund? klein
Wie ist der Körperbau? kräftig

Diese Hunderassen passen zu deiner Beschreibung:
Dackel, Mops, Chihuahua, Französische Bulldogge
