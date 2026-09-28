# dazo — websites, bots and automation

[![Website](https://img.shields.io/badge/website-fyosamu.github.io-4dd4ac?style=flat-square)](https://fyosamu.github.io/)
[![Price](https://img.shields.io/badge/from-%24450%20fixed-7aa2ff?style=flat-square)](https://fyosamu.github.io/pricing/)
[![Payment](https://img.shields.io/badge/payment-USDT%20%7C%20BEP--20%20%C2%B7%20ERC--20-ffb454?style=flat-square)](https://fyosamu.github.io/#contact)
[![Referral](https://img.shields.io/badge/referral-15%25%20of%20fee-4dd4ac?style=flat-square)](https://fyosamu.github.io/partners/)

The source of **[fyosamu.github.io](https://fyosamu.github.io/)** — the public site for **dazo**, a one-person remote build studio.

This repository is the whole site: plain static HTML, no framework, no build step, no dependencies. It deploys on GitHub Pages.

---

## What dazo builds

| Service | Price | Turnaround |
|---|---|---|
| Custom website (theme or fully bespoke) | **$750 – $2,500** | 3–7 days |
| Existing website → Android / iOS app | **$1,000 – $3,200** | 4–8 days |
| Telegram or Discord bot | **$600 – $1,800** | 2–5 days |
| AI workflow automation | **$900 – $3,000** | 3–7 days |
| Technical SEO audit and fixes | **$500 – $1,500** | scoped per site |
| Speed optimisation (Core Web Vitals) | **$400 – $1,200** | 1–3 days |
| Care plan — updates, backups, fixes | **$150 – $400 / mo** | ongoing |

Prices are **fixed-scope and published up front**. No discovery call needed to see a number.

Payment in **USDT** — BEP-20 or ERC-20 only (never TRC-20).

---

## Free tools

Two calculators that live on the site. Both run entirely in the browser — no tracking, no email gate, nothing sent anywhere.

- **[Website cost calculator](https://fyosamu.github.io/tools/website-cost-calculator/)** — scope in, price out in USD and USDT, with the typical market range for comparison.
- **[Telegram bot cost calculator](https://fyosamu.github.io/tools/telegram-bot-cost-calculator/)** — features and message volume in, build price and monthly hosting out.

Both are **also open source**: **[github.com/Fyosamu/dazo-cost-calculators](https://github.com/Fyosamu/dazo-cost-calculators)** — MIT, one HTML file each, no dependencies. Fork it, change one price table, host it yourself.

---

## Pages

| Path | Purpose |
|---|---|
| `/` | Home, service overview, contact |
| `/pricing/` | **The complete published price list** — order by email |
| `/web-development/` | Custom website builds |
| `/website-to-app/` | Turn an existing site into an app |
| `/telegram-bot-development/` | Bots for Telegram and Discord |
| `/ai-automation/` | AI workflow automation and SaaS integrations |
| `/technical-seo/` | Technical SEO audit, schema, crawlability and fixes |
| `/speed-optimization/` | Speed optimisation and Core Web Vitals work |
| `/website-care-plan/` | Care plan — backups, patches, monitoring, support |
| `/partners/` | Referral program — keep **15%** of the fee |
| `/tools/website-cost-calculator/` | Free website pricing tool |
| `/tools/telegram-bot-cost-calculator/` | Free bot pricing tool |
| `/llms.txt` | AI-crawler summary of the whole site |
| `/assets/resume.pdf` | Stable, linkable CV URL |

---

## Running it locally

There is nothing to build. Serve the `portfolio/` directory with any static server:

```bash
cd portfolio
python -m http.server 8080
# open http://localhost:8080
```

## Structure

```
portfolio/
├── index.html                          home
├── robots.txt                          crawl rules + sitemap + llms.txt pointer
├── sitemap.xml                         all indexable URLs
├── indexnow-key.txt                    IndexNow verification
├── llms.txt                            AI-crawler summary of the site
├── assets/
│   ├── og-card.jpg                     social share image (1200×630)
│   └── resume.pdf                      published CV
├── web-development/                    service page
├── website-to-app/                     service page
├── telegram-bot-development/           service page
├── ai-automation/                      service page
├── technical-seo/                      service page
├── speed-optimization/                 service page
├── website-care-plan/                  service page
├── partners/                           referral program
├── pricing/                            complete published price list
└── tools/
    ├── website-cost-calculator/        free tool
    └── telegram-bot-cost-calculator/   free tool
```

Every page carries Open Graph and Twitter Card tags, a canonical URL, and JSON-LD structured data (`Service`, `WebApplication`, `FAQPage`).

---

## Partner program

Send work dazo's way and keep **15% of the fee** — no cap, no exclusivity, no minimum volume.
Details: **[fyosamu.github.io/partners/](https://fyosamu.github.io/partners/)**

---

## Contact

**[fyosamu.github.io/#contact](https://fyosamu.github.io/#contact)** · GitHub: [@Fyosamu](https://github.com/Fyosamu)
