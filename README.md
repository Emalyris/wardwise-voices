# WardWise note voices

Recorded voices of WardWise notes, played by the "Listen to this note" player on wardwiseug.com.
Served by GitHub Pages: https://emalyris.github.io/wardwise-voices/index.json

- `index.json`: every recorded note, by `COURSE|topickey` (for example `CN211|pneumonia`), with its sound file and timings.
- `<course>/<topic>-<hash>.mp3`: the note read top to bottom (Kokoro voice, 32 kbit/s mono).
- `<course>/<topic>-<hash>.json`: when each block of the note starts, so the page can light it up.

Do not edit by hand. These files are made by the private repo `Emalyris/wardwise-explainers` (`voices/`, workflow "Record note voices").
Voice: Kokoro-82M (Apache 2.0), run with kokoro-onnx (MIT).
