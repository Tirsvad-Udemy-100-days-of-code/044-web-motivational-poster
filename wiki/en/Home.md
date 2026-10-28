# Motivational Poster

**Languages:** English · [Dansk](../da/Home.md) · [Bahasa Malaysia](../ms/Home.md)

A motivational poster web page made with HTML and CSS only.

![Motivational poster](../../screenshots/desktop.png)

## Requirements

1. The `h1` uses the Libre Baskerville font from Google Fonts.
2. White text on a black background.
3. An image with a 5px white border.
4. Centred text.
5. A `div` holds the `h1`, `p` and `img`, and is centred on the page.
6. The `h1` is uppercase through CSS, not by retyping it.

## How it works

### HTML

```html
<div class="poster">
  <img class="motivation-img" src="./assets/images/daenerys.jpeg" alt="A woman holding a dragon egg">
  <h1>That Special Moment</h1>
  <p>When you find the perfect avocado at the supermarket</p>
</div>
```

Keeping the image and the text in one `div` means one rule can size, centre
and colour all of them.

### CSS

| Rule | What it does |
| --- | --- |
| `body { background-color: black; }` | Black page background. |
| `.poster { width: 50%; margin-left: 25%; }` | Half the page wide, with 25% free on each side, so it is centred horizontally. |
| `.poster { margin-top: 100px; }` | Space above the poster. |
| `.poster { color: white; text-align: center; }` | White, centred text. |
| `.poster { font-family: "Libre Baskerville", serif; }` | The Google Font, with a fallback. |
| `.motivation-img { width: 100%; border: 5px solid white; }` | The image fills the `div` and gets a white frame. |
| `h1 { text-transform: uppercase; }` | Uppercase title without retyping it. |

The Google Font is loaded with a `<link>` in the `<head>` of `index.html`.

## Make your own

1. Put your image in `assets/images/`.
2. Update `src` and `alt` on the `img`.
3. Change the text of the `h1` and `p`.
4. Experiment: fonts, colours, border width, spacing.

## Run it

Open `index.html` in a browser. An internet connection is needed to load the
font.
