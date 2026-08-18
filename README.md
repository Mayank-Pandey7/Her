# Her — Love Flower Gift Page

A romantic virtual gift page deployed at love-flower.pages.dev.

## Structure

```
index.html              — Main HTML
css2.css                — Google Fonts @font-face declarations (Caveat, Dancing Script)
restriction.js          — DevTools restriction script
assets/
  app.css               — All styles
  app.js                — All logic (flower bloom, passkey, photo grid, letter)
  giftbox.png           — Gift box image (landing page)
  music.mp3             — Background music
  flowers/
    flower-1.png        — Flower variant 1
    flower-2.png        — Flower variant 2
    flower-3.png        — Flower variant 3
  photos/
    rose.png            — Rose decoration (page 2 top-left)
    centre.png          — Centre couple image (page 2 hero)
    locked.png          — Lock icon
    image1.jpg          — Photo 1  (add your own photos)
    image2.jpg          — Photo 2
    ...
    image10.jpg         — Photo 10
```

## Passkey
Default passkey is `3128`. Change it in `assets/app.js` — search for `PASSCODE`.

## Customisation
- **Letter text** — edit `LETTER_TEXT` in `assets/app.js`
- **Photos** — replace `assets/photos/image1.jpg` … `image10.jpg` with your own
- **Caption / sub text** — edit directly in `index.html`
- **Music** — replace `assets/music.mp3`

## Deployment
Push to a Cloudflare Pages project (or any static host).
