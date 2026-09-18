# Camden da Silva — portfolio site

A single-page personal site built from `portfolio.tex`. Plain HTML and CSS, no build step and no framework, so GitHub Pages can serve it as-is.

## Files

| File | What it is |
| --- | --- |
| `index.html` | The whole site — text and styling in one file |
| `images/` | Figures and photos used on the page |
| `portfolio.pdf` | The PDF portfolio, linked from the header and footer |

## Putting it online (GitHub Pages)

1. Create a repository named `<your-username>.github.io` (public).
2. Upload everything in this folder, keeping the `images` folder intact.
3. Settings → Pages → Source: *Deploy from a branch*, branch `main`, folder `/ (root)`.
4. Wait a minute or two, then open `https://<your-username>.github.io`.

## Changing the site later

Everything is in `index.html`. Search for the heading you want to change and edit the text around it. Colours, fonts and spacing are the `--variables` in the `<style>` block near the top of the file. To add a project, copy one `<article class="project">` block and replace its contents.

New figures go in `images/` and are referenced as `images/your-file.png`. Keep them under about 300 KB each so pages load quickly.
