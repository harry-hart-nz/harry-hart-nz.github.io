# Harry Hart — Portfolio (exported site)

This is a plain, static website — just HTML, CSS and images. No build tools,
no frameworks, no Claude account required. It works on desktop, tablet and
mobile out of the box (try resizing your browser, or open it on your phone).

## What's inside

```
index.html      Home
fuled.html      FULED case study
aureon.html     Aureon Nutrition case study
about.html      About
contact.html    Contact
css/style.css   All styling (colors, fonts, responsive breakpoints)
images/         All photos and screenshots, already compressed for the web
```

## Preview it locally

Double-click `index.html` to open it in a browser — everything works
offline except the two Google Fonts (Anton, Space Grotesk, Space Mono),
which need an internet connection to load.

## Put it on a real domain (free hosting)

The easiest path, no coding required:

1. **Netlify** — go to app.netlify.com/drop and drag the whole
   `site-export` folder onto the page. It's live at a `*.netlify.app`
   URL in seconds. Add a custom domain for free under Site settings →
   Domain management.
2. **Vercel** — similar drag-and-drop flow at vercel.com/new, or
   `npx vercel` from inside this folder if you're comfortable with a
   terminal.
3. **GitHub Pages** — push this folder to a GitHub repo, then turn on
   Pages in the repo's Settings tab. Free, and pairs well with a
   custom domain bought elsewhere (Namecheap, Google Domains, etc.).

Any of these gets you a real, permanent URL you can point a domain
like `harrisonhart.com` at — no Claude subscription needed for anyone
to view it.

## Editing it yourself

Everything is plain HTML/CSS, so you can open the files in any code
editor (VS Code is a good free option) and change text directly in the
`.html` files. Shared colors, fonts and spacing all live in
`css/style.css` — change a value there and it updates every page.
