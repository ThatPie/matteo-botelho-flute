# Matteo Botelho's flute portfolio

The portfolio contains Home, Performances, and Contact pages. All three performance videos are included, with dates and credits from their descriptions and Matteo's approved wording. The approved plan and assignment checklist are in [PLAN.md](PLAN.md).

Live site: https://matteobotelho.com/

- Performances: https://matteobotelho.com/performances.html
- Contact: https://matteobotelho.com/contact.html

Repository: https://github.com/ThatPie/matteo-botelho-flute

## Files

- `docs/index.html`: page structure and Matteo's unchanged biography.
- `docs/performances.html`: solo and chamber performance videos, dates, and credits.
- `docs/contact.html`: both email addresses plus LinkedIn, YouTube, and Instagram.
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

Performances is at http://127.0.0.1:8080/performances.html while the local server is running. It can also be opened directly from `docs/performances.html`, though YouTube playback should be checked through the local server.

Contact is at http://127.0.0.1:8080/contact.html, or open `docs/contact.html` directly.

## Check phone width in Chrome

1. Open the page and choose View > Developer > Developer Tools, or press Option+Command+I on Mac.
2. Toggle the device toolbar with Option+Command+M.
3. Select Responsive and enter a width of 390px; repeat at 320px.
4. Check the header, stacked portrait and bio, readable text, and absence of sideways scrolling.
5. Also enlarge text using browser zoom and use Tab to check visible keyboard focus.

## Content decisions

Matteo supplied and selected the headshot. His biography wording is preserved from the brief; paragraph breaks are added for readability. The palette is #0E0E52, #3993DD, and #FCFCFC. Headings use Crimson Text; body text uses PT Serif. All fonts load locally.

The header links Home, Performances, and Contact. Contact includes five ordinary links, with no backend or form.

## Publishing

GitHub Pages is configured to publish the `docs/` folder from `main`. Updating website files in that folder and saving the changes to GitHub triggers publication. The rest of this repository stores the plan and instructions.

Before publication, the three pages were checked in the local browser on desktop and at 390px and 320px phone widths. Navigation, portrait, local fonts, keyboard focus, video playback, and contact destinations were verified.
