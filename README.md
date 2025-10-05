# The Flushing A Website

A single-file, mobile-friendly site for **The Flushing A** (Flushing, MI). Includes menu scans with searchable web-formatted text, a gallery, an About/Legacy section, community events, and local business links.

## Project Structure
```
flushinga-site-mb86/
│── index.html
└── images/
    ├── logo/
    │   └── flushinga_logo.jpg
    └── menu/
        ├── page1.jpg
        ├── page2.jpg
        └── page3.jpg
```

## Run Locally
Open `index.html` in any modern browser.

## Deploy on GitHub Pages
1. Create a new repo named `flushinga-site` on GitHub.
2. Upload all files in this folder to the repo (or drag-drop the zip contents).
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, set:
   - **Source**: `Deploy from a branch`
   - **Branch**: `main` and **Folder**: `/ (root)`
5. Save. Your site will appear at:
```
https://<your-username>.github.io/flushinga-site-mb86/
```

## Editing Content
- Replace the three scan images in `images/menu/` if you update menu photos.
- Replace the logo at `images/logo/flushinga_logo.jpg` to change branding.
- Edit the **About/Legacy** text directly in `index.html`.

## Notes
- Menu categories alternate subtle background tones for readability.
- Header uses a mobile hamburger; hero has quick links to key sections.
- Unsplash-powered gallery images are embedded via CDN.


## Guest Feedback (Interactive)
- The **Guest Feedback** section in `index.html` provides an in-page, interactive postcard-style survey.
- Submissions open the default email client addressed to `flushinga.official@gmail.com` with a date-stamped subject like `Flushing A Guest Survey YYYY-MM-DD HHMM` so you can sort emails by date easily.
- A printable postcard PDF is available at `docs/FlushingA_Customer_Survey_Print.pdf`.
