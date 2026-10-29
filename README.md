# This Is Not a Birthday Party

**Ceci n'est pas une fête d'anniversaire** is a vibecoded, immersive web experience made for my birthday dinner. Guests are invited into Château Beckers, a strange old house where an ordinary-sounding evening of food and drinks slowly becomes something less ordinary.

The characters are fictionalized portraits of my friends, created for the occasion. The site gives them a shared world through a moody introduction, character portraits, a house history, video performances, and hidden clues to uncover. It is part interactive story, part dinner-party atmosphere, and very much a personal project made for one memorable night.

## Explore

- **Prelude** (`index.html`): the invitation into Château Beckers
- **The Salon** (`intro.html`): meet the house's guests
- **The Story** (`verhaal.html`): discover the history the house chooses to tell
- **The Hint Room** (`hintkamer.html`): solve three small puzzles to reveal clues
- **Trailer and portraits** (`trailer.html`, `video.html`): watch the house and its characters come to life

The experience is in Dutch. It is built with plain HTML, CSS, and JavaScript, with its audio, portraits, and videos kept in the repository. There is no build step or package install.

## Run locally

Open `index.html` in a browser, or serve the project folder locally:

```sh
python3 -m http.server 8000
```

Then visit <http://localhost:8000>.
