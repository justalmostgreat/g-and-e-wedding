# Gabrielle & Ernesto — Wedding Site

Live invitation site. Published with GitHub Pages.

## Add the photos
Drop the real photos into `images/` with these exact names (the site already points to them):

- `images/couple-1.jpg` — the couple walking (used in the hero + link preview)
- `images/couple-2.jpg` — the hands / engagement close-up

Until they're added, those spots show a soft floral placeholder. After adding, commit & push:

```
git add images && git commit -m "Add photos" && git push
```

## Edit content
Everything lives in `index.html` (single file). Names are real; the **RSVP link** and the
**RSVP deadline date** are placeholders to fill in. Site is bilingual (EN/ES toggle in the nav)
and set to `noindex` so it won't show up in Google searches.
