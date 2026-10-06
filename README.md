# QuickFile Support Portal

The homepage that links to all the QuickFile tools and help: https://quickfile-support-portal.vercel.app/

It's a single static `index.html` with no build step. Vercel publishes it straight from this GitHub repo (steemac/QuickFile-Support-Portal).

## Publishing a change
1. Edit `index.html`, or ask Claude to.
2. Open **GitHub Desktop** and pick this repository (**QuickFile-Support-Portal**).
3. Check the change in the **Changes** tab, type a short summary (e.g. "Add MTD guide card") and click **Commit to main**.
4. Click **Push origin**.
5. Vercel redeploys in about a minute. Refresh https://quickfile-support-portal.vercel.app/ to check it.

To preview before pushing, double-click `index.html` to open it in your browser.

## Adding a new tool card
Each tool is an `<article class="tool">` inside `<section class="tools" id="tools">`. To add one:
1. Copy an existing `<article class="tool">…</article>` block.
2. Change the eyebrow, `<h3>` title, description, feature tags (`<li>`), the quick guide steps and the button link.
3. Give the `<details>` a unique id, e.g. `id="guide-mtd"`.

Cards appear in the order they're written.

## Tools linked from the portal
| Card | Link |
|---|---|
| Community Forum | https://community.quickfile.co.uk/ |
| QuickFile Videos | https://quickfile-videos.vercel.app/ |
| Support Articles | https://support.quickfile.co.uk/ |
| YouTube Channel | https://www.youtube.com/@QuickFileHelpGuides |
| MTD for Income Tax Guide | https://quickfile-mtd-itsa-guide.vercel.app/ |
| Reporting | https://reporting-tool-v2.vercel.app/ |
| Archive | https://quickfile-archive-viewer.vercel.app/ |
| Academy | https://quickfile-academy.vercel.app/ |
| Demo Data | https://quickfile-demo-data.vercel.app/ |
| Blog | https://community.quickfile.co.uk/c/blog/47 |
