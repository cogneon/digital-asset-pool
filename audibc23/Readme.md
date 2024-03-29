 Hybrides Setup für das 8. Zusammenarbeit 2.0 Barcamp bei Audi.

# Räume
## Bühne
Setup mit zwei Kameras und drei (max. 4) Mikrofonen. Auf dem StreamingPC wird [Microsoft Teams](https://wiki.cogneon.de/Microsoft_Teams) für die Videokonferenz eingesetzt. Der Audiomixer2 ist in Teams Mikrofon und Lautsprecher, das VideoUSBInterface die Webcam.

```mermaid
graph LR;
    Cam1-->|SDI|Videomixer;
    Cam2-->|HDMI|Videomixer;
    Mic1-->|XLR|Audiomixer1;
    Mic2-->|XLR|Audiomixer1;
    Mic3-->|XLR|Audiomixer1;
    Mic4-->|XLR|Audiomixer1;
    MusicPlayer-->|Klinke|Audiomixer1;
    Videomixer-->|SDI|VideoUSBInterface;
    VideoUSBInterface-->|USB-A|StreamingPC;
    Audiomixer1-->|???|Audiomixer2
    Audiomixer2-->|USB-A|StreamingPC;
    Audiomixer2-->|Klinke6.3|PA;
    StreamingPC-->|WiFi|Internet;
```

**Equipment:**

1. Cam1: [Canon XA25](https://wiki.cogneon.de/Canon_XA25) (Close Up)
1. Cam2: GoPro 4 (Totale Publikum)
1. Mic1-4: [Sennheiser XSW](https://wiki.cogneon.de/Sennheiser_XSW)
1. Audiomixer1: Behringer RX1202FX
1. Audiomixer2: [Yamaha AG06](https://wiki.cogneon.de/Yamaha_AG_Serie)
1. Videomixer: Blackmagic Television Studio
1. VideoUSBInterface: [Blackmagic Web Presenter](https://wiki.cogneon.de/Blackmagic_Web_Presenter)
1. StreamingPC: offen
1. PA: offen

## Breakout-Räume
4x [Hybrid Meeting Kit](https://wiki.cogneon.de/hmk) inkl. NUCs

# Rollen
- VideoGuide
- AudioGuide
- KameraGuide
- GimbleGuide
- RoomBuddy (4x)
- Infodesk (1-3)