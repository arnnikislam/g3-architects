# G3 Architects

A responsive, single-page architecture studio landing page built with semantic HTML and custom CSS. It presents a hero banner, team gallery, feature highlights, company statistics, sponsor logos, and a footer.

## Live demo

[View the live site](https://arnnikislam.github.io/g3-architects/)

## Built with

- HTML5
- CSS3 (Flexbox, Grid, custom properties, and media queries)
- Google Fonts: Work Sans

## Features

- Responsive navigation and page sections for desktop, tablet, and mobile screens
- Reusable colour tokens and button styles
- Flexible team-image grid and feature layout
- Statistics and sponsor sections using local image assets
- No build tooling or JavaScript dependency: open the page directly in a browser

## Run locally

Clone or download the repository, then open `index.html` in a modern web browser. For a local development server, use any static-server extension or tool (for example, VS Code Live Server).

## Project structure

```text
g3-architects/
|-- index.html              # Page structure and content
|-- styles/
|   `-- style.css           # Visual design and responsive rules
`-- images/                 # Banner, team, feature, icon, and sponsor assets
```

## Responsive breakpoints

| Viewport | Layout behaviour |
| --- | --- |
| Up to 576px | Navigation, galleries, features, facts, and sponsors stack vertically. |
| 576px to 996px | Team and feature sections stack; facts and sponsors use two columns. |
| Above 996px | Desktop flex and grid layouts are used. |

## Notes

This is a static presentation project. The navigation links and "Explore More" controls are visual placeholders and do not currently lead to pages or trigger interactions.

## License

No license has been specified for this repository.
