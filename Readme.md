# How to Run
1. Raspberry Pi Pico und Micro-USB zu USB - Kabel kaufen. ([Kabel](https://www.amazon.de/SIZUKA-Ladekabel-Schnellladekabel-Android-Motorola/dp/B0B998S4C6/ref=sr_1_8?__mk_de_DE=%C3%85M%C3%85%C5%BD%C3%95%C3%91&keywords=Micro+-+USB+zu+USB+-+Kabel&qid=1671524476&s=computers&sr=1-8), [Raspberry Pi](https://www.raspberrypi.com/products/raspberry-pi-pico/))
2. .uf2 Datei [herunterladen](https://circuitpython.org/board/raspberry_pi_pico/)
3. Repo clonen
4. .uf2 Datei in den Pico ziehen.
5. Alles, am Pico löschen und alles aus dem "pico" - Ordner kopieren und in den Pico ziehen.
6. Ducky Script schreiben und als "payload.dd" statt der alten "payload.dd" am Pico speichern.

## Skript
Das Ducky Script am Repo extrahiert alle WLAN Passwörter und SSID's vom Opfer-PC und schickt sie an die angegebene Outlook E-Mail Adresse. Dazu in die "payload.dd" Datei gehen und die Felder "yourMail@outlook.com" und "your Password" zur eigenen Outlook-Email und Password austauschen. 

Ducky sollte nun funktionsfähig sein => einfach in einem Computer stecken und warten.

### Rechtliches
Dieses Repo dient ausschließlich Bildungszwecken, wir übernehmen keine Verantwortung
für missbräuchliche Verwendung der Ressource.
