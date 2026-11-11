# techopia.se

Website for Techopia: executive search, headhunting and interim leadership for tech.

Plain static site. No build step, no dependencies.

## Structure

- `index.html` – the page
- `assets/style.css` – styles
- `assets/fonts/` – self-hosted Familjen Grotesk and Source Serif 4 (SIL Open Font License)
- `assets/favicon.svg`

## Run locally

```sh
python3 -m http.server 8000
```

Then open http://localhost:8000.

## To fill in before launch

- Contact email in `index.html` (currently `hello@techopia.se`)
- LinkedIn profile link in `index.html`
