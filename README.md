# Delta Clearance Calculator

Offline/online delta clearance calculator with blue, grey, and light themes, built for quick ruling-span and actual-span clearance checks.

## Included files

- `index.html` — main landing page with links to each theme
- `blue.html` — dark blue theme
- `grey.html` — neutral dark gray theme
- `light.html` — light gray theme
- `.nojekyll` — keeps GitHub Pages from processing the files with Jekyll
- `README.md` — this guide

## How to use it online with GitHub Pages

1. Upload all files to the root of your GitHub repository.
2. In the repository, go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the `main` branch and the `/root` folder.
5. Click **Save**.
6. Open the GitHub Pages link once GitHub finishes publishing the site.

The main online page will be:

```text
https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/
```

The direct theme links will be:

```text
https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/blue.html
https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/grey.html
https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/light.html
```

For this repository, the link should look like:

```text
https://AZX-215.github.io/delta-clearance-calculator/
```

## How to use it offline

1. Download or clone the repository to your computer.
2. Open the folder in File Explorer.
3. Double-click `index.html` to open the theme chooser in your browser.
4. Select Blue, Grey, or Light.

You can also open a theme directly by double-clicking:

- `blue.html`
- `grey.html`
- `light.html`

No internet connection is required once the files are on your computer. The calculator is built into the HTML files and does not depend on outside websites, scripts, or services.

## Using it from Google Drive or OneDrive

You can store the files in a synced folder like Google Drive for Desktop or OneDrive and open them from File Explorer. That still runs the calculator locally on your computer.

Opening the files from the Google Drive website may show a preview or download prompt instead of running the calculator as a normal webpage. For a real online webpage, use GitHub Pages.

## Calculator features

Each theme has the same calculator functions:

- 1, 2, or 3 calculators visible at once
- Ruling span helper
- Conductor/table selection
- Actual span input
- Ruling span input
- Automatic nearest ruling-span table selection
- Final clearance result with raw calculation shown
- Warnings when the selected table does not directly cover the entered values

## Notes

- Settings are saved locally in the browser using local storage.
- Saved settings may be separate for the online version and the offline local file version.
- Treat warnings or extrapolated values as check items and verify against the original standard or workbook before final design use.
