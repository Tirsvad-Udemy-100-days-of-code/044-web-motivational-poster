# Motivationsplakat

[English](Home) · **Dansk** · [Bahasa Malaysia](Home-ms)

En motivationsplakat som webside, lavet kun med HTML og CSS.

![Motivationsplakat](https://git.tirsystem.com/Tirsvad-Udemy-100-days-of-code/044-web-motivational-poster/raw/branch/main/screenshots/desktop.png)

## Krav

1. `h1` bruger skrifttypen Libre Baskerville fra Google Fonts.
2. Hvid tekst på sort baggrund.
3. Et billede med en hvid kant på 5px.
4. Centreret tekst.
5. En `div` indeholder `h1`, `p` og `img` og er centreret på siden.
6. `h1` er med store bogstaver via CSS, ikke ved at skrive den om.

## Sådan virker det

### HTML

```html
<div class="poster">
  <img class="motivation-img" src="./assets/images/daenerys.jpeg" alt="A woman holding a dragon egg">
  <h1>That Special Moment</h1>
  <p>When you find the perfect avocado at the supermarket</p>
</div>
```

Når billede og tekst ligger i samme `div`, kan én regel bestemme størrelse,
placering og farve for dem alle.

### CSS

| Regel | Hvad den gør |
| --- | --- |
| `body { background-color: black; }` | Sort sidebaggrund. |
| `.poster { width: 50%; margin-left: 25%; }` | Halvdelen af sidens bredde med 25% fri på hver side, så plakaten er centreret vandret. |
| `.poster { margin-top: 100px; }` | Luft over plakaten. |
| `.poster { color: white; text-align: center; }` | Hvid, centreret tekst. |
| `.poster { font-family: "Libre Baskerville", serif; }` | Google-skrifttypen med en reserve. |
| `.motivation-img { width: 100%; border: 5px solid white; }` | Billedet fylder hele `div`'en og får en hvid ramme. |
| `h1 { text-transform: uppercase; }` | Store bogstaver uden at skrive titlen om. |

Google-skrifttypen hentes med et `<link>` i `<head>` i `src/index.html`.

## Lav din egen

1. Læg dit billede i `src/assets/images/`.
2. Ret `src` og `alt` på `img`.
3. Ret teksten i `h1` og `p`.
4. Eksperimenter: skrifttyper, farver, kantbredde, afstande.

## Kør den

Åbn `src/index.html` i en browser. Du skal have internetforbindelse for at hente
skrifttypen.
