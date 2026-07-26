# Vortex Tech — Week 1: Personal Portfolio Page

A single-page personal portfolio built with plain HTML and CSS as part of the
Vortex Tech Web Development Internship Track (Week 1).

## What's included

- **Header** — name and title, set against a subtle node/graph pattern.
- **About** — a short bio.
- **Skills** — a Flexbox-based chip layout, listing core technical skills.
- **Contact** — email and social links.

## Structure

```
portfolio-week1/
├── index.html   # page structure (semantic HTML5: header, section, footer)
├── style.css    # all styling — colors, typography, Flexbox layout, media query
└── README.md
```

## Design

- **Colors:** deep navy background (`#12141c`) with panel tones, a teal accent
  (`#5eead4`) for emphasis and links, and a warm amber (`#f5a623`) used
  sparingly on hover states.
- **Type:** Space Grotesk for headings, Inter for body text, JetBrains Mono
  for labels and small tags.
- **Layout:** Flexbox is used for the skills list (wrapping chips) and for
  each section's label/content split.
- **Responsive:** a `max-width: 600px` media query stacks sections vertically
  and switches the contact links to a single column for small screens.

## How to run it

No build step required.

1. Clone or download this repository.
2. Open `index.html` directly in any modern browser (double-click it, or
   right-click → "Open with" your browser).

To edit content, update the text in `index.html` (name, bio, skills, contact
links) — replace the placeholder name, email, and social links with your own.

---
Vortex Tech · Web Development Internship Track · Week 1 of 4