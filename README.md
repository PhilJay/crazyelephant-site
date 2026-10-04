# Crazy Elephant site

This is the static landing site for Crazy Elephant, a trick shot game for iPhone and iPad. Preview it locally with `python3 -m http.server 8000` in this folder and open http://localhost:8000. It deploys as GitHub Pages from the `main` branch.

Styles live in `styles.css` and are copied into each page by `./build.sh`, so nothing blocks the first paint. Edit `styles.css`, run the script, and commit both.

`404.html` uses `<base href="/crazyelephant-site/">` so it works on any missing path; to preview it, serve the parent folder and open http://localhost:8000/crazyelephant-site/404.html.
