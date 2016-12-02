# Karte der Verkehrs- und Tarifverb�nde in Deutschland

Dieses Repository stellt die Karte der Verkehrs- und Tarifverb�nde in Deutschland bereit.

Es bietet ein [QGIS](http://www.qgis.org/)-Projekt mit Geodaten der Verkehrs- und Tarifverb�nde in Vektor-Form (ShapeFiles).

# �bersicht

## Karte der Verkehrs- und Tarifverb�nde

![Karte der Verkehrs- und Tarifverb�nde](Bilder/Verbundkarte.png)

## Verf�gbarkeit der Fahrpl�ne

![Verf�gbarkeit der Fahrpl�ne](Bilder/Verf�gbarkeit-der-Fahrpl�ne.png)

## Offene Fahrpl�ne

### SWU

SWU Stadtwerke Ulm/Neu-Ulm GmbH

* [GTFS](https://www.swu.de/privatkunden/swu-nahverkehr/gtfs-daten.html) - offiziell, Lizenz [ODbL 1.0](http://opendatacommons.org/licenses/odbl/1.0/), Zugriff muss beantragt werden

### RNV

Rhein-Neckar-Verkehr GmbH

* [GTFS](https://opendata.rnv-online.de/datensaetze/gtfs-general-transit-feed-specification) - offiziell, Lizenz [DL DE BY 2.0](https://www.govdata.de/dl-de/by-2-0), kein Antrag n�tig

### VBB

VBB Verkehrsverbund Berlin-Brandenburg GmbH

* [GTFS](http://daten.berlin.de/datensaetze?field_tags_tid=723) - offiziell, Lizenz [CC BY 3.0 DE], kein Antrag n�tig

### VRR

Verkehrsverbund Rhein-Ruhr A�R

* [DINO](http://data.ndovloket.nl/vrr/) - inoffiziell, unklare Lizenz, kein Antrag n�tig

### VRS

Verkehrsverbund Rhein-Sieg GmbH

* [GTFS](https://www.vrsinfo.de/fahrplan/oepnv-daten-fuer-webentwickler.html) - offiziell, [Propri�tere Nutzungsvereinbarung](https://www.vrsinfo.de/fileadmin/Dateien/api/NutzervereinbarungODOS.pdf), Zugriff muss beantragt werden

### AVV

Aachener Verkehrsverbund GmbH

* [DINO](http://data.ndovloket.nl/avv/) - inoffiziell, unklare Lizenz, kein Antrag n�tig

## DB Fernverkehr

DB Fernverkehr AG

* [GTFS](https://github.com/fredlockheed/db-fv-gtfs/releases) - inoffiziell, Lizenz [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/), kein Antrag n�tig

# Einrichtung

Aus lizenztechnischen Gr�nden wird Teil des Bildmaterials nicht im Repository ver�ffentlich sonder muss extra herundergeladen und aufbereitet werden.

Das Herunterladen auf Aufbereiten ist erst sehr pragmatisch via Batch-Files gemacht.

## Windows

* [ImageMagick](http://www.imagemagick.org/script/index.php) installieren

```
Verwaltungsgrenzen\download.bat
Verbundkarte\Wikipedia\download.bat
Verbundkarte\Kursbuch\download.bat
Verbundkarte\Kursbuch\crop.bat
Verbundkarte\Kursbuch\append.bat
Verbundkarte\DE\download.bat
Verbundkarte\DE\HE\download.bat
Verbundkarte\DE\SH\download.bat
```

# Lizenz

[CC BY-SA 2.5](https://creativecommons.org/licenses/by-sa/2.5/deed.en)

Wird noch ggf. angepasst.

# Quellen

## [Karte der Verkehrsverb�nde und Tarifverb�nde in Deutschland](https://commons.wikimedia.org/wiki/File:Karte_der_Verkehrsverb%C3%BCnde_und_Tarifverb%C3%BCnde_in_Deutschland.png)

[Karte der Verkehrsverb�nde und Tarifverb�nde in Deutschland](https://commons.wikimedia.org/wiki/File:Karte_der_Verkehrsverb%C3%BCnde_und_Tarifverb%C3%BCnde_in_Deutschland.png) von [Maximilian D�rrbecker](https://de.wikipedia.org/wiki/Benutzer:Chumwa) lizenziert unter [CC BY-SA 2.5](https://creativecommons.org/licenses/by-sa/2.5/deed.en).

![Karte der Verkehrsverb�nde und Tarifverb�nde in Deutschland von Maximilian D�rrbecker lizenziertunter CC BY-SA 2.5](https://upload.wikimedia.org/wikipedia/commons/thumb/f/f3/Karte_der_Verkehrsverb%C3%BCnde_und_Tarifverb%C3%BCnde_in_Deutschland.png/489px-Karte_der_Verkehrsverb%C3%BCnde_und_Tarifverb%C3%BCnde_in_Deutschland.png)

## [Verwaltungsgebiete 1:1.000.000](http://www.geodatenzentrum.de/geodaten/gdz_rahmen.gdz_div?gdz_spr=deu&gdz_akt_zeile=5&gdz_anz_zeile=1&gdz_unt_zeile=17&gdz_user_id=0)

[Verwaltungsgebiete 1:1.000.000](http://www.geodatenzentrum.de/geodaten/gdz_rahmen.gdz_div?gdz_spr=deu&gdz_akt_zeile=5&gdz_anz_zeile=1&gdz_unt_zeile=17&gdz_user_id=0) � GeoBasis-DE / [BKG](http://www.bkg.bund.de/) 2016.

## [Interaktive Verbundkarte](http://kursbuch.bahn.de/hafas/kbview.exe/dn?rt=1&mainframe=IK_verbund) vom [Elektronischen Kursbuch](http://kursbuch.bahn.de/)

Das Urheberrecht an den Kartendaten liegt bei DB Netz AG, I.NVT 52 (V).