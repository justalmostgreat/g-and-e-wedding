# Gabrielle & Ernesto, Wedding Site

Live invitation site, published with GitHub Pages:
https://gabbyandernesto.com/

## Structure
- `index.html` : "coming soon" placeholder (only the Save the Date is out). To launch the main site, rename `home.html` back to `index.html`.
- `home.html` : the main site (envelope intro, our story, schedule, travel, stay, things to do, FAQ). Bilingual EN/ES.
- `designs/` : five clickable design directions to choose from.
- `images/` : optimized photos (hero, portrait, embrace, night, ring).
- `save-the-date/` : the Save the Date (sealed envelope opens, card slides out). The tap that opens it starts the song, with a mute button in the corner.
- `audio/` : `gema.mp3` (Gema, Los Dandys), the Save the Date song.

## Editing
Everything lives in `index.html` (single file). To update:

```
git add -A && git commit -m "your message" && git push
```

GitHub Pages redeploys automatically in about a minute.

## Still to fill in
- RSVP button destination (a WithJoy link or a Google Form).
- RSVP deadline date (currently shows "date to be confirmed").

The page is set to `noindex`, so it will not appear in search engines.
