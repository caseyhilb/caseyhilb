# YOUR NAME — Actor & Filmmaker Portfolio

A **free, mobile-first, one-page website** built for GitHub Pages using HTML, W3.CSS, and custom CSS. No server or build process needed.

## Files
- `index.html` — **edit your words, links, projects, videos, and email here**.
- `style.css` — edit the colors and visual styling here.
- `assets/headshot.jpg` — the headshot you supplied.

## 1. Personalize your website

Open `index.html` in a text editor (or edit it directly on GitHub). Search for `EDIT` comments, which mark places to make changes.

- **Name:** Replace `YOUR NAME` and `YOUR<span>NAME</span>` with your name. The latter is two separately colored parts; e.g., `CASEY<span>HILB</span>`.
- **Bio:** Locate `<p class="bio">` and replace the words between `<p ...>` and `</p>`.
- **Instagram / IMDb:** Replace `href="#"` in the two social buttons with full profile URLs, e.g. `href="https://www.instagram.com/yourusername/"`.
- **Credits:** In the RESUME section, replace every example `credit-row`. Copy one entire `<article class="credit-row"> ... </article>` to add more. Place newest credits at the top within each group.
- **Email:** Replace both occurrences of `hello@example.com` with your email address in the CONTACT section. Keep `mailto:` as is.
- **Page title:** Replace `YOUR NAME` in the `<title>` near the top of `index.html`.
- **Footer:** Replace `YOUR NAME` at the bottom.

### How to embed YouTube videos

Find the `media-grid` section in `index.html`. Delete one placeholder:

```html
<div class="video-placeholder"> ... </div>
```

and paste this in its place (replace `YOUR_VIDEO_ID` and the title):

```html
<article class="video-card">
  <div class="video-frame">
    <iframe
      src="https://www.youtube-nocookie.com/embed/YOUR_VIDEO_ID"
      title="My acting reel"
      loading="lazy"
      referrerpolicy="strict-origin-when-cross-origin"
      allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
      allowfullscreen></iframe>
  </div>
  <div class="video-details">
    <h3>ACTING REEL</h3><span>2026 / REEL</span>
  </div>
</article>
```

For `https://www.youtube.com/watch?v=AbCd123`, the video ID is `AbCd123`. For `https://youtu.be/AbCd123`, it's also `AbCd123`. Videos must permit embedding on YouTube.

### Change hex colors

Open `style.css` and find `:root` at the top. Replace the values for `--green`, `--green-light`, `--black`, `--gray`, etc. The rest of the site will update automatically.

### Change your headshot

Replace `assets/headshot.jpg` with another image using the same filename, or change the `src` attribute in the HOME section.

## 2. Publish free on GitHub Pages

1. Create a public repository on GitHub, e.g. `film-portfolio`.
2. Upload `index.html`, `style.css`, and the whole `assets` folder to the **root** of that repository (not another nested folder).
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**. Select `main` and `/(root)`, then save.
5. Your public site will appear at `https://YOUR-USERNAME.github.io/film-portfolio/`. If the repo is named `YOUR-USERNAME.github.io`, your site appears at `https://YOUR-USERNAME.github.io/`.
6. For future changes, edit files in GitHub and commit. GitHub Pages republishes the changes.

## 3. Contact limitations

GitHub Pages is static: it **does not have an internal inbox or process form submissions**. The CONTACT section uses a `mailto:` link instead. Clicking **EMAIL ME** opens the visitor's configured email handler, with your email address and the subject populated. A visitor needs an email app or webmail handler set up for this to work.

If you later want an actual contact form, you can integrate a third-party form service (e.g. Formspree), subject to that service's current free plan and privacy rules.

## Notes

- W3.CSS and Google Fonts load from external CDNs; the customized CSS is yours.
- The silver tape effect is created in CSS and inspired by your reference image, so it doesn't need a separate picture file.
- The layout is designed mobile-first, scales up to desktop, and includes keyboard focus styles and a reduced-motion preference.
- All displayed film entries and media items initially are **obvious sample placeholders** until you replace them with your real work.
