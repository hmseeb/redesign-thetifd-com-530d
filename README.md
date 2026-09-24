# Texas Independent Funeral Directors — Website Redesign

A complete, ground-up redesign of thetifd.com built with vanilla HTML, CSS, and JavaScript.
No build step, no frameworks, no external APIs or environment variables.

## Business

**Texas Independent Funeral Directors LLC (TIFD)**
Licensed service infrastructure for Texas families and funeral professionals.

- **24/7 assistance:** (713) 255-2063
- **Email:** Info@TheTIFD.com (complaints: Admin@TheTIFD.com)
- **Address:** 13314 Almeda Rd, Houston, TX 77045

## Files

| File | Purpose |
| --- | --- |
| `index.html` | Single-page entry point with semantic markup, meta/Open Graph tags, JSON-LD `FuneralHome` schema, and an inline SVG favicon placeholder |
| `styles.css` | Design system (custom properties), responsive layout, and all component styles |
| `script.js` | Mobile nav, sticky header, scroll reveal, scroll-spy nav highlighting, obituary search handling, footer year |

## Sections

1. **Utility bar + sticky header** — 24/7 phone line and portal access always reachable
2. **Hero** — brand promise, dual CTAs (families / directors), core pillars, immediate-need card
3. **Four paths** — Families, Funeral Directors, Trade Partners, The Casket Store
4. **What TIFD provides** — coordinated infrastructure: family intake, licensed director access, trade coordination, compliance records
5. **Process** — five-step path from first contact to case close
6. **Obituaries** — search and memorial information
7. **Contact** — call, email, and visit cards with directions
8. **Footer** — family/professional link groups, contact block, social profiles, legal links

## Design notes

- Deep ink and teal palette drawn from the TIFD brand mark, paired with a warm sand neutral
- Serif display typography over a system sans body stack for a calm, dignified tone
- Mobile-first responsive layout with a floating "Call 24/7" action on small screens
- Accessibility: skip link, visible focus rings, ARIA labelling, `prefers-reduced-motion` support, print styles

## Running locally

Open `index.html` directly in a browser, or serve the directory:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000
