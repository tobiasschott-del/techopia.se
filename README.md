# techopia.se

Website for Techopia, a discreet headhunting and executive search firm for emerging tech.

Plain static site. No build step, no dependencies.

## Structure

- `index.html` – the page
- `assets/style.css` – styles (dark palette; the hero light streak is inline SVG in `index.html`)
- `assets/fonts/` – self-hosted Familjen Grotesk and Playfair Display (SIL Open Font License)
- `assets/logo.svg` – logo (The Thinker in front of a globe, vector style), also used as favicon

## Run locally

```sh
python3 -m http.server 8000
```

Then open http://localhost:8000.

## To fill in before launch

- LinkedIn profile link (not on the page yet)
