# Zachary Sheppard — Portfolio

My personal portfolio site: projects, skills, experience and contact links.

## Files

- `index.html` — the whole site (HTML, CSS and a little JS in one file). Open it in a browser to preview.

## Edit it

Open `index.html` in VS Code. Each section is marked by an `id`:
`#projects`, `#skills`, `#about`, `#contact`. To add a project, copy one `<article class="proj">` block and change the text and links.

## Put it online with GitHub Pages (free)

1. On GitHub, create a new **public** repo named exactly `zsheppard78.github.io`.
2. In this folder, run:

   ```bash
   git init
   git add .
   git commit -m "Initial portfolio site"
   git branch -M main
   git remote add origin https://github.com/zsheppard78/zsheppard78.github.io.git
   git push -u origin main
   ```

3. On GitHub go to the repo's **Settings → Pages** and make sure the source is the `main` branch, root folder.
4. After a minute or two the site is live at **https://zsheppard78.github.io**.

To update it later: edit `index.html`, then `git add . && git commit -m "Update" && git push`.

## Ideas for later

- Add `resume.pdf` to this folder and a "Download resume" button linking to it.
- Point each project's "Code" button at its own GitHub repo.
- Add screenshots of the live apps.
