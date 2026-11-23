# DNA

A static movie and TV show browsing site, built in 2023 as one of my first
web projects. It has a home page with sliders, a movies grid, a shows grid
and a detail page for each title with a synopsis, a video player and a
download button.

## Pages

| Page | What it shows |
| --- | --- |
| `index.html` | Home: banner slider, Must Watch Movies, Recommended Shows, Movie of the Week |
| `movies.html` | Grid of movie cards, each linking to its own page |
| `shows.html` | Grid of TV show cards |
| `<Title>.html` | One page per title: poster, synopsis and release details, player, download |
| `Suits.html` | Show page with a season picker and a pop-up player per episode |

## Built with

- HTML, CSS and JavaScript, with no build step
- Bootstrap 4 and jQuery 3.4
- Slick and Owl Carousel for the sliders, Magnific Popup and Select2
- Font Awesome 6.4 for icons

## Run it

Open `index.html` in a browser, or serve the folder:

```bash
npx serve .
```

## Status

This is an early learning project and is not maintained. Video links point to
third-party hosts and most no longer work. Some pages (`100.html`,
`F.R.I.E.N.D.S.html`, `POI.html`, `Peaky Blinders.html`) are empty
placeholders.
