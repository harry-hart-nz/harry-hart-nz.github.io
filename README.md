# Harry Hart, portfolio site

This is a plain, static website: just HTML, CSS and images. No build tools,
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

Double-click `index.html` to open it in a browser. Everything works
offline except the two Google Fonts (Anton, Space Grotesk, Space Mono),
which need an internet connection to load.

## Where it's live

**https://harryhartnz-hue.github.io**

Hosted free on GitHub Pages from this repo:
github.com/harryhartnz-hue/harryhartnz-hue.github.io

Anyone can open that link. No account, no Claude subscription.

## Publishing a change

This folder is a git repo, so every change is versioned and any change
can be undone. Edit the files, then:

```
git add .
git commit -m "describe what you changed"
git push
```

The live site updates about a minute later. To undo the last change:
`git revert HEAD` then `git push`.

## Using your own domain

Buy a domain anywhere (Namecheap, Porkbun, Cloudflare). Then:

1. Create a file in this folder called `CNAME` containing just the
   domain, e.g. `harryhart.co.nz`. Commit and push it.
2. At your domain registrar, add four A records for the bare domain
   pointing at `185.199.108.153`, `185.199.109.153`,
   `185.199.110.153`, `185.199.111.153`, and a CNAME record for `www`
   pointing at `harryhartnz-hue.github.io`.
3. In the repo's Settings → Pages, tick "Enforce HTTPS" once the
   certificate is issued (can take up to an hour).

## Editing it yourself

Everything is plain HTML/CSS, so you can open the files in any code
editor (VS Code is a good free option) and change text directly in the
`.html` files. Shared colors, fonts and spacing all live in
`css/style.css`, so changing a value there updates every page.
