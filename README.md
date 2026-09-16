# gabrielloufi.github.io

Personal site — portfolio, publications and CV. Static HTML, no build step, no JavaScript beyond
a one-line copyright year. Served by GitHub Pages at <https://gabrielloufi.github.io>.

```
index.html          Home: intro, selected projects, toolkit, contact
projects.html       Full project write-ups
publications.html   Research, with the record on Scholar and Lattes
cv.html             Roles, education, skills
assets/css/style.css   Everything visual (design tokens at the top)
```

## Design

The palette and typography follow the LinkedIn banner: near-black ground with a dotted grid,
heavy Inter headlines against JetBrains Mono for code and metadata, and three neon accents —
magenta `--pink`, violet `--violet`, green `--green`. All of them are custom properties declared
once in `:root` at the top of `assets/css/style.css`; change them there and the whole site follows.

The site is dark only, on purpose — a light variant would not be the same brand.

## Editing

There is no templating layer, so the nav and the footer are repeated in all four pages and have to
be changed in all four. `publications.html` carries a commented-out block showing the markup for a
publication entry.
