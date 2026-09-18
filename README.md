# Camden da Silva — portfolio site

A single-page personal site built from `portfolio.tex`. Plain HTML and CSS, no build step and no framework, so GitHub Pages can serve it as-is.

Every file sits at the top level — no subfolders — so the whole site can be uploaded in one drag or one file-picker selection.

## Files

| File | What it is |
| --- | --- |
| `index.html` | The whole site — text and styling in one file |
| `*.png`, `*.jpg` | Figures and photos used on the page |
| `portfolio.pdf` | The PDF portfolio, linked from the header and footer |

## Putting it online (GitHub Pages)

1. Create a repository named `<your-username>.github.io` (public).
2. Upload every file in this folder — select them all at once.
3. Settings → Pages → Source: *Deploy from a branch*, branch `main`, folder `/ (root)`.
4. Wait a minute or two, then open `https://<your-username>.github.io`.

## Changing the site later

Everything is in `index.html`. Search for the heading you want to change and edit the text around it. Colours, fonts and spacing are the `--variables` in the `<style>` block near the top of the file. To add a project, copy one `<article class="project">` block and replace its contents.

New figures go in this same folder and are referenced by filename alone, e.g. `<img src="your-file.png">`. Keep them under about 300 KB each so pages load quickly.
