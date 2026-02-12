# Rai Valentine — Interactive offline Valentine page

This small page asks "Will you be my Valentine?" with two options: **Yes** and **No**. The **No** button playfully dodges clicks; **Yes** reveals a cute cat and plays a short bundled song or your provided `shaky.mp3`.

Files in this folder:

- `index.html` — main page (includes inline SVG cat so it works offline)
- `style.css` — styles and small animations
- `script.js` — runaway No behavior and bundled synth song
- `shaky.mp3` — (optional) your provided real audio file
 - `dudu.gif` — (optional) your provided Dudu GIF; place it next to `index.html` and it will be shown when the user clicks Yes

Usage:

1. Open `index.html` in your browser (double-click or open via File → Open).
2. If `shaky.mp3` is present in this folder it will be used; otherwise the page plays a short synthesized melody.
3. If `dudu.gif` is present it will be shown on Yes; the page now shows only the GIF and the message "thank you jaanu". The previous SVG fallback has been removed.

Notes:

- Modern browsers may require a user gesture to start audio; clicking **Yes** acts as that gesture.
