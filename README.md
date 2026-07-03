# open-code

A collection of small, reusable, copy-paste code snippets by [Unfoldcro](https://www.unfoldcro.com) — mostly for **Shopify** and **WordPress** stores. Grab what you need, drop it into your theme, and tweak the marked variables.

## Snippets

| File | Platform | What it does |
| --- | --- | --- |
| [`Gradient Heading Custom`](./Gradient%20Heading%20Custom) | Any / HTML | Animated "Aurora" gradient heading. Set colors and speed via `data-colors` and `data-speed` attributes; accessible (screen-reader label included). |
| [`Whatsapp icon`](./Whatsapp%20icon) | WordPress · Shopify | Fixed floating WhatsApp chat button that opens a chat to your number. |
| [`milestone functionality`](./milestone%20functionality) | Shopify (Liquid) | Cart progress / free-shipping milestone bar with up to 3 reward tiers, price or quantity mode, and theme-editor settings. |
| [`Custom Shopify Font`](./Custom%20Shopify%20Font) | Shopify | Reference link for adding custom fonts to the Vision theme. |
| [`ufccredit.js`](./ufccredit.js) | Any / JS | Branded console credit banner (Unfoldcro ASCII art + tagline). |

## Usage

Each file is self-contained. General placement:

- **Shopify** → Online Store → Themes → **Edit code**. Liquid snippets (e.g. `milestone functionality`) go in a snippet/section; JS/HTML goes in `theme.liquid` before `</head>` or `</body>`.
- **WordPress / Elementor** → Custom Code / theme `<head>` (see the comment at the bottom of each file for the exact spot).

Every snippet has inline comments marking the values you should replace (WhatsApp number, brand colors, milestone targets, etc.). Read the comments before pasting.

## License

Open source — free to use and adapt. Attribution appreciated but not required.

---

Built and maintained by [Unfoldcro](https://www.unfoldcro.com) — Shopify Development · Speed Optimization · Custom Builds.
