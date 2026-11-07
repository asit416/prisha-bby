# A Little Diwali Surprise for Prisha

## Open the website
1. Extract this ZIP.
2. Double-click `index.html` to preview it in your browser.
3. It also works as a static website on GitHub Pages, Netlify, or Vercel.

## Add your photos
- Open the page and click **Customize** (bottom-right).
- Choose photos for the six slots and edit captions.
- **Save on this device** saves photos in that browser only.
- **Export photo backup** downloads a JSON backup of your selected photos.

Important: browser-local saves do NOT automatically appear for Prisha on a public link or on another device. To put your actual photos on the published website, the simplest reliable method is to add image files to the website project and deploy again. If you send me your chosen photos, I can help prepare the gallery with them embedded.

## Publish using GitHub Pages
1. Create a new GitHub repository.
2. Upload `index.html` (and any image files you add).
3. In repository Settings -> Pages, choose deploy from branch `main` and folder `/ (root)`.
4. Wait for GitHub Pages to publish and share the generated URL.

## Notes
- The website uses Google Fonts; an internet connection is needed for those fonts.
- The background music control is intentionally subtle and starts only after a click. It is a simple synthesized ambient tone, not a commercial song.
- The site is responsive and uses CSS/Canvas effects rather than a heavy WebGL scene, so it should run more reliably on phones.

## Update: photos are now built in
The 6 gallery photos live in `assets/photos/` (photo-1.jpg ... photo-6.jpg) and are the default gallery images.
Upload the WHOLE folder contents (index.html + assets/) to GitHub so everyone sees them.
Image paths are relative (assets/photos/...), so they work on GitHub Pages project sites.
To swap a photo later, replace the file in assets/photos/ with the same name.
