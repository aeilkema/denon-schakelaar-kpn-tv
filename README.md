# Denon Schakelaar

**Nederlandse versie** | [English](README.en.md)

## Nederlands

Denon Schakelaar is een Android TV-app om een Denon AVR-X2400H vanuit de KPN TV+ Box te bedienen. De app zoekt de receiver op het lokale netwerk en biedt knoppen om de receiver in te schakelen en een HDMI-ingang te kiezen.

In Instellingen kun je apparaatnamen, HDMI-nummers, pictogrammen en de volgorde aanpassen. Je kunt ingangen ook verbergen op het startscherm. De interface is ontworpen voor gebruik met een afstandsbediening en heeft een donkere weergave.

### Installatie

Download de [laatste release](https://github.com/aeilkema/denon-schakelaar-kpn-tv/releases/latest/download/DenonSchakelaar.apk) en installeer de APK op een Android TV-apparaat. Voor deze app is sideloaden nodig; hij staat niet in de Play Store. De receiver en Android TV moeten op hetzelfde lokale netwerk zitten.

### Werking en beperkingen

- Receiver zoeken gebeurt via SSDP op het lokale netwerk.
- Inschakelen en ingangskeuze gebruiken Denon Telnet-commando’s op poort 23.
- HDMI-nummers zijn vooraf ingevuld volgens de standaardindeling van de AVR-X2400H. Pas ze aan als de receiver anders is ingesteld.
- De app vraagt bij verbinding de bronnamen op via de Denon-interface en werkt ze bij als de receiver ze beschikbaar stelt. Als de receiver geen namen terugstuurt, gebruikt de app de ingestelde labels. HDMI-toewijzingen worden niet automatisch uitgelezen; die stel je zelf in.
- Het inschakelen van een aangesloten apparaat hangt af van HDMI-CEC en de instellingen van dat apparaat. Voor sommige apparaten, waaronder een Nintendo Switch, is handmatig ontwaken nodig.
- De app is gemaakt voor de Denon AVR-X2400H. Andere Denon- en Marantz-modellen zijn niet getest.

### Persoonlijk gebruik

Dit project is gepubliceerd voor persoonlijk gebruik. Er wordt geen ondersteuning of garantie geboden. Er wordt geen licentie verleend voor hergebruik, verspreiding of commerciële toepassing zonder toestemming van de auteur.

## English

Denon Schakelaar is an Android TV app for controlling a Denon AVR-X2400H from a KPN TV+ Box. It discovers the receiver on the local network and provides controls to power it on and select an HDMI input.

Settings let you change device names, HDMI numbers, icons and input order. Inputs can be hidden from the home screen. The interface is designed for remote control navigation and uses a dark theme.

### Installation

Download the [latest release](https://github.com/aeilkema/denon-schakelaar-kpn-tv/releases/latest/download/DenonSchakelaar.apk) and install the APK on an Android TV device. Sideloading is required; the app is not available from the Play Store. The receiver and Android TV device must be on the same local network.

### Operation and limitations

- Receiver discovery uses SSDP on the local network.
- Power and input selection use Denon Telnet commands on port 23.
- HDMI numbers start with the AVR-X2400H factory assignments. Change them if your receiver uses a different configuration.
- On connection, the app requests source names from the Denon interface and updates them when the receiver provides them. If the receiver returns no names, the app uses its configured labels. HDMI assignments are not read automatically and must be set in the app.
- Waking a connected device depends on HDMI-CEC and that device’s settings. Some devices, including the Nintendo Switch, may need to be woken manually.
- The app was made for the Denon AVR-X2400H. Other Denon and Marantz models have not been tested.

### Personal use

This project is published for personal use. No support or warranty is provided. No license is granted for reuse, redistribution or commercial use without the author’s permission.
