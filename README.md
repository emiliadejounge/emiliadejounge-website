# emiliadejounge.com

A from-scratch rebuild of your personal site — plain HTML/CSS/JS, no build
step, no framework. Open `index.html` in a browser and it just works.

## Structure

```
index.html        all page content
css/styles.css    all styling
js/main.js        scroll header, mobile nav, active-link highlight, reveal animation
images/           drop photos here (see images/README.md)
```

## Editing content

Everything is in `index.html` — bio text, job history, interests, links.
Search for the text you want to change and edit it directly; no templating,
no data files.

To add or remove a job from the "Work" timeline, copy one `<details class="role">…</details>`
block and edit its contents.

## Adding your photos

See [images/README.md](images/README.md) for the exact filenames the page
expects. Until you add them, every photo slot shows a solid color instead of
a broken image — the site looks intentional either way.

## Previewing locally

Just open `index.html` in a browser. If you want a local server (for testing
on your phone on the same wifi, etc.):

```bash
python3 -m http.server 8000
```

then visit `http://localhost:8000`.

## Deploying

Any static host works. Two easy options:

**Netlify Drop** — go to https://app.netlify.com/drop and drag this whole
folder in. You get a live URL instantly; connect your `emiliadejounge.com`
domain from the Netlify dashboard afterward (Domain settings → Add custom
domain, then update your domain's DNS as instructed).

**GitHub Pages** — push this folder to a GitHub repo, then in the repo's
Settings → Pages, set the source to your main branch. Point your domain's
DNS at GitHub Pages (see GitHub's "Managing a custom domain" docs) and add a
`CNAME` file here containing `emiliadejounge.com`.

Either way, you'll update your domain's DNS records at wherever you
currently manage `emiliadejounge.com` (likely Google Domains/Squarespace
Domains or your registrar) — that part isn't something I can do for you
since it requires access to your domain account.
