# balajipathipati.com

Personal website of Balaji Pathipati. Plain HTML + CSS, hosted free on GitHub Pages.

## Structure

```
index.html            Home page (name banner + photo)
assets/css/style.css  All styling; colours/fonts are tokens at the top
assets/img/balaji.jpg Profile photo (square crop works best, ~800x800px)
CNAME                 Tells GitHub Pages which domain to serve
```

## Update the site

Edit a file → commit → push to `main`. GitHub Pages republishes in ~1 minute.

## DNS (Namecheap → Advanced DNS)

| Type  | Host | Value               |
|-------|------|---------------------|
| A     | @    | 185.199.108.153     |
| A     | @    | 185.199.109.153     |
| A     | @    | 185.199.110.153     |
| A     | @    | 185.199.111.153     |
| CNAME | www  | balajipathipati.github.io. |

Delete Namecheap's default parking records (URL Redirect / CNAME to parkingpage) first.

## Roadmap

- [x] v1: name + photo (live)
- [ ] About section
- [ ] Contact / LinkedIn links
- [ ] Work / projects
- [ ] Writing / blog (consider migrating to Astro when this arrives)
