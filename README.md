# mokalauver

Backup of [@mokalauver](https://www.instagram.com/mokalauver/), the **Moka** account of [illitlauver](https://github.com/illitlauver/hub) — ILLIT fan accounts with a Laufey theme. *Fan account; not affiliated with ILLIT, BELIFT LAB, or Laufey.*

This repo fills itself: every hour, the hub's *Back up Instagram* action copies any new posts here.

- **`posts/`** — photos and videos, named `YYYYMMDD-N.ext` (e.g. `20260504-1.jpg`, `20260504-2.jpg` for a 2-photo carousel). The date comes from the caption if it contains one (`260504`, `20260504`, `2026.05.04`, …), otherwise from the day it was posted (Taiwan time). N keeps counting if several posts share a date.
- **Commit history** — one commit per post, with the caption as the commit message.
- **`posts.json`** — every post's caption, Instagram link, post time, and files. Edited captions are updated here; posts deleted from Instagram stay in the backup.
