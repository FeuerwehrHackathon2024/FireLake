# Was ist das?
Eine Standartisierte Eingangs- und Ausgangsschnittstelle für den Feuerwehrdienst.
Datenmüllhalde :>


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

[https://www.lightningmaps.org/blitzortung/europe/index.php?bo_page=archive&bo_show=maps&bo_map=de2&lang=de&bo_year=2023&bo_month=08&bo_day=24&bo_hour_from=12&bo_hour_range=2&bo_animation=1#bo_arch_strikes_maps_form](https://www.lightningmaps.org/blitzortung/europe/index.php?bo_page=archive&bo_show=maps&bo_map=de2&lang=de&bo_year=2023&bo_month=08&bo_day=24&bo_hour_from=0&bo_hour_range=24&bo_animation=1#bo_arch_strikes_maps_form)

# Grafische Darstellung
![Grafik](https://raw.githubusercontent.com/FeuerwehrHackathon2024/FireLake/main/Firelake.png)

# Anwendungsfall Fahrzeugdaten
![Fahrzeug Grafik](https://teltonika-gps.com/cdn/use-cases/2023/01/63d91a6cbc4dc4-83625632/487898-wildfire-emergency-vehicle-gps-tracker-fmc225-v12-final.svg)
