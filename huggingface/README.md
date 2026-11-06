---
license: cc-by-4.0
language:
- en
pretty_name: Website Design Statistics 2026
size_categories:
- n<1K
task_categories:
- tabular-classification
tags:
- web-design
- typography
- ui-design
- saas
- design-systems
- landing-pages
configs:
- config_name: default
  data_files: website-design-statistics-2026.csv
---

# Website Design Statistics 2026

Headline size, fonts, body text, dark mode, gradients and buttons, measured on the homepages of **196 SaaS and AI companies** in November 2026.

**Source and full write-up with charts:** [Website Design Statistics 2026, BrowserMoon](https://www.browsermoon.com/blog/website-design-statistics)

## Key findings

- Median homepage headline: **64px**, **6 words**, line height **1.08**; 75% use negative letter spacing (about -0.025em).
- **84%** of headlines use a brand's own or a less common font. Inter: 9%. Geist: 5%. Serif: 5%.
- Body text: median about **18px**; half of sites use 18px or more.
- **36%** of homepages are dark (SaaS 37%, AI companies 33%). **53%** use a gradient in the first screen.
- Main button: median **46px** tall; slightly rounded 45%, pill 29%, square 8%; blue 29%, white 22%, black 21%.
- "Get started" is the most common button text (21%).

## Columns

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

## Method

Homepages of 218 SaaS and AI companies were loaded in a desktop browser at 1440×900 in November 2026. 22 were excluded because they blocked automated visits or did not load, leaving 196 (121 SaaS, 75 AI). The headline is the first visible H1, or the largest text when there is none.

## Citation

> Website Design Statistics 2026, BrowserMoon. https://www.browsermoon.com/blog/website-design-statistics

Also on GitHub: https://github.com/sparow-svg/website-design-statistics
