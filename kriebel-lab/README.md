# Floral Evolution Lab website

A simple, no-build lab website: one page with a banner and four tabs (Research, Publications, Data, Art).

## Files
- `index.html` – all the content. Text in [square brackets] is placeholder to replace.
- `style.css` – colors and layout. Change the colors at the top (`--accent`, etc.).
- `assets/banner.svg` – the banner image. Swap in your own photo by adding it to `assets/` and editing the `url(...)` in `index.html`.

## Put it online with GitHub Pages

Your URL depends on your GitHub username:

| What you name the repository | Your site's address |
|---|---|
| `USERNAME.github.io` | `https://USERNAME.github.io` |
| `rkriebel` (or anything else) | `https://USERNAME.github.io/rkriebel` |

So to get **ricardokriebel.github.io** or **rkriebel.github.io**, your GitHub username must be `ricardokriebel` or `rkriebel` (you can change it under Settings → Account if it's free). Alternatively, buy a domain such as `rkriebel.com` (~$12/yr) and point it at GitHub Pages.

### Steps (no command line needed)
1. On github.com, click **New repository**. Name it `USERNAME.github.io` (with your actual username). Make it **Public**. Create it.
2. Click **uploading an existing file**, drag in `index.html`, `style.css`, `README.md` and the `assets` folder, then **Commit changes**.
3. Go to **Settings → Pages**. Under "Build and deployment", choose **Deploy from a branch**, branch **main**, folder **/ (root)**, and Save.
4. Wait a minute or two, then open `https://USERNAME.github.io`.

To edit later: open `index.html` on GitHub, click the pencil icon, change text, and commit. The site updates in about a minute.

### Adding a tab
In `index.html`, copy one `<a href="#...">` line in the `<nav>` and one `<section id="...">` block, giving both the same new name (e.g. `people`).
