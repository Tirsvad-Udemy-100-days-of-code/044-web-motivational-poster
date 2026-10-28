# 044-web-motivational-poster

A motivational poster web page built with plain HTML and CSS. It is the final
project of the HTML/CSS section (6.4) of the Udemy course *100 Days of Code*.

![Motivational poster](screenshots/desktop.png)

## Features

- Black background, white text, everything centred.
- Title in the *Libre Baskerville* Google Font, made uppercase with
  `text-transform`.
- Image with a 5px white border that fills its container (`width: 100%`).
- One `div.poster` holds the image, `h1` and `p`; it is centred with
  `width: 50%` and `margin-left: 25%`.
- A small media query widens the poster on narrow screens.

## Run it

No build step. Open `index.html` in a browser (the font is loaded from Google
Fonts, so an internet connection is needed to see it).

## Project layout

```text
index.html            the page
style.css             the styles
assets/images/        the poster image
screenshots/          screenshots used in this README
docs/wiki/           documentation in English, Dansk and Bahasa Malaysia
```

## Wiki

| Language | Start page |
| --- | --- |
| English | [docs/wiki/en/Home.md](docs/wiki/en/Home.md) |
| Dansk | [docs/wiki/da/Home.md](docs/wiki/da/Home.md) |
| Bahasa Malaysia | [docs/wiki/ms/Home.md](docs/wiki/ms/Home.md) |

## Make your own poster

Change the image in `assets/images/`, then edit the `h1` and `p` text in
`index.html`.

## License

See [LICENSE](LICENSE).
