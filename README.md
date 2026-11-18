# ClearView Tracker — Trinity Woods

Static single-page site showing ClearView Services maintenance history for
Trinity Woods. No build step, no backend, no Netlify — GitHub Pages serves
`index.html` as-is.

## Data (live, not in this repo)

- Jobs: Google Sheet "ClearView Tracker – Live Jobs", tab "Sheet1" — read
  as CSV. This is the only data source; editing the sheet updates the page.
- Ty's checkmark ("invoice processed") and new work orders: Google Form —
  the page fills a hidden form and submits it; the hourly watch script reads
  responses back into the sheet.

## Editing

Edit `index.html`, commit, push to `main`. Pages publishes the push
automatically.

## Live URL

https://quincyeason.github.io/clearview-tracker/
(previous host: https://clearview-status-trinity-woods.netlify.app — do not
delete until the cutover is confirmed)
