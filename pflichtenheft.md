# Pflichtenheft **"Obst und Gemuese Meier oHG"**
---
## 1. Zielbestimmung

### 1.1 Musskriterien

- Lagersystem fuer die Waren
- Verwaltung von Produktdaten (Gemuese & Obstsorten)
- Ausgabe bestimmter Daten aller Produkte (alphabetische Liste)
- Ausgabe aller Daten eines Produkts
- Lieferschein Erstellung
- Suche mit Endbenutzersprache

### 1.2 Wunschkriterien

- Anwendung von Filter auf Produktliste (Attribute hinzunehmen oder entfernen)
- Sortieren der Produktliste nach Attributen
- Liste aller Lieferanten
- Liste aller Produzenten
- Liste aller Kunden

### 1.3 Abgrenzungskriterien

- keine Vorbestellungen
- keine Portierung auf andere Rechnerplatformen benoetigt
**TODO**

## 2. Produkteinsatz

### 2.1 Anwendungsbereiche

- Verwaltung Lager
- Verwaltung Kunden

### 2.2 Zielgruppen
 
- Geschaeftsfuehrer 
- Aushilfe

### 2.3 Betriebsbedingungen

- Rechner im Verkausfsraum
- Rechner im Lager

## 3. Produktuebersicht

**TODO: insert graphics**

## 4. Produktfunktionen

### 4.1 Anwendungsfaelle

**/F01/**
- Geschaeftsprozess: Hinzufuegen, Aendern, Loeschen von Produkten
- Ziel: User veraendert Produktdatenbank
- Kategorie: primaer
- Vorbedingung: - 
- Nachbedingung Erfolg: Datenbestand geaendert
- Nachbedingung Fehlschlag: Datenbestand **nicht** geandert
- Akteure: Geschaeftsfuehrer, Aushilfe
- Beschreibung: 
	- entsprechender Datenbestand veraendern
  - Datenbestand aktualisieren und Meldung ausgeben
- Erweiterung:
	- neuen Datensatz erfassen
  - Datensatz loeschen
  - Datensatz aendern
  
**/F02/**
- Geschaeftsprozess: Hinzufuegen, Aendern, Loeschen von Kundendaten
- Ziel: User veraendert Kundendatenbank
- Kategorie: primaer
- Vorbedingung: - 
- Nachbedingung Erfolg: Datenbestand geaendert
- Nachbedingung Fehlschlag: Datenbestand **nicht** geandert
- Akteure: Geschaeftsfuehrer, Aushilfe
- Beschreibung: 
	- entsprechender Datenbestand veraendern
  - Datenbestand aktualisieren und Meldung ausgeben
- Erweiterung:
	- neuen Datensatz erfassen
  - Datensatz loeschen
  - Datensatz aendern
  
**/F03/**
- Geschaeftsprozess: Hinzufuegen, Aendern, Loeschen von Lieferantendaten
- Ziel: User veraendert Lieferantendaten
- Kategorie: primaer
- Vorbedingung: - 
- Nachbedingung Erfolg: Datenbestand geaendert
- Nachbedingung Fehlschlag: Datenbestand **nicht** geandert
- Akteure: Geschaeftsfuehrer
- Beschreibung: 
	- entsprechender Datenbestand veraendern
  - Datenbestand aktualisieren und Meldung ausgeben
- Erweiterung:
	- neuen Datensatz erfassen
  - Datensatz loeschen
  - Datensatz aendern
  
**/F04/**
- Geschaeftsprozess: Hinzufuegen, Aendern, Loeschen von Produzentendaten
- Ziel: User veraendert Produzentendaten
- Kategorie: primaer
- Vorbedingung: - 
- Nachbedingung Erfolg: Datenbestand geaendert
- Nachbedingung Fehlschlag: Datenbestand **nicht** geandert
- Akteure: Geschaeftsfuehrer
- Beschreibung: 
	- entsprechender Datenbestand veraendern
  - Datenbestand aktualisieren und Meldung ausgeben
- Erweiterung:
	- neuen Datensatz erfassen
  - Datensatz loeschen
  - Datensatz aendern
  
**/F05/**
- Geschaeftsprozess: Ausgabe bestimmter Daten aller Produkte (alphabetische Liste)
- Ziel: User erhaelt Produktliste
- Kategorie: primaer
- Vorbedingung: - 
- Nachbedingung Erfolg: Rueckgabe einer Liste
- Nachbedingung Fehlschlag: Fehlermeldung
- Akteure: Geschaeftsfuehrer, Aushilfe
- Beschreibung: 
	- Ausgabe von folgenden Daten pro Produkt als Liste: 
  	- Anzahl
    - Bezeichnung
    - Kategorie
    - Einkaufsdatum
    - Mindesthaltbarkeitsdatum
    - Preis
    - **TODO**
- Erweiterung: - 
  
**/F06/**
- Geschaeftsprozess: Ausgabe aller Daten **eines** Produkts
- Ziel: User erhaelt alle Daten eines Produkts
- Kategorie: primaer
- Vorbedingung: Eingabe des Produkts anhand **Bezeichnung** 
- Nachbedingung Erfolg: Rueckgabe einer Liste
- Nachbedingung Fehlschlag: Fehlermeldung
- Akteure: Geschaeftsfuehrer, Aushilfe
- Beschreibung: 
	- Ausgabe von **allen** Daten eines Produkts
- Erweiterung: - 

**/F07/**
- Geschaeftsprozess: Lieferschein erstellen fuer Kunden
- Ziel: User erhaelt Lieferschein
- Kategorie: primaer
- Vorbedingung: 
	- Eingabe des Kunden
  - Eingabe von Positionen
- Nachbedingung Erfolg: Rueckgabe eines Dokuments
- Nachbedingung Fehlschlag: Fehlermeldung
- Akteure: Geschaeftsfuehrer, Aushilfe
- Beschreibung: 
	- Kundendaten aus Kundendatenbank abrufen und eintragen
  - eingegebene Positionen (Menge, Bezeichnung) eintragen
  - Dokument erzeugen
- Erweiterung: - 

**/F08/**
- Geschaeftsprozess: Suche mit Endbenutzersprache
- Ziel: User erhaelt Suchergebnis(se)
- Kategorie: primaer
- Vorbedingung: 
	- Eingabe des Suchbegriffs
- Nachbedingung Erfolg: Rueckgabe einer Liste
- Nachbedingung Fehlschlag: Fehlermeldung
- Akteure: Geschaeftsfuehrer, Aushilfe
- Beschreibung: 
	- Vergleich des Suchbegriffs mit allen Elementen in allen Datenbanken
  - Ausgabe aller "Matches"
- Erweiterung: - 
  

## 5. Produktdaten
**/D01/ Produktdaten**
- Anzahl
- Bezeichnung
- Herkunft(Land, Region)
- Kategorie
- Verkaufspreis
- Einkaufspreis
- Bezugsquelle


