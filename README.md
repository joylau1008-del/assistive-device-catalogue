# CareKit Assistive Device Catalogue

This is an independent, static website for four sample assistive devices. It can be hosted on GitHub Pages, Cloudflare Pages, or opened locally from the folder.

## Files

- `index.html` — the complete website.
- `catalogue.csv` — device data used by the website.
- `images/` — product photographs.

## Test locally

Open `index.html` in a browser. The website includes the four sample devices as a built-in fallback, so the search and filters also work when the CSV cannot be loaded from a local file.

## Publish with GitHub Pages

1. Create a free GitHub account at https://github.com.
2. Create a new repository, for example `assistive-device-catalogue`.
3. Upload `index.html`, `catalogue.csv`, and the complete `images` folder.
4. Open repository **Settings**.
5. Select **Pages**.
6. Choose **Deploy from a branch**.
7. Choose the `main` branch and `/root` folder.
8. Select **Save**.
9. GitHub will provide a normal website address such as `https://yourusername.github.io/assistive-device-catalogue/`.

## Update the devices

Open `catalogue.csv` in Excel or Google Sheets. Keep one device per row and keep the column headings unchanged. Add new rows for new devices. Use a permanent unique ID. Put the matching picture in `images/` and write its filename in the `Image Filename` column.

Functions are separated with a vertical bar (`|`), for example:

```text
Bathing|Transfers|Seated shower
```

After updating the CSV or images, upload the changed files to GitHub. The website will use the new catalogue after GitHub Pages finishes publishing the update.

## Privacy

Only publish general product information. Do not put patient names, diagnoses, identity numbers, clinical records, or patient photographs in this public website.
