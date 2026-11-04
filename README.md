# Acid Green Film Site — GitHub-ready (flat files)

Your original Acid Green Film Site, with realistic crinkled tape and silver chain dividers.
The extra duct tape in the CONTACT section has been removed.

## Upload to GitHub — NO folders needed

1. Download the ZIP and **extract/unzip it** on your computer.
2. Open the extracted folder. Select all SIX files listed below.
3. In your GitHub repository, choose **Add file → Upload files**.
4. Drag those six individual files to the upload area and **Commit changes**.
5. If you are replacing an existing site, upload the files to your existing repository and confirm you are overwriting the same filenames.
6. Open **Settings → Pages** and select **Deploy from a branch**, **main**, **/(root)** if it isn't configured already.
7. After GitHub Pages finishes deploying, hard-refresh your site (on Mac, Cmd + Shift + R).

## Exact files to upload

- `index.html` — site content: name, bio, social links, film credits, media, email
- `style.css` — appearance: colors, layout, tape and chain decorations
- `headshot.jpg` — your photo
- `silver-tape.png` — realistic crinkled tape shown above your photo
- `chain-divider.png` — silver chains used for dividers
- `README.md` — these instructions (optional to upload)

**All files go at the TOP LEVEL of the repository alongside `index.html`. Do not upload the ZIP itself, and do not create an `assets` folder.**

## Editing

Open `index.html` and search for `EDIT:` comments to replace your bio, name, links, credits, YouTube embeds, and contact email. Open `style.css` to change the colors in `:root` or edit the site layout. The chain graphics and tape are linked as `chain-divider.png` and `silver-tape.png` (without `assets/`).

The original site uses W3.CSS and Google Fonts from public CDNs; an Internet connection is required for those external styles/fonts.

## Contact and media

The email button uses `mailto:` because GitHub Pages is static; it does not receive or store submissions. The Media section contains sample placeholders with a commented example for a YouTube embed.
