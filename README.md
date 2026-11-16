# Drum Kit

A browser drum kit in vanilla JavaScript. Click a drum or press its key to play the sound, with a short press animation on the button.

**[▶ Play it live](https://shzunknown11.github.io/DrumKit/)**

## Keys

| Key | Sound |
|---|---|
| `W` `A` `S` `D` | Tom 1 – 4 |
| `J` | Snare |
| `K` | Crash |
| `L` | Kick bass |

## How it works

- One `click` listener per `.drum` button and one `keydown` listener on the document.
- Both call the same `makeSound(key)` function, which plays the matching file with the `Audio` API.
- No build step and no dependencies: `index.html`, `index.js`, `styles.css`.

## Run locally

Clone the repo and open `index.html` in a browser.

## What I practised

DOM events, keyboard handling, the HTML5 Audio API and reusing one handler for two input types.

---

Built by **[Shazan (Mohammad Taha)](https://github.com/SHZunknown11)**, full-stack developer and CSE student at Chandigarh University. More projects on the [portfolio](https://mohammad-taha-portfolio.pages.dev).
