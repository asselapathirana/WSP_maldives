# WSP Videos Website

This is a minimal static site ready for GitHub Pages. It renders a grid of embedded YouTube videos and a simple resources section.

## Quick start

1. Create a new GitHub repository (public is easiest for Pages).
2. Upload the contents of this folder to the root of your repository.
3. Enable GitHub Pages:
   - Go to **Settings → Pages**.
   - Under **Build and deployment**, choose **Deploy from a branch**.
   - Select **Branch = main** (or your default) and **/ (root)**, then **Save**.
4. Your site will be published at the GitHub Pages URL shown on that page.

## Edit videos

- Update `data/videos.js` to add/remove YouTube video IDs. The page auto-numbers them as "WSP Video 1..N".
- You can also add an optional title per video (see comments in `data/videos.js`).

## Add files/resources

- Place PDFs or other files in the `assets/` folder and then add links in `index.html` under the **Resources** section.
- Two example placeholder files are included:
  - `assets/example-handout.txt`
  - `assets/README_assets.txt`

## Local preview

Just open `index.html` in a browser to preview locally.
