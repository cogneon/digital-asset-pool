Hybrides Setup für das 8. Zusammenarbeit 2.0 Barcamp bei Audi.

# Bühne
Setup mit zwei Kameras und drei (max. 4) Mikrofonen.

```mermaid
graph LR;
    Cam1-->|SDI|Videomixer;
    Cam2-->|HDMI|Videomixer;
    Mic1-->|XLR|Audiomixer1;
    Mic2-->|XLR|Audiomixer1;
    Mic3-->|XLR|Audiomixer1;
    Mic4-->|XLR|Audiomixer1;
    Videomixer-->|SDI|VideoUSBInterface;
    VideoUSBInterface-->|USB-A|StreamingPC;
    Audiomixer1-->|???|Audiomixer2
    Audiomixer2-->|USB-A|StreamingPC;
    Audiomixer2-->|Klinke6.3|PA;
    StreamingPC-->|WiFi|Internet;
```

# Breakout-Räume
[Hybrid Meeting Kits](https://wiki.cogneon.de/hmk) inkl. NUCs