# Gorilla Fangen

Ein Gorilla-Tag-ähnliches Fangspiel für Handy und PC, komplett in einer Datei (`index.html`).

## Steuerung
- **Links:** Joystick zum Laufen
- **Rechts:** Wischen zum Umsehen, Knopf **SPRING** zum Springen
- **Gegen einen Baum laufen:** Du kletterst automatisch schnell hoch
- **PC auf dem Baumstumpf:** Name ändern, Fellfarbe (R/G/B 0–9), Raum beitreten/erstellen, Freunde hinzufügen, Bots an/aus
- Am Computer: WASD + Maus ziehen, Leertaste springen, E = PC, V = Ansicht

Wer orange ist, ist die **Lava**. Wen sie berührt, wird auch Lava. Sind alle gefangen, startet eine neue Runde.

## Online mit Freunden
Räume laufen über PeerJS (WebRTC). Dafür muss das Spiel von einer echten Webseite geladen werden, z. B. GitHub Pages:
Repository → Settings → Pages → Branch auswählen → Save. Danach ist das Spiel unter
`https://<name>.github.io/<repo>/` erreichbar.

Freunde fügst du mit ihrer 6-stelligen Freundes-ID hinzu (steht im PC unter FREUNDE).
