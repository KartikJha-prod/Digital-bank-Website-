# Digitalbank

A responsive landing page for a fictional digital bank, built with plain HTML and CSS. It has a navbar, hero, features section, latest-articles grid and footer.

## Project Structure

```
.
├── index.html
├── style.css
├── README.md
└── Images/
    ├── bg-intro-desktop.svg
    ├── image-mockups.png
    ├── image-currency.jpg
    ├── image-restaurant.jpg
    ├── image-plane.jpg
    ├── image-confetti.jpg
    └── icon-*.svg (facebook, youtube, twitter, pinterest, instagram)
```

## Run Locally

1. Keep `index.html`, `style.css` and the `Images` folder together.
2. Open `index.html` in your browser.

## View It Online with GitHub Pages

1. Create a new repository on GitHub and upload all the files, keeping the `Images` folder.
2. Make sure `index.html` is in the root of the repo.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
5. Choose the **main** branch and the **/ (root)** folder, then click **Save**.
6. Wait 1 to 2 minutes. Your site will be live at:
   `https://<your-username>.github.io/<repo-name>/`

> **Important:** use relative image paths such as `Images/image-mockups.png`, not `/Images/...`. A leading slash breaks images on a GitHub Pages project site. File names are also case-sensitive there, so `Images` and `images` are different folders.

## Customization

- Brand gradient: `#33D35E` to `#2AB6D9`
- Footer color: `#2E3052`
- Layout lives in `.Grid-container`, `.features`, `.grid-container-2` and `.footer` in `style.css`

## License

Add a license here if you plan to share the project.
