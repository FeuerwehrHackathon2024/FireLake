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


# Grafische Darstellung
![Grafik](https://raw.githubusercontent.com/FeuerwehrHackathon2024/FireLake/main/Firelake.png)
