# AidroidJa — Privacy & data deletion (Netlify)

Public site for [aidroidprivacy.netlify.app](https://aidroidprivacy.netlify.app).

| Path | File |
|------|------|
| `/` | `index.html` — privacy policy |
| `/delete` | `delete/index.html` — Play Console delete-data URL |
| `/app-ads.txt` | AdMob app-ads.txt |

## Deploy

Connected to Netlify from this repo. Publish directory: `.` (root). No build command.

## Local preview

```bash
python3 -m http.server 8080
```

- Privacy: http://localhost:8080/
- Delete: http://localhost:8080/delete/

## Add another app (data deletion)

Edit `delete/index.html`: add a nav link and a new app section. Keep the same `/delete` URL in Play Console.
