Dieser Ordner enthält Ressourcen für das [GfWM KnowledgeCamp 2022](https://gfwm.de/gkc22) (#gkc22) in Berlin und online.

- **Wann:** 13.-14.10.2022

- **Wo:** [The Student Hotel]([Berlin Mitte](https://www.thestudenthotel.com/de/berlin-mitte/)), Berlin & Online (Hybrid)

# Technik Session-Räume

Dokumentation folgt.

# Technik Bühne

```mermaid
graph LR;
      Camcorder-->VideoMixer;
      WeitwinkelKamera-->VideoMixer;
      VideoMixer-->DockingStation;
      DockingStation-->PC;
      AudioMixer-->Lautsprecher;
      AudioMixer-->DockingStation;
      AudioMixer-->Kontrollkopfhörer;
      Funkmikrofon1-->Empfänger;
      Funkmikrofon2-->Empfänger;
      Empfänger-->AudioMixer;
      LAN-->DockingStation;
      StreamDeck-->DockingStation;
      DockingStation-->Display;
```

**Materialliste** (s.a. [COPEDIA Seite](https://wiki.cogneon.de/Multimedia_Schrank)):

- **PC:** Lenovo X1 Carbon (von Simon)

- **Docking Station:** Hyper Drive Gen2

- **Camcorder:** Canon XA25 (auf Stativ, Totale Bühne)

- **Weitwinkel-Kamera:** GoPro (auf Stativ, Totale Publikum)

- **VideoMixer:** Blackmagic ATEM Mini Pro (Pausenbild über ATEM, OBS aktuell nicht geplant)

- **Funkmikros/Empfänger:** Sennheiser XS Wireless 1

- **AudioMixer:** Zoom PodTrack P4 (USB MixMinus konfiguriert, Kanal 1: Funkmikro 1, Kanal 2: Funkmikro 2, Kanal 3: Reserve, Kanal 4: PC)

- **Lautsprecher:** von Location(in Klärung, Ausgang AudioMixer: 3,5mm Klinke)

- **Display:** von Location(in Klärung)