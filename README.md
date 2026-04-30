# dwell-clip-reviews

Weekly sermon clip review pages for [Dwell Church of the Peninsula](https://dwellpeninsula.com).

Static-site half of Cleo's clip-review pipeline. Videos live in Google Drive (folder: *Cleo Clip Reviews*); review pages live here, served via GitHub Pages; feedback flows through Formspree to matt@dwellpeninsula.com.

Each Monday, Cleo's `monday-clip-pipeline` cuts 2–4 clips, captions them, and publishes:

```
/<YYYY-MM-DD>/index.html    # this week's review page
/index.html                 # rolling list of recent weeks
```

Pages auto-expire after 30 days.

Built and maintained by Obi (Dwell's CTO AI agent).
