# Sales Intelligence Dashboard 2026

An interactive sales dashboard built from `Module5_Sales_Data_2026.xlsx` (1,271 sales lines, January–June 2026).

## Features
- Six headline figures: revenue, orders, units, average order value, returning-customer share, online share
- Filters: Province, Category, Channel, Customer type
- Charts: revenue by month, product, category, province, day of week, channel and customer mix
- Sortable product performance table
- Key insights that update with the filters
- Light and dark theme, works on phones

## Pages
| Page | File | Sections |
|---|---|---|
| Home (dashboard) | `index.html` | overview, filters, kpis, monthly, insights, products, categories, provinces, mix, weekdays, product-table, notes |
| Services | `services.html` | intro, analysis, features, use-cases |
| About | `about.html` | intro, project, data, how-built, definitions |
| Contact | `contact.html` | intro, creator, channels, links |
| Sitemap | `sitemap.html` | every page and section above, with links |

Shared styles for the four inner pages live in `site.css`.

## Tech
A static site in plain HTML, CSS and JavaScript. No build step and no dependencies. The sales data is embedded in the page.

## Run locally
Open `index.html` in any browser.

## Deploy on Vercel
1. Import this repository at https://vercel.com/new
2. Framework Preset: **Other**. Leave Build Command and Output Directory empty.
3. Click **Deploy**.
