# Was ist das?
„Fire Lake“ soll ein großer Feuerwehr-Speichersee werden, in den öffentliche und interne Informations- und Datenquellen einfließen können. Denn für fast alle informations- und datenbasierten Feuerwehr-IT-Projekte ist ein zentraler Datenspeicher eine wichtige Grundlage. 

Einsatzrelevante Echtzeitdaten zu Umwelt, Infrastruktur, sozialen Medien und IoT, Informationen aus Statistik- und GIS-Daten, Dienst- und Einsatzvorschriften, Einsatzkonzepten sowie Echtzeit-Diagnosedaten wichtiger Einsatzmittel („predective Maintenance“) sollen diesen Speichersee füllen.

In Echtzeit verarbeitet können die (frei-)verfügbaren Daten helfen „vor die Lage“ zu kommen, um Entscheidungen z.B. bei der Feuerwehralarmierung datenbasiert zu unterstützen oder in Zukunft auch ereignisbasiert eine Einsatzwahrscheinlichkeit zu ermitteln. Für das LLM einer Feuerwehr-KI kann der große Datensee die Grundlage bilden um hilfreiche Fakten zu extrahiert, Zusammenhänge festzustellen oder Risiken frühzeitiger zu erkennen.

Technische Grundlagen von FireLake soll ein OpenSource-Data Lake Framework wie z.B. Apache Hudi sein, das über 

## Informationsquellen
- BayernInfo.de || VerkehrsInfo.de
- Störauskunft
    - Strom
    - Wasser
    - Internet
- Google Maps
- lightningmaps.org
- dwd.api.bund.dev --> inkl. Hochwasser und Überschwemmungen / Fließgeschwindigkeiten
- Geodaten
    - Hausumringungen https://geodaten.bayern.de/opengeodata/OpenDataDetail.html?pn=hausumringe
- Interne BOS Datentöpfe inkl. Authorization:
    - Brandmeldeanlage (BMA)
    - Car2X / Car to Car 
    - AEPs
        - Anfahrtkarten - zur Überlagerung
    - Interne Kartenmaterialien (Überschwemmungsgebiete nach Statistiken)
    - Einwohnermeldeamt
    - Lokale Datentöpfe
        - Material Listen
        - Personal


## Mögliche App Schnitstellen
- api/get
    - available_vehicle

- api/set
    - vehicle_state

- [Lightning Apps](https://www.lightningmaps.org/blitzortung/europe/index.php?bo_page=archive&bo_show=maps&bo_map=de2&lang=de&bo_year=2023&bo_month=08&bo_day=24&bo_hour_from=0&bo_hour_range=24&bo_animation=1#bo_arch_strikes_maps_form)

# Grafische Darstellung
![Grafik](images/Firelake.png)

## Szenarios
- [BMA](Szenario-BMA.md)   
- [Stromausfall](Szenario-Stromausfall.md)

## Eingabe
- [Blitzortung](input_Blitzortung.md)
- [Car2X](input_car2x.md)
- [Einsatzberichte](input_einsatzberichte.md)
