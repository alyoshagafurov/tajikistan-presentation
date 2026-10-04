# Tajikistan — A portrait

An English-language, eighteen-slide photo presentation by **Abdullo Gafurov**. Every slide pairs a full-screen photograph and a different ornamental overlay with a headline and one short supporting line. The accompanying English script is in [SPEAKER_NOTES.md](SPEAKER_NOTES.md). The site includes locally stored photographs, Wikimedia Commons images with credits, generated images, and browser-native transitions; there is no build step or package installation.

## Present the slides

Open `index.html` in a modern browser. For the best experience, use fullscreen mode. Use [SPEAKER_NOTES.md](SPEAKER_NOTES.md) for the separate spoken text for each slide.

- `←` / `→` or `Page Up` / `Page Down`: previous or next slide
- `Home` / `End`: first or last slide
- Swipe left or right on a touch screen

The presentation respects the device's reduced-motion setting and works on mobile screens.

Image licenses, author credits, and fact references are listed in [PHOTO_CREDITS.md](PHOTO_CREDITS.md).

## Deploy to Vercel

Import the GitHub repository into Vercel. Select **Other** as the framework preset, leave the build command blank, and set the output directory to `.`. Vercel serves `index.html` and the local `assets/` folder directly. The included `vercel.json` enables clean URLs.

## Push to GitHub

Create an empty GitHub repository, then run these commands from this folder (replace the URL with your repository URL):

```sh
git remote add origin https://github.com/YOUR_USERNAME/tajikistan-presentation.git
git add .
git commit -m "Create Tajikistan presentation"
git push -u origin main
```

Alternatively, import the repository in GitHub Desktop and publish the `main` branch.
