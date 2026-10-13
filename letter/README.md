# A Letter, Just for You

A responsive, single-page romantic letter experience built with plain HTML, CSS, and JavaScript.

## Run it
1. Extract the ZIP.
2. Open `index.html` in a modern browser. For the best experience, use a small local web server (for example VS Code Live Server).
3. Add your music file at `assets/romantic-piano.mp3` (create the `assets` folder if needed). Use music you own or have permission to use.
4. Replace the sample photo URLs and messages in `LETTER_PAGES` near the bottom of `index.html`.

## Customize
Each page in `LETTER_PAGES` has:
- `image`: photo URL or relative local path such as `assets/photo-1.jpg`
- `alt`: accessible description
- `date`: optional small note/date
- `message`: message shown below the photo
- `durationMs`: time before moving to the next page, in milliseconds

The last page stays visible longer, then the closing message appears. Music remains playing after the ending until the visitor mutes it or leaves the page.

## Notes
- Browsers often block autoplay with sound. Playback is attempted when the envelope is clicked, which is the first user gesture.
- The sample audio file is intentionally not included. Add your own licensed audio file at `assets/romantic-piano.mp3`.
- Sample photographs are remote Unsplash URLs; replace them with personal photos for the real experience.
- Reduced-motion preferences are respected.
