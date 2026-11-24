# Seerettungsdienste Bodensee / Zürichsee / Neuenburgersee / Genfersee

Stand: 17.09.2026

## Dateien

| Datei | Inhalt |
|---|---|
| `seerettung_kontakte.xlsx` / `.csv` | Kontakttabelle (Organisation, Bereich, Notruf, Telefon, E-Mail, Website) |
| `genfersee_sektionen.csv` | die 33 SISL-Sektionen mit Sektorfläche |
| `seerettung_<see>.gpx` | Zuständigkeitsbereiche als geschlossene Tracks (ein Track = ein Dienst), Genfersee zusätzlich mit Waypoints der Rettungsstationen |
| `seerettung_<see>.geojson` | dieselben Sektoren als Polygone (mit Inseln als Löcher) |
| `uebersicht.png` | Übersichtskarte aller vier Seen |

## Geometrie-Grundlage

Seepolygone: swissTLM3D 2.4 (2026), Bundesamt für Landestopografie swisstopo,
via github.com/oliverheisel/LakesOfSwitzerland (WGS84). Der Bodensee umfasst Ober- und
Untersee, der Zürichsee den Obersee bis Schmerikon.

## Wie die Sektoren gebildet wurden

* **Bodensee, Zürichsee, Neuenburgersee:** Das Ufer ist in Abschnitte je Dienst
  aufgeteilt (Gemeinde- bzw. Landesgrenzen am Ufer). Jeder Wasserpunkt gehört zum
  nächstgelegenen Uferabschnitt. Das bildet die übliche Regel «Ufergemeinde bis
  Seemitte» ab.
* **Genfersee:** Für die 34 SISL-Sektionen bestehen keine publizierten Sektorgrenzen;
  alarmiert wird über die Polizei die nächstgelegene Sektion. Modelliert ist deshalb
  die nächstgelegene Rettungsstation (Voronoi). Sektionen Vevey-Sentinelle und
  Vevey-Vétéran sind zu einem Sektor zusammengefasst.

## Vorbehalte

* Die Grenzen sind **Annäherungen**, nicht die rechtsverbindlichen Einsatzräume.
  Verbindlich sind die kantonalen Schifffahrtsämter, Polizeikorps und die Dienste selbst.
* Im Bodensee-Obersee gibt es keine Staatsgrenze (Kondominium); die Linien folgen
  hier den Uferzuständigkeiten.
* Erlenbach (ZH) ist seit 2024/25 zwischen dem SRD-Verbund Horgen und dem SRD
  Küsnacht strittig; hier Küsnacht-Erlenbach zugeordnet.
* Neuenburgersee: die Grenze SIS Neuchâtel / SSBL (Neuchâtel–Hauterive) und die
  Zuordnung des Nordwestufers (Béroche, Bevaix, Cortaillod) zum SIS Neuchâtel sind
  Annahmen; publiziert sind nur die Grenzen Yvonand, Chevroux und Broyekanal.
* Alarmierung immer über die Notrufnummern, nicht über die Telefonnummern der Dienste.
