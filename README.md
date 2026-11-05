# stefanruschel.github.io

Personal website of Stefan Ruschel, live at <https://stefanruschel.github.io>.

Two files make up the whole site:

- `index.html` holds all the content.
- `style.css` holds the look: colours and fonts are at the top.

## Updating the site

1. Open `index.html` and edit the text between the tags.
2. To add a publication or talk, copy an existing `<li> ... </li>` block, paste it at the top of its list and change the details. A ready-made template sits in a comment above the Publications section.
3. Commit and push. GitHub Pages republishes the site within a minute or two.

You can also edit directly on github.com: open `index.html`, click the pencil icon, edit, then "Commit changes".

## Changing the photo

Replace `images/photo.jpg` with another portrait-format image (2:3) of the same name. The original, uncropped photo is `images/SR_foto.png`.

## Previewing locally

Double-click `index.html` to open it in a browser.

## Publishing (first time only)

On GitHub, go to the repository's Settings → Pages and set Source to "Deploy from a branch", branch `main`, folder `/ (root)`.
