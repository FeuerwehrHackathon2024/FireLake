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

- [Lightning Apps](https://www.lightningmaps.org/blitzortung/europe/index.php?bo_page=archive&bo_show=maps&bo_map=de2&lang=de&bo_year=2023&bo_month=08&bo_day=24&bo_hour_from=0&bo_hour_range=24&bo_animation=1#bo_arch_strikes_maps_form)

# Grafische Darstellung
![Grafik](images/Firelake.png)

## Szenarios
- [BMA](https://github.com/FeuerwehrHackathon2024/FireLake/blob/main/Szenario-BMA.md)   

## Eingabe
- [Blitzortung](input_Blitzortung.md)
- [Car2X](input_car2x.md)
- [Einsatzberichte](input_einsatzberichte.md)
