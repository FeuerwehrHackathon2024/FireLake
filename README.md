# Was ist das?
![Grafik](images/Firelake.svg)

„Fire Lake“ soll ein großer Feuerwehr-Speichersee werden, in den öffentliche und interne Informations- und Datenquellen einfließen können. Denn für fast alle informations- und datenbasierten Feuerwehr-IT-Projekte ist ein zentraler Datenspeicher eine wichtige Grundlage. 

Einsatzrelevante Echtzeitdaten zu Umwelt, Infrastruktur, sozialen Medien und IoT, Informationen aus Statistik- und GIS-Daten, Dienst- und Einsatzvorschriften, Einsatzkonzepten sowie Echtzeit-Diagnosedaten wichtiger Einsatzmittel („[predictive Maintenance](https://github.com/FeuerwehrHackathon2024/PredictiveMaintenance)“) sollen diesen Speichersee füllen.

In Echtzeit verarbeitet können die (frei-)verfügbaren Daten helfen „vor die Lage“ zu kommen, um Entscheidungen z.B. bei der Feuerwehralarmierung datenbasiert zu unterstützen oder in Zukunft auch ereignisbasiert eine Einsatzwahrscheinlichkeit zu ermitteln. Für das LLM einer Feuerwehr-KI kann der große Datensee die Grundlage bilden um hilfreiche Fakten zu extrahiert, Zusammenhänge festzustellen oder Risiken frühzeitiger zu erkennen.

Technische Grundlagen von FireLake soll ein OpenSource-Data Lake Framework wie z.B. Apache Hudi sein, das über 

## Informationsquellen
- Verkehrsdaten
    - [BayernInfo.de](https://bayernInfo.de/)
    - [VerkehrsInfo.de](https://verkehrsinfo.de/)
- Infrastruktur (z.B. Strom, Wasser, Internet)
    - [Störauskunft.de](https://störauskunft.de/)
- Wetter Daten
    - [lightningmaps.org](https://www.lightningmaps.org/) - ([Beispiel](https://www.lightningmaps.org/blitzortung/europe/index.php?bo_page=archive&bo_show=maps&bo_map=de2&lang=de&bo_year=2023&bo_month=08&bo_day=24&bo_hour_from=0&bo_hour_range=24&bo_animation=1#bo_arch_strikes_maps_form))
    - [dwd.api.bund.dev](dwd.api.bund.dev) --> inkl. Hochwasser und Überschwemmungen / Fließgeschwindigkeiten
- Geodaten
    - [Google Maps](https://www.google.com/maps/)
    - [Hausumringungen](https://geodaten.bayern.de/opengeodata/OpenDataDetail.html?pn=hausumringe)
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

## Szenarios
- [BMA](Szenario-BMA.md)   
- [Stromausfall](Szenario-Stromausfall.md)

## Eingabe
- [Blitzortung](input_Blitzortung.md)
- [Car2X](input_car2x.md)
- [Einsatzberichte](input_einsatzberichte.md)
