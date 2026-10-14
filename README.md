# Harsh Kumar: Portfolio

A single-page portfolio (HTML, CSS and JavaScript in one file) with a 3D backend-architecture background,
a star-map of tools, a project filter and a message form that emails you through Web3Forms.

## Files
- `index.html`: the whole site. Photo, logos and styles are embedded, so nothing else is needed.
- `.nojekyll`: tells GitHub Pages to serve the file as it is.
- `README.md`: this guide (you do not have to upload it).

## Deploy on GitHub Pages (free)
1. Sign in to GitHub and create a new **public** repository named `portfolio`.
2. Click **Add file > Upload files**, drag in `index.html` and `.nojekyll`, then **Commit changes**.
   (If your system hides `.nojekyll`, skip it; the site works without it.)
3. Go to **Settings > Pages**. Under *Build and deployment*, set **Source** to *Deploy from a branch*,
   choose branch `main` and folder `/ (root)`, then **Save**.
4. After 1-2 minutes the site is live at `https://<your-username>.github.io/portfolio/`.
   For a cleaner address, name the repository `<your-username>.github.io` instead; the site is then at
   `https://<your-username>.github.io/`.
5. Open the site, send yourself a test message from the form, and check your inbox and spam folder.

## Message form
The form posts to Web3Forms and the message arrives in your email. The access key is already set in
`index.html` (search for `web3formsKey`). It is not a secret. The free plan allows 250 messages a month.
The form only sends from a real host such as GitHub Pages; opened from a local file or inside claude.ai it
falls back to opening the visitor's email app.

## Editing your content
Open `index.html` in a text editor and find the block that starts with `/* ===== EDIT THIS BLOCK`.
It holds your name, email, bio, stats, projects, education and achievements, skills and links.
Save the file and upload it to the repository again (**Add file > Upload files**, same name) to update the site.

## Tips
- Keyboard shortcut: press `/` or `Ctrl/Cmd + K` for the command palette.
- Three themes (Midnight, Paper, Terminal) are in the top-right switcher.
- Make sure the Google Drive resume link is set to "Anyone with the link".
