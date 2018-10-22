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
|Angemessenheit| | | | |
|Richtigkeit| | | | |
|Interoperabilität| | | | |
|Ordnungsmäßigkeit| | | | |
|Sicherheit| | | | |
|Übertragbarkeit| | | |X|
|**Zuverlässigkeit**| | | | |
|Reife| | | | |
|Fehlertoleranz| | | | |
|Wiederherstellbarkeit| | | | |
|**Benutzbarkeit**| | | | |
|Verständlichkeit| | | | |
|Erlernbarkeit| | | | |
|Bedienbarkeit| | | | |
|Effizienz| | | | |
|Zeitverhalten| | | | |

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

**/B05/ Hilfedatenbank

- an passenden Stellen werden Hilfetexte eingeblendet

## 9. Lieferanforderungen

## 10. Anforderungen an Dokumentation

## 11. Nichtfunktionale Anforderungen

## 12. Technische Produktumgebung

### 12.1 Software
### 12.2 Hardware
### 12.3 Orgware
### 12.4 Produkt Schnittstellen

## 13. Spezielle Anforderungen an die Entwicklungsumgebung

## 14. Gliederung in Teilprodukte

## 15. Ergaenzungen