# mokalauver

Posts and backups for the **Moka** account of [illitlauver](https://github.com/illitlauver/hub) — an ILLIT fan project in the style of Laufey's lauvers. *Fan account; not affiliated with ILLIT, BELIFT LAB, or Laufey.*

## Posting

1. Add photos to a new folder under `posts/`, e.g. `posts/2026-10-09-concert/1.jpg`, `2.jpg`, …
2. Commit them. **The commit message is the Instagram caption** (multiple lines and emoji are fine).
3. Push to `main`. The *Post to Instagram* action posts it — one photo is a single post, 2–10 photos become a carousel in filename order.

- Add `[skip post]` to the commit message to back up photos without posting.
- Photos may be JPG, PNG, WEBP, or HEIC; they're converted to JPEG and location data is stripped.
- Shape must be between 4:5 portrait and 1.91:1 landscape, or the post is rejected — crop first.
- Results (and post links) appear in the action run's summary; the `bot` branch keeps the posted log.