**/D02/ Lieferantendaten**
- Name
- Adresse
- Preisliste

**/D03/ Produzent**
- Name
- Adresse
- Preisliste

**/D04/ Kunde**
- Name
- Adresse

## 6. Leistungsanforderungen

**/L01/ Listenausgabe**
- 1000 Produkte müssen innerhalb von 2 Sekunden abegrufen werden können!

**WIP** Verfeinerung / Eigene ANforderungen

## 7. Qualitätsanforderung

**TODO WEITERE ASPEKTE**

| Produktqualität | sehr gut | gut | normal |nicht relevant |
|---|---|---|---|---|
| **Funktionalität** | | | | |
|Angemessenheit|X | | | |
|Richtigkeit| |X | | |
|Interoperabilität|X |X | | |
|Ordnungsmäßigkeit|X | | | |
|Sicherheit| | |X | |
|Übertragbarkeit| | | |X|
|**Zuverlässigkeit**| | | | |
|Reife| | |X | |
|Fehlertoleranz| | |X | |
|Wiederherstellbarkeit| | |X | |
|**Benutzbarkeit**| | | | |
|Verständlichkeit| | |X | |
|Erlernbarkeit| |X | | |
|Bedienbarkeit| |X | | |
|Effizienz|X | | | |
|Zeitverhalten|X | | | |

## 8. Benutzungsoberflaeche

**/B01/ Aussehen**

- Responsives Design, fuer Darstellung auf kleinem Monitor im Verkaufsraum, aber auch grosses Display im Lager
- Einfache Designsprache, klare Schrift (Kontrast), evtl. barrierefrei

**/B02/ Aufbau**

- "uebersichtliche Struktur"
- Oberer Bereich: Menueleiste mit Optionen
  - Datenbankoperationen(/F01-F04/)
    - Produkt
    - Kunde
    - Lieferant
    - Produzent
  - Ausgabe von Daten (/F05-F06/)
  - Lieferscheinerstellung (/F07/)
  - Suche (/F08/)
- Mittlerer Bereich: Darstellung der Operation/Anfrage

**/B03/ Fehleingaben**

- Fehleingaben beispielsweise bei Datenbankoperationen muessen abgefangen werden und eine Fehlermeldung muss angezeigt werden

**/B04/ Authentifizierung**

- Zugang zur Software muss autorisiert werden

**/B05/ Hilfedatenbank**

- an passenden Stellen werden Hilfetexte eingeblendet

## 9. Lieferanforderungen

- ausfuehrbares Programm in 9 Monaten
- Installation und Einweisung vor Ort

## 10. Anforderungen an Dokumentation

- Benutzerhandbuch und Installationshinweise
- Changelog

