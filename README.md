# Techjays video assets

Brand files used by the `techjays-usecase-video` Claude skill. The skill downloads them straight from this repository, so it works in any Claude account without a Google Drive connection.

| File | What it is |
|---|---|
| `intro.mp4` | Techjays intro, 2.0s, 1920×1080 |
| `outro.mp4` | Techjays outro, 6.48s, 1920×1080 |
| `logo_icon.png` | Black Techjays mark, transparent PNG (bottom-right watermark) |
| `music/*.mp3` | Approved background music tracks |
| `music/tracks.txt` | List of the music files, one per line. The skill picks a track at random from this list. |

**Adding a music track:** upload the `.mp3` into `music/` and add its file name as a new line in `music/tracks.txt`.

Keep the file names above unchanged, because the skill looks for them by name.
