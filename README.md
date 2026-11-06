# Website design statistics 2026

Headline size, fonts, body text, dark mode, gradients and buttons, measured on the homepages of **196 SaaS and AI companies** in November 2026.

Full write-up with charts and screenshots: **[Website Design Statistics 2026 on BrowserMoon](https://www.browsermoon.com/blog/website-design-statistics)**

## Key findings

| Measure | Typical homepage (median) |
|---|---|
| Headline size | 64px (middle half: 52 to 72px) |
| Headline length | 6 words (82% use 8 or fewer) |
| Headline line height | 1.08 |
| Headline letter spacing | tight, about -0.025em (75% of sites) |
| Body text size | about 18px (half use 18px or more) |
| Main button height | 46px (middle half: 40 to 51px) |
| Navigation bar height | 72px |

- **84%** of headlines use a brand's own or a less common font. Inter: 9%. Geist: 5%. Serif headlines: 5%.
- **36%** of homepages are dark (SaaS 37%, AI companies 33%).
- **53%** use a gradient in the first screen.
- Main button shape: slightly rounded (3–8px) 45%, pill 29%, rounded (9px+) 18%, square 8%.
- Main button colour: blue 29%, white 22%, black 21%, purple 7%.
- "Get started" is the most common button text (21% of buttons include it). 30% mention "free", 9% ask for a demo.

## The data

[`website-design-statistics-2026.csv`](website-design-statistics-2026.csv), one row per site:

| Column | Meaning |
|---|---|
| `site` | Domain |
| `category` | `saas` or `ai` |
| `headline_font` | First font in the headline's font stack |
| `headline_px` | Rendered headline size at 1440×900 |
| `headline_weight` | Font weight |
| `headline_letter_spacing` | Computed letter spacing |
| `headline_words` | Words in the headline |
| `body_px` | First body paragraph size |
| `dark_background` | Background behind the headline is dark |
| `gradient_in_first_screen` | Any CSS gradient in the first screen |
| `button_text`, `button_background`, `button_radius`, `button_height_px` | First filled button in the first screen, ignoring cookie banners and skip links |

## How it was measured

Homepages of 218 well-known SaaS and AI companies were loaded in a desktop browser at 1440×900 in November 2026. 22 were excluded because they blocked automated visits or did not load, leaving 196 (121 SaaS, 75 AI). The headline is the first visible H1, or the largest text when there is none. Sizes are as rendered at that screen size. Percentages are rounded.

## Use and citation

You are welcome to use this data in articles, talks and research. Please credit and link the source:

> Website Design Statistics 2026, BrowserMoon: https://www.browsermoon.com/blog/website-design-statistics

Licensed under [CC BY 4.0](LICENSE).

---

Made by [BrowserMoon](https://www.browsermoon.com), design templates for AI coding tools like Claude Code, Cursor, Lovable and Bolt.
