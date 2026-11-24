# Velokarte Europa · VIANDAR

Interaktive Velokarte auf der Ridian Karte von Ubique. Zeigt alle EuroVelo Routen mit Ausbaustand sowie Veloland und Mountainbikeland von SchweizMobil. Zu jeder Etappe gibt es Wetter, Veloservices, Vermietungen und aktuelle Sperrungen. In der Schweiz plant die Karte zusätzlich die Reise mit dem ÖV: Ausgangs- und Zielbahnhof eingeben, dann zeigt sie Hinreise, Zeitplan der Etappe und Rückreise mit Angaben zur Velomitnahme.

Herausgeber: VIANDAR GmbH, Reto Schubnell, reto@viandar-outdoor.ch, https://viandar-outdoor.ch

Die Rubrik Gravel zeigt die 19 Gravel-Touren aus der Auswahl «Die schönsten Gravel-Touren» von SchweizMobil. Die Suche läuft über alle Angebote. Ein Ort wie Weinfelden zeigt alle Etappen, Services und Sperrungen im Umkreis von 3 km, ein Name wie Rhein alle Routen und Etappen mit diesem Namen.

## Inhalt

- `index.html`: die ganze Seite in einer Datei, läuft auf GitHub Pages oder lokal im Browser (braucht Internet für Kartenkacheln und Live Daten)
- `eurovelo-etappen-odbl.json`: die aus den EuroVelo GPX Tracks abgeleitete Datenbank (vereinfachte Linien, Längen, Höhenmeter, Länder)

## Quellen und Lizenzen

- **EuroVelo Routen:** Contains information from EuroVelo GPX tracks downloaded from www.EuroVelo.com on 24.11.2026, which is made available here under the Open Database License (ODbL). Die abgeleitete Datenbank in `eurovelo-etappen-odbl.json` und in `index.html` steht ebenfalls unter der ODbL. EuroVelo® ist eine eingetragene Marke der European Cyclists' Federation. Diese Karte ist kein offizielles Angebot von EuroVelo.
- **Nationale EuroVelo Koordinationsstellen:** pro.eurovelo.com
- **Veloland und Mountainbikeland:** © Stiftung SchweizMobil, Geometrie über geo.admin.ch (ASTRA, Kantone)
- **Gravel-Touren:** Auswahl gemäss https://schweizmobil.ch/de/die-schonsten-gravel-touren
- **Sperrungen:** geo.admin.ch, live geladen
- **Karte:** Ridian von Ubique, Daten © OpenStreetMap contributors
- **Veloläden im Umkreis:** © OpenStreetMap contributors, ODbL, live über Overpass
- **ÖV Schweiz:** Haltestellen und Abfahrten von transport.opendata.ch, Verbindungen und Velomitnahme vom search.ch Fahrplan
- **Ortssuche:** Photon von komoot (© OpenStreetMap contributors), in der Schweiz ersatzweise geo.admin.ch
- **Wetter:** Open-Meteo, in der Schweiz Modell ICON-CH2 von MeteoSchweiz

Alle Angaben ohne Gewähr. Die Karte ist eine Planungshilfe. Massgebend sind Verkehrsregeln und Signalisation vor Ort.
