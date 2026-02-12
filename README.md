# awesome-ckan-de
A curated list of all awesome things related to CKAN in deutsch

## Extensions-Kataloge

* **CKAN-Hub** Alle CKAN Extensions auf einen Blick. CKAN-Versionen im Überblick. CKAN-Statistiken. CKAN-Services.
* **CKAN Ecosystem Catalog** Open Data Portals based on CKAN, Extension Catalog

## Überblick Open Data Portale

* **Open Data Portal Watch** Über 280 Open Data Portale weltweit im Überblick | Wirtschaftsuniversität Wien | https://data.wu.ac.at/portalwatch/
* **CKAN instances around the world** (en.) Viele CKAN-Portale sind hier gelistet [https://ckan.org/about/instances/](https://ckan.org/showcase)
* **Websites using CKAN** (en.) automatisch erstellte Liste mit über 1200 CKAN-Portalen https://trends.builtwith.com/websitelist/CKAN

## Große CKAN Open Data Portale weltweit

* **Britisches Open Data Portal** (en.) data.gov.uk | Find open data  https://data.gov.uk/
* **U.S. Government’s open data** (en.) Über 200.000 Datensätze der US-Regierung https://github.com/ckan/ckanext-harvest
* **Europe’s Earth Observation Data Hub (NextGEOSS)** Earth observation datasets https://catalogue-9.nextgeoss.eu/

## Deutsche CKAN Open Data Portale

* **Offene Daten Portal Stadt Frankfurt am Main** Leichte, schriftbetonte Oberfläche, integriert in städtische Corporate Design https://offenedaten.frankfurt.de
* **Open Data Portal Metropole Ruhr** Aufgeräumtes, übersichtliches Template, viel Inhalt https://opendata.ruhr
* **Open Data Portal Aachen** Hübsch aufbereitet https://offenedaten.aachen.de/
* **Offene Daten der Stadt Leipzig** mit vielen Bildern aus dem Stadtarchiv https://opendata.leipzig.de/

Weitere Open Data Portale gibt es als Open Data [hier](https://opendata.ruhr/dataset/ubersicht-der-open-data-angebote-in-deutschland/resource/2a8fafd0-b87f-4342-82b6-6e56569d673d)

## Empfehlenswerte CKAN Extensions

* **ckanext-pages** (en.) Kleines CMS für CKAN mit Seiten und Beiträgen https://github.com/ckan/ckanext-pages
* **datastore** (en.) Ermöglicht die Speicherung von tabellarischen Daten in der CKAN-Datenbank PostgreSQL https://docs.ckan.org/en/2.9/maintaining/datastore.html
* **recline_view / Data Explorer** (en.) Universelle Anzeige von strukturierten Inhalten, optimiert für den CKAN DataStore  https://docs.ckan.org/en/2.9/maintaining/data-viewer.html#data-explorer
* **recline_grid_view / DataStore Grid** (en.) Universelle Anzeige von strukturierten Inhalten, nur für den CKAN DataStore https://docs.ckan.org/en/2.9/maintaining/data-viewer.html#datastore-grid
* **recline_map_view / DataStore Map** (en.) Anzeige von Daten aus dem DataStore mit GeoJson (Lat/Lon) Feldern https://docs.ckan.org/en/2.9/maintaining/data-viewer.html#datastore-map
* **ckanext-dcat** (en.) Fügt RDF-Informationenzu den Datensätzen hinzu, die beim Harvesten Metadaten zur Verfügung gestellt und konsumiert werden können. DCAT = Data Catalog Vocabulary: https://github.com/ckan/ckanext-dcat In Deutschland am besten eingesetzt mit [**ckanext-dcatde**](https://github.com/GovDataOfficial/ckanext-dcatde)
* **ckanext-similar-datasets** Darstellung ähnlicher Datensaätze https://github.com/ondics/ckanext-similar-datasets

## Nutzung von CKAN in eigenen Anwendungen / Apps / Applikationen

* **opendata.swiss API nutzen** Wie programmiere ich den Zugriff auf die Daten von opendata.swiss? https://handbook.opendata.swiss/de/content/nutzen/api-nutzen.html
* **CKAN Downloader for Amsterdam Data** (en.) Nutzung von CKAN Datensätzen in Jupyter Notebooks https://github.com/KRontheWeb/ckan-downloader
* **Verwendung der API bei der SBB** Wie kann man die API als Anwender nutzen? Informationen der Open-Data-Plattform Mobilität Schweiz https://opentransportdata.swiss/de/cookbook/verwendung-des-ckan-api/
* **jupyter-ckan** (en.) Beispiele für CKAN in Jupyter / sandbox for jupyter notebooks that interact with CKAN https://github.com/CINERGI/jupyter-ckan
* **ckan.js** (en.) CKAN in eigenes JavaScript einbinden https://github.com/okfn/ckan.js
* **ckan-api-client 0.1-beta5** (en.) CKAN Python Client zur CKAN API. Nutzung der CKAN API in einem Python-Programm https://pypi.org/project/ckan-api-client/

## CKAN API

* **CKAN’s Action API** (en.) API Kurzbeschreibung https://ckan.org/portfolio/api/
* **API guide** (en.) API Dokumentation https://docs.ckan.org/en/2.9/api/index.html
* **ckanapi** (en.) Python-API und erweiterte CKAN-CLI https://github.com/ckan/ckanapi


## CKAN Handbuch / Anleitungen 

* **Das Berliner Open-Data-Handbuch** https://daten.berlin.de/sites/default/files/berliner-open-data-handbuch.pdf
* **handbook.opendata.swiss** Open Government Data Handbuch Schweiz https://handbook.opendata.swiss/de/index.html
* **CKAN Handbuch (en.) für Version 2.9** https://docs.ckan.org/en/2.9/contents.html
* **Data Catalog Vocabulary (DCAT) - Version 2** (en.) DCAT Spezifikation https://www.w3.org/TR/vocab-dcat/
* **DCAT-AP** Metadatenmodell zum Austausch von offenen Verwaltungsdaten https://www.dcat-ap.de/

## DCAT-AP.de

Der deutsche Metadatenstandard wird benötigt, um GovData-Harvesting zu ermöglichen. DCAT-AP.de hilft, Metadaten über Open Data Portal hinweg in gleicher Weise zu verwenden. 

Hier ein paar Tools und Hinweise mit Bezug zu DCAT-AP.de:

* Einführender Artikel zu DCAT-AP und DCAT-AP.de: https://ckan.de/was-ist-eigentlich-dcat-ap/
* kurzes Erklärvideo: https://youtu.be/DGCay_bbvDc
* CKAN-Extension für die DCAT-AP Basis: https://github.com/ckan/ckanext-dcat
* CKAN-Extension für die deutsche Erweiterung zu DCAT-AP: https://github.com/GovDataOfficial/ckanext-dcatde
* Konventionen-Handbuch für DCAT-AP.de: Wie sind die Metadaten definiert? https://www.dcat-ap.de/def/dcatde/2.0/implRules/
* Validator zur Prüfung von Open Data Portalen und Datensätzen auf DCAT-AP.de Konformität: https://www.itb.ec.europa.eu/shacl/dcat-ap.de/upload

# Verbesserungen

Jeder qualifizierte Beitrag ist willkommen. Vorgehensweise:

* Gitub-Fork erstellen
* Ergänzungen durchführen
* Pull Request stellen
* Warten, bis er akzeptiert wird
* Fertig

Wir freuen uns auf viele Änderungen.

# Autor

https://ckan.de

(C) 2021 | [Ondics GmbH](https://ondics.de)
