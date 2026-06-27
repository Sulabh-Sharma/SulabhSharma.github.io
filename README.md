# SulabhSharma.github.io

# Your Portfolio — Edit & Publish Guide

This is a single file, `index.html`. Everything — text, colors, layout — lives
inside it, so there's nothing to install and no build process.

## Editing the content

1. Open `index.html` in any text editor (VS Code, Notepad, TextEdit — anything works).
2. Scroll to find the part you want to change. The file is broken into clearly
   labeled blocks, e.g.:
   ```
   <!-- SECTION: HERO  — main headline, summary, contact buttons -->
   ```
3. Change the text between the tags. For example, to update your headline, find
   this line and edit the words inside it:
   ```html
   <h1>I build cloud pipelines that <span class="accent">catch their own mistakes</span> before production does.</h1>
   ```
4. Save the file. Open it in a browser (just double-click it) to preview your change.

You don't need to touch anything in `< >` brackets — just the words around them.

## Changing colors or fonts

Near the very top of the file, inside `<style>`, there's a block that starts with:
```css
:root{
  --bg: #0E141B;
  --blue: #5B8DEF;
  ...
}
```
Change any hex code there and it updates everywhere that color is used on the site.

## Adding a new job, skill, or project

Copy an existing block (e.g. one `<div class="job">...</div>` for a new role, or
one `<span class="pill">...</span>` for a new skill tag) and paste a duplicate
right below it, then edit the text inside your copy.

## Publishing it online (free options)

**Easiest — Netlify Drop**
1. Go to https://app.netlify.com/drop
2. Drag your `index.html` file onto the page.
3. You instantly get a live URL you can share. Re-drag the file any time you
   make an edit, to update the live site.

**GitHub Pages (good if you already use GitHub)**
1. Create a new repository, e.g. `sulabh-portfolio`.
2. Upload `index.html` (rename it to stay `index.html`).
3. In the repo, go to Settings → Pages → set source to the main branch.
4. Your site will be live at `https://<your-username>.github.io/sulabh-portfolio/`.

**Vercel**
1. Go to https://vercel.com, sign up, and choose "Add New Project".
2. Drag and drop the folder containing `index.html`.
3. Deploy — you'll get a live URL.

Any of these let you re-upload the file whenever you make changes, and the
live site updates within seconds.

## Coming back to Claude for changes

If you'd rather not hand-edit the HTML, you can paste the updated resume text
or describe the change you want, and ask for a fresh version of `index.html`.
