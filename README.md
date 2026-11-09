# Rehearsal Book

A phone-first song book for choir rehearsal. Open `index.html` in a browser, or host the folder (GitHub Pages works) and add it to your home screen.

- **Lyrics and music notes** are kept separately for each song, with the hymn number.
- **Key** is saved per song with your own note. The **Keyboard** tab shows the key on a piano, labels the notes in sol-fa (d r m f s l t) and plays the key note, chord and scale.
- **Recordings**: record inside the app or pick a file, then tap **Mark** as each lyric line starts. The lines light up as the recording plays, and tapping a line jumps to it.
- **Rehearse mode**: full-screen lyrics, text size, optional music notes, auto-scroll, and a recording to follow.
- **Notes** per song, with a tick when done.

Everything is saved in the browser on the phone (songs in local storage, recordings in IndexedDB), so it works offline once opened. Clearing browser data removes it.

No build step. Files: `index.html` (the app), `sw.js` (offline), `manifest.webmanifest` and icons (install to home screen).