## 11. Nichtfunktionale Anforderungen

- Authentifizierung
- Alle Datenbanken verschluesselt
- Preis 0 EUR oder Rabatt groesser 10% nur durch Authentifizierung des Geschaeftsfuehrers
- alle Loeschoperationen nur durch Geschaeftsfuehrer moeglich

## 12. Technische Produktumgebung

### 12.1 Software

- Webbrowser (plattformunabhängig)

### 12.2 Hardware

- PC
- Laptop
- Tablet
- Smartphone

### 12.3 Orgware

**TODO ERGÄNZEN**

- Intranet
- Cloud? --> synchronisation?

### 12.4 Produkt Schnittstellen

- Druckeranbindung (Lieferscheine)
- Barcode Scanner

## 13. Spezielle Anforderungen an die Entwicklungsumgebung

- **Node.js (Backend)**
- **Angular 6 (Frontend)**

### Software
- Texteditor

### Hardware 
- PC, Laptop

### Produktschnittschtelle
- Gitlab mit Issue handling

## 14. Gliederung in Teilprodukte

nicht erfoderlich.

## 15. Globale Testfälle

**/T01/**

- **Bezeichnung**: Produkt anlegen
- **Beschreibung**: Erstellen eines Datenbestand
- **Vorbedingung**: Produkt darf nicht vorhanden sein
- **Sollverhalten**: Datenbestand erzeugt

**/T02/**

- **Bezeichnung**: Produkt änderung
- **Beschreibung**: Änderung eines Datenbestand
- **Vorbedingung**: Produkt muss vorhanden sein
- **Sollverhalten**: Datenbestand veraendert

**/T03/**

- **Bezeichnung**: Kundendaten anlegen
- **Beschreibung**: Erstellen eines Datensatzes
- **Vorbedingung**: Kunde darf nicht vorhanden sein
- **Sollverhalten**: Datensatz wird erfolgreich angelegt

**/T04/**

- **Bezeichnung**: Kundendaten änderung
- **Beschreibung**: Änderung eines Datensatzes
- **Vorbedingung**: Kunde muss vorhanden sein
- **Sollverhalten**: Datensatz wird erfolgreich geändert

**/T05/**

- **Bezeichnung**: Kundendaten löschen
- **Beschreibung**: Löschen eines Datensatzes
- **Vorbedingung**: Kunde muss vorhanden sein
- **Sollverhalten**: Datensatz wird erfolgreich gelöscht

**/T06/**

- **Bezeichnung**: Lieferant anlegen
- **Beschreibung**: Erstellen eines Datensatzes
- **Vorbedingung**: Lieferant darf nicht vorhanden sein
- **Sollverhalten**: Datensatz wird erfolgreich angelegt

**/T07/**

- **Bezeichnung**: Lieferant ändern
- **Beschreibung**: Ändern eines Datensatzes
- **Vorbedingung**: Lieferant muss vorhanden sein
- **Sollverhalten**: Datensatz wird erfolgreich geändert

**/T08/**

- **Bezeichnung**: Produzent anlegen
- **Beschreibung**: Erstellen eines Datensatzes
- **Vorbedingung**: Produzent darf noch nicht vorhanden sein
- **Sollverhalten**: Datensatz wird erfolgreich angelegt

**/T09/**

- **Bezeichnung**: Produzent ändern
- **Beschreibung**: Ändern eines Datensatzes
- **Vorbedingung**: Produzent muss vorhanden sein
- **Sollverhalten**: Datensatz wird erfolgreich geändert

**/T10/**

- **Bezeichnung**: Ausgabe bestimmter Produktdaten
- **Beschreibung**: Produktliste ausgeben lassen 
- **Vorbedingung**: -
- **Sollverhalten**: Eine Liste von Produkten

**/T11/**

- **Bezeichnung**: Alle Produktdaten ausgeben
- **Beschreibung**: Zu einem Produkt alle informationen ausgeben 
- **Vorbedingung**: Produktbezeichnung muss gegeben sein
- **Sollverhalten**: Ein Produkt mit allen informationen, welche es zu dem Produkt gibt

**/T12/**

- **Bezeichnung**: Lieferschein erstellen
- **Beschreibung**: Erstellen eines Lieferschein fuer einen Kunden
- **Vorbedingung**: Kunde und Position muss gegeben sein
- **Sollverhalten**: Ein Lieferschein wird erstellt

**/T13/**

- **Bezeichnung**: Suche mit Endbenutzersprache
- **Beschreibung**: Suche nach einem Begriff in Deutsch 
- **Vorbedingung**: Ein Suchbegriff in Deutsch muss eingegeben werden
- **Sollverhalten**: Alle Produkte, Lieferanten und Produzenten, welche den Suchbegriff als information beinhalten, werden ausgegeben

## 16. Ergaenzungen/Glossar

