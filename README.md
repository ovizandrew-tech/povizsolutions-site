# Poviz Solutions website

Company website for **povizsolutions.com**, hosted on Netlify (publishes this folder as-is, no build step).

## Pages
- `/` home: overview, products, recent work, how we work
- `/pos/` Poviz Hub POS (available)
- `/estate/`, `/guard/`, `/minutedesk/` products in development (register interest)
- `/solutions/` overview of other products and services
- `/websites/`, `/data/` services
- `/work/` Vita Fruity case study
- `/about/`, `/contact/` (demo request form), `thanks.html`

## Style
Shared styles in `assets/site.css`: navy, white and grey with one blue accent (#1E6BF0), sharp 4px corners, one-colour logo.

## Forms
The demo request form on `/contact/` uses Netlify Forms (form name: `demo-request`).
Product pages link to `/contact/?interest=pos|estate|guard|minutedesk|web|data|other` to preselect the interest.
