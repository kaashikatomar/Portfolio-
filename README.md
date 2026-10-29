# Kaashika Tomar — Personal Portfolio

A lightweight, responsive personal portfolio built with semantic HTML, CSS, and vanilla JavaScript. It has no build step or third-party runtime dependencies, and can be published directly with GitHub Pages.

## Preview locally

Open `index.html` in a browser, or serve the folder locally for a closer match to a hosted site:

```sh
python3 -m http.server 8000
```

Then visit [http://localhost:8000](http://localhost:8000) from this folder.

## Publish with GitHub Pages

1. Create a GitHub repository and place the contents of this folder at the repository root.
2. Push the files to the repository's default branch.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, then select the default branch and the `/ (root)` folder. Save.
5. GitHub will show the published address in the Pages settings when the deployment is ready.

The site uses relative asset paths, so it works on both a user site and a repository project site such as `https://username.github.io/repository/`. `.nojekyll` is included to let GitHub Pages serve files directly.

## Edit the portfolio

- **Text and sections:** edit `index.html`. The hero, About, interests, skills, experience, projects, contact details, and footer are all in that file.
- **Look and layout:** edit `styles.css`. Colors and typography are set near the top in `:root`.
- **Navigation and gentle reveal effects:** edit `script.js`. The mobile menu works with a keyboard, and reveal effects switch off for reduced-motion preferences.
- **Contact links:** search for `kaashikatomar@gmail.com`, `github.com/kaashikatomar`, and the LinkedIn URL in `index.html`.
- **Add a project:** duplicate the `<article class="project-entry">` block in the Projects section and replace its title, description, category, and status. Add an external link only when there is a real project URL to share.
- **Record details:** update the neutral recognition line in the Experience section once exact titles, dates, descriptions, and source links are available.

No project screenshots, project URLs, dates, record titles, or technical achievements have been fabricated. Fonts are requested from Google Fonts; system serif and sans-serif fallbacks keep the layout usable if that service is unavailable.
