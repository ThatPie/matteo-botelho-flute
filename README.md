# Matteo Botelho's flute portfolio

The first version contains only the Home/About page. The approved future plan and assignment checklist are in [PLAN.md](PLAN.md).

## Files

- `docs/index.html`: page structure and Matteo's unchanged biography.
- `docs/styles.css`: typography, colors, desktop and phone layout.
- `docs/script.js`: keeps the copyright year current.
- `docs/assets/`: selected headshot and locally hosted fonts with their licenses.
- GitHub Pages publishes the `docs/` folder from the `main` branch. Planning documents are not served.

## Preview in a browser

Double-click `docs/index.html` to open it in your browser. No install or build is needed.

For a local server, run this from the `site` folder:

```sh
python3 -m http.server 8080 --bind 127.0.0.1 --directory docs
```

Then visit http://127.0.0.1:8080. Press Ctrl+C in the terminal when finished.

## Check phone width in Chrome

1. Open the page and choose View > Developer > Developer Tools, or press Option+Command+I on Mac.
2. Toggle the device toolbar with Option+Command+M.
3. Select Responsive and enter a width of 390px; repeat at 320px.
4. Check the header, stacked portrait and bio, readable text, and absence of sideways scrolling.
5. Also enlarge text using browser zoom and use Tab to check visible keyboard focus.

## Content decisions

Matteo supplied and selected the headshot. His biography wording is preserved from the brief; paragraph breaks are added for readability. The palette is #0E0E52, #3993DD, and #FCFCFC. Headings use Crimson Text; body text uses PT Serif. All fonts load locally.

The home navigation works now. Performances and Contact will be added to the header when those pages are built.
