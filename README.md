# The College Adjutant: BAF Shaheen Edition

A fun Instagram web-link game landing page. You play as the adjutant of BAF Shaheen College.
This game is made purely for fun and entertainment. Characters and events are fictional.

## Files

- `index.html` is the whole page (HTML, Tailwind CSS, Font Awesome, Google Fonts).
- `logo.png` is your logo. Put it in the same folder as `index.html`. It is not included here.
  If the file is missing, a placeholder emblem shows instead.

## Before you publish

Open `index.html` and change these:

- `@your_username` to your real Instagram username (search for it in the file).
- Check the name, "Inspired by" line and footer text.

## Publish with GitHub Pages (free link)

1. On GitHub, create a new repository and set it to **Public**.
2. Upload `index.html` and `logo.png` (Add file, then Upload files). Commit.
3. Open the repository **Settings**, then **Pages**.
4. Under Build and deployment, choose **Deploy from a branch**, pick `main` and `/ (root)`, then Save.
5. After a minute or two the link appears on that page. It looks like
   `https://<your-github-username>.github.io/<repository-name>/`.
   Put that link in your Instagram bio or story.

## Notes

- The "Total appointed Adjutants" counter is saved with `localStorage`, so it is stored
  in each player's own browser. It is not a shared total across all players.
- The page needs internet, because Tailwind, Font Awesome and the Google Fonts load from CDNs.
