# Personal website

Source of https://khvatkinnikita.github.io/website/. GitHub Pages serves these files as they are from the `main` branch of the repository `KhvatkinNikita/website`. There is no build step.

| File | What it holds |
|---|---|
| `index.html` | About, research and publications, timeline, contact |
| `cv.html` | The CV as a web page, and the source of `cv.pdf` |
| `cv.pdf` | The CV to download |
| `style.css` | Colours, fonts and layout of both pages, including the print layout of the CV |
| `photo.jpg` | Profile photo, 400 × 400 px |
| `.nojekyll` | Tells GitHub Pages to publish the files without processing them |

## Preview

Open `index.html` in a browser.

## Update

1. Edit the text in `index.html` or `cv.html`. A new paper or talk goes in three places: the publications in `index.html`, the timeline in `index.html` and the CV in `cv.html`.
2. If `cv.html` changed, make the PDF again: open `cv.html` in Edge or Chrome, Print, Save as PDF, untick "Headers and footers", and save over `cv.pdf`.
3. Publish:

   ```
   git add -A
   git commit -m "Describe the change"
   git push
   ```

   The site shows the change about a minute later.
