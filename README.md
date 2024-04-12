# stlink4dummies


1) Programme runterladen und installieren: [ReFlasher](https://www.scooterhacking.org/forum/viewtopic.php?f=14&t=676) und [Zadig](https://zadig.akeo.ie/)
2) ST-Link ohne irgendwas angeschlossenes an den Pins an den PC stecken
3) Zadig öffnen, sicherstellen dass oben der ST-Link ausgewählt ist, dort wo "WinUSB" steht mit den pfeilsysmbolen "libusb-win32" (o. ä.) auswählen, Install/Replace Driver drücken
4) Sobald fertig, Zadig schließen, reflasher öffnen
5) In Reflasher unter Diagrams das Bild von deinem Controller öffnen
6) ST-Link abstecken, Kabel wie dargstellt verbinden. **Der Controller muss ganz ausgebaut sein**. ST-Link einflashen.
7) Scooter auswählen. Unter Periphal bei Xiaomi: BLE und bei Ninebot: DRV auswählen.
8) Serial Number eintragen, diese findet sich in SHU/auf dem Scooter. Kann aber auch nachträglich geändert werden über SHU.
9) Wenn zutreffend AT32 anklicken.
10) Launch Recovery klicken.
