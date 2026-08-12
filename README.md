# Harry Potter Kosmos — Upload-Assets

Öffentliche Ablage für den automatisierten YouTube-Upload des Kanals
[@harrypotterkosmos](https://www.youtube.com/@harrypotterkosmos) über Upload-Post.

Das Repo ist öffentlich, weil YouTube die Thumbnails und Untertitel über eine
frei erreichbare URL abholen muss. Es enthält keine Videodateien im Verzeichnis —
die liegen als Release-Assets, weil normale Repo-Dateien bei 100 MB enden.

## Aufbau

```
thumbnails/   HP01_thumbnail.jpg … HP08_thumbnail.jpg   1280x720 JPG
untertitel/   HP01.de.srt … HP08.de.srt                 deutsch
```

## Zuordnung

| ID | Folge | Laufzeit |
|----|-------|----------|
| HP01 | Nach den Heiligtümern | 32:07 |
| HP02 | Das mächtigste Tierwesen | 25:15 |
| HP03 | Voldemort gegen Grindelwald | 29:13 |
| HP04 | Das Gold der Potters | 25:26 |
| HP05 | Die elf Zauberschulen | 19:45 |
| HP06 | Der Erste Zaubererkrieg | 19:44 |
| HP07 | Slytherin Top 5 | 16:57 |
| HP08 | HBO-Serie: Das Zeitproblem | 17:22 |

## Verwendung

Rohdatei-URL nach dem Schema

```
https://raw.githubusercontent.com/evoldotv-ops/hp-kosmos-assets/main/thumbnails/HP01_thumbnail.jpg
```

Diese URL geht als `youtubeThumbnailUrl` an Upload-Post, die SRT-URL als
`youtubeSubtitles`. Videos kommen als Release-Asset dazu und werden über
`browser_download_url` referenziert.

## Rechte

Die Thumbnail-Motive sind eigene Bildgenerierungen für den Kanal. Die Ablage
dient ausschließlich dem Upload der eigenen Videos, nicht der Weiterverbreitung.
