Dieser Ordner enthält die Ressourcen für die **lernOS Convention 2020** (loscon22). Alle Infos zur Veranstaltung unter https://cogneon.de/loscon22. Das Leitthema der Veranstaltung ist **"The Re-Return of Knowledge Management"**. Das visuelle Design ist in Anlehnung an den Film [Die Rückkehr der Jedi-Ritter](https://de.wikipedia.org/wiki/Die_R%C3%BCckkehr_der_Jedi-Ritter) an die Star Wars Filmreihe angelehnt. Der Font ist [Star Jedi Hollow]([https://www.dafont.com/star-jedi.font).

# Logo

![](./loscon22-logo.png)

# Key Visual

![](./loscon22-key-visual.png)

# Hintergründe
Hintergrundgrafiken z.B. für Microsoft Teams im Format 16:9 (1280x720px)
![](./loscon22-hintergrund-schwarz.png)
![](./loscon22-hintergrund-yoda.png)
![](./loscon22-hintergrund-darth-yoda.png)
![](./loscon22-hintergrund-sturmtruppler.png)

# Sticker

Druck erfolgt als gestanzte Sticker über [Stickermule](https://www.stickermule.com/) (300 Stück).

![](./loscon22-sticker.png)

# Technik Bühne
```mermaid
  graph TD;
      PresenterPC-->|HDMI|HDMISplitter;
      HDMISplitter-->Beamer;
      HDMISplitter-->VideoMixer;
      Funkmikrofon1-->AudioMixer;
      Funkmikrofon2-->AudioMixer;
      Funkmikrofon3-->AudioMixer;
      Headset1-->|XLR|AudioMixer;
      Headset2-->|XLR|AudioMixer;
      Musikquelle-->|Klinke|AudioMixer;
      Kamera1-->|HDMI|VideoMixer;
      RolleKameraEngel-->Kamera1;
      Kamera2-->|HDMI|VideoMixer;
      VideoMixer-->|USB|StreamingPC;
      AudioMixer-->|USB|StreamingPC;
      StreamingPC-->Streamyard;
      Streamyard-->|RTMP|Youtube;
      Youtube-->StreamKontrollPC;
      RolleVideoregie-->StreamingPC;
      RolleStreamKontrolle-->StreamKontrollPC;
```

Planungsstand Equipment:

* PresenterPC: Lenovo X1 Carbon (Simon)?
* StreamingPC: Lenovo X1 Carbon (Simon) oder NUC?
* HDMISplitter:
* HDMIUSBConverter: Elgato Cam Link
* Funkmikrofon 1/2/3: Sennheiser Handmikrofone
* Headset 1/2: Beyerdynamic DT297
* Musikquelle: iPad (Simon)
* Kamera 1: Canon XA25 auf Stativ mit Fernsteuerung
* Kamera 2: Panasonic HC X929
* VideoMixer: ATEM Mini
* AudioMixer: Zoom L12

Offen: der Beamer muss vom Presenter PC (Folien), aber auch aus der Videoregie (z.B. Teams) bespielt werden können (Bild und Ton). Ansatz: der Beamer im Plenum zeigt das gleiche Bild, wie ... der Stream?

# Technik Breakout Räume
Wir gehen davon aus, dass Session-Owner ihr eigenes **Notebook** mitbringen. Das Funkmikrofon 1 kann beim Session-Owner angeklipst werden, das Funkmikrofon 2 kann in einem Schaumstoffwürfel gesteckt und als Publikumsmikro verwendet werden. Alternativ liegt auch für Funkmikrofon 1 noch ein Schaumstoffwürfel bereit.

```mermaid
  graph TD;
      Webcam-->|USB|USBHub;
      Freisprecheinrichtung-->|USB|USBHub;
      Funkmikrofon1-->Funkempfänger;
      Funkmikrofon2-->Funkempfänger;
      Funkempfänger-->|USB|USBHub;
      Beamer-->|HDMI|Notebook;
      USBHub-->|USB-A|Notebook;
```
Planungsstand Equipment:
* Webcam: [OBSBOT Tiny 4K](https://www.obsbot.com/obsbot-tiny-4k)
* Freisprecheinrichtung [Jabra Speak 510](https://www.jabra.com.de/business/speakerphones/jabra-speak-series/jabra-speak-510##7510-209) und/oder [EPOS Expand 80](https://www.eposaudio.com/de/de/enterprise/products/expand-80-bluetooth-speakerphone-1000202)
* Funkmikrofon/-empfänger: [Rode Wireless Go II](https://de.rode.com/Wireless/Wirelessgo)
* USBHub:
* Notebook: von Session Owner mitgebracht, Mindestanforderung: HDMI (Typ A, Adapter müssen selber mitgebracht werden), 1x USB-A
