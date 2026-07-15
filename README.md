# ☕ Coffee, from the inside

An interactive visual guide to coffee drinks. Hover over a cup and it **breaks apart into its layers** — espresso, steamed milk, foam, chocolate — with proportions annotated (e.g. cappuccino: ⅓ espresso, ⅓ milk, ⅓ foam).

Pure HTML + CSS + JS. No frameworks, no build step.

## Features

- **16 drinks**, each in its real vessel: espresso in a demitasse, cortado in a gibraltar glass, latte in a tall footed glass, irish coffee in a footed goblet, affogato in a coupe (with an ice-cream scoop), iced latte and dalgona in cold tumblers, espresso tonic in a highball (bubbles + lemon wheel), einspänner in a handled glass, nitro cold brew poured like a stout…
- **Trait icons** on every card: hot/iced, intensity (beans) and sweetness (sugar cubes)
- **Appetizing volumetric rendering** — hand-drawn SVG with elliptical liquid surfaces, crema/foam textures (procedural turbulence), glass sheen, warm light, animated steam, and barista details on top (cocoa dust, latte-art heart, rosetta, chocolate drizzle)
- **Break-apart interaction** — layers float up as creamy discs with spring easing, labels draw in, siblings blur out; 3D tilt and cursor spotlight
- **Proportion bars** on every card for a glanceable recipe
- **i18n** — English by default, Português (BR) and Deutsch via the top-right switcher
- Keyboard accessible (tab + focus breaks the cup), touch support (tap toggles), respects `prefers-reduced-motion`

## Run locally

```sh
python3 -m http.server 4173
# open http://localhost:4173
```

## Files

| File | What it is |
|---|---|
| `index.html` | The final site — grid panel of all drinks with rich rendering |
| `variacao-1.html` | Prototype 1 — light exploded-diagram grid |
| `variacao-2.html` | Prototype 2 — dark theme, ceramic cup splits in half |
| `variacao-3.html` | Prototype 3 — full-screen editorial accordion panels |
| `variacao-4.html` | Prototype 4 — grid with custom vessels + i18n |
| `variacao-5.html` | Prototype 5 — single-stage hero with vessel morphing & liquid pour |

Proportions are approximate — every barista has their own.
