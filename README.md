# top10carshippers.com

Independent editorial site reviewing US auto transport companies.

## Stack
- Static HTML, single shared `styles.css`
- Hosted on Netlify, deployed automatically from this repo (main branch)

## Structure
```
/                                     site root
├── index.html                        homepage
├── styles.css                        shared stylesheet
├── top-7-car-shipping-companies.html main list
├── best-for-first-time-shippers.html sub-list
├── best-for-cross-country.html       sub-list
├── roadrunner-auto-transport-review.html
├── broker-vs-carrier.html            vetting reference
├── fmcsa-checklist.html              vetting reference
├── verify-a-car-shipping-company.html  vetting reference
├── common-auto-transport-scams.html  vetting reference
├── robots.txt
├── sitemap.xml
├── favicon.png
├── netlify.toml
└── blog/
    ├── lowest-quote-trap.html
    ├── damage-claims.html
    └── open-vs-enclosed.html
```

## Editing
- Style changes go in `styles.css` (one place, applies to all pages)
- Content changes go in the relevant HTML file
- Push to `main` to deploy

## Maintained by
MtoM Consulting on behalf of RoadRunner Auto Transport.
