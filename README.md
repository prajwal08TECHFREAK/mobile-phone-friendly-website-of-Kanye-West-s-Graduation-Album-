# Graduation '07

Fan-made tribute site for Kanye West's 2007 album *Graduation*. A single-page
experience with pop-art visuals, heavy motion, and background music that starts
with the page.

## Features

- Intro loader held until the music is actually rolling
- Custom bear-face cursor on desktop
- Two-line hero title with floating stickers, parallax, and scroll-driven reveals
- Album section with animated stats and a flip card
- Artwork gallery with lightbox popups
- Full 13-track tracklist, each track with its own popup and a Spotify link
- Draggable poster wall, posters open in popups
- Footer marquee and a small easter egg
- Background music streams the official *Flashing Lights* upload on YouTube
  (audio only, hidden player) and fades in from 60% volume over the first 5 seconds
- Responsive for phones: swipe-safe scrolling, on-screen popups that fit the
  screen, touch anywhere to start the sound

## Structure

```
index.html    markup and all scripts
style.css     all styles
images/       source images
```

No build step, no dependencies. Plain HTML, CSS, and vanilla JS.

## Run

Open `index.html` directly, or serve the folder:

```sh
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

**GitHub Pages:** push the repo and enable Pages on the root. Nothing else to
configure.

## Notes

- Background music needs an internet connection (YouTube embed). On phones the
  browser starts it muted; any tap, swipe, or key press turns the sound on.
- All copy on the site is original writing. No lyrics appear anywhere.
- Album artwork and poster imagery belong to their respective rights holders
  and are used here only for a non-commercial fan project.

## Credits

- *Graduation* (2007), Kanye West
- Art direction inspired by Takashi Murakami's superflat style and the album's
  Dropout Bear imagery

Unofficial fan project. Not affiliated with the artist, the label, or any
rights holders.
