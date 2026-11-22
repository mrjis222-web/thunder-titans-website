# Thunder Titans Club Website

A responsive, orange-themed club website made with plain HTML, CSS and JavaScript.

## Run in VS Code
1. Extract `thunder-titans-website.zip`.
2. Open the `thunder-titans-website` folder in VS Code.
3. Install the **Live Server** extension (if you do not already have it).
4. Right-click `index.html` → **Open with Live Server**.

You can also open `index.html` directly in a browser.

## Add your own logo and team photos
Put your images inside the `assets` folder and keep these exact file names:

- `club-logo.png` — club logo (transparent PNG works best)
- `advisor.jpg` — advisor photo
- `president.jpg` — president photo
- `vice-president.jpg` — vice president photo
- `secretary.jpg` — secretary photo
- `brand-ambassador.jpg` — brand ambassador photo

If your image is PNG or WebP, either convert it to JPG or update the matching image path in `index.html`.

## Add names and social links
Open `index.html` and find the `team-grid` section. Replace role titles and `Thunder Titans` text with each person's real name and designation.

In the footer, replace the `href="#"` values with your actual Facebook, Instagram and YouTube page links.

## Activate the contact form
Open `script.js` and change:
`const CLUB_EMAIL = "yourclubemail@example.com";`
to the club's real email address.

The form uses the visitor's email app (`mailto:`). It does not store messages on a server. To receive messages without opening an email app, you will need a backend or a form service.

## Update gallery photos
Search in `index.html` for `gallery-grid`. Replace the sample image URLs with your own image paths, for example:
`assets/gallery-1.jpg`

Add those image files to the `assets` folder.

## Notes
- The site is responsive for desktop, tablet and mobile.
- Some hero/activity/gallery images are sample online photos and need internet access.
- Google Fonts and Lucide icons also load from the internet.
- Update any club details, names, email address and social links before publishing.
