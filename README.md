# Café de' Mercanti, a concept redesign

A UI and UX exercise: a one-page website for an Italian espresso bar in Old Montreal,
designed and built by hand.

**Live:** https://cafe-de-mercanti.vercel.app

> This is an unofficial concept. It is not affiliated with Café de' Mercanti. Menu, prices,
> hours and reviews on the page are placeholders written for the design.

## What's in it

- **Hero** with a full-bleed photo, the address line and two clear calls to action.
- **Story section** in two columns, with four short facts instead of a wall of text.
- **Menu as a slider**: four tabs (Caffè, Bevande, Dolci, Pranzo), dots, swipe on touch,
  and auto-advance that pauses while you hover.
- **Quote divider** with a light parallax on scroll.
- **Specials** as image cards, sample **reviews**, and a photo **gallery** grid.
- **Visit section** where today's opening hours highlight themselves, next to an embedded map.
- **Mobile navigation** with a burger menu, plus a nav bar that pins after you scroll.
- **Scroll reveals** using an `IntersectionObserver`, so sections fade in as they arrive.

## Design

Bodoni Moda for headings and Inter for text. The palette is coffee-toned:
espresso `#1c1410`, crema `#f5efe6`, parchment `#faf7f2` and a copper accent `#b87333`.

## Stack

Plain HTML, CSS and vanilla JavaScript. No framework and no build step. Deployed on Vercel
as a static site.

```
index.html       the page and its script
style.css        every style, with colour tokens at the top
images/photos/   the photos the page uses, as WebP
```

Photos are from Unsplash, saved as WebP in `images/photos/` so they cannot disappear. The
other files in `fonts/` and `images/` are from early iterations and are not used by the page.

## Run it

Open `index.html` in a browser, or serve the folder:

```
npx serve .
```

## Credits

Photos from [Unsplash](https://unsplash.com). Design and code by
[Abhinav Yadav](https://yabhinav.dpdns.org).
