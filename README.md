**Live previews:** [https://key-hr.github.io/1/](https://key-hr.github.io/1/) and [https://scott-holding.github.io/keyhr2.0/](https://scott-holding.github.io/keyhr2.0/)

# Key HR Corporate Website

**Key HR website revisioning** for [keyhro.com](https://keyhro.com)

This repository holds the redesigned Key HR website and serves as its content governance guide. This README is the single source of truth for developers, designers and content contributors managing the redesigned Key HR web presence.

| | |
|---|---|
| **Live previews** | [key-hr.github.io/1](https://key-hr.github.io/1/) and [scott-holding.github.io/keyhr2.0](https://scott-holding.github.io/keyhr2.0/) |
| **Production domain** | [keyhro.com](https://keyhro.com) |
| **This version** | Version 2: design polish (see [Version History](#version-history)) |
| **Site file** | [`index.html`](index.html) (one page with in-page routing) |
| **Error page** | [`404.html`](404.html) (shown for any missing address, on any host) |

## Folder Structure

```
index.html            All page content (routes like #payroll, #about)
404.html              Error page for any missing address
assets/
  site.css            All styles
  site.js             Router, menus, animations, forms and reader
  spanish.js          Spanish translations used by the language toggle
  images/             Logo, hero, leadership headshots and community photos
  forms/              Client forms and legal update packets (PDF, English and Spanish)
pages/                Clean links for each page (for example pages/payroll.html opens #payroll)
sitemap.xml           Search engine page list
robots.txt            Search engine rules
```

Every page has a clean link in `pages/`, for example [key-hr.github.io/1/pages/payroll.html](https://key-hr.github.io/1/pages/payroll.html).

The site also works when opened directly from a computer: open `index.html` in any browser.

## Version History

| Version | What changed |
|---|---|
| **1. Baseline** | The site before this round of work. |
| **2. Design polish** (this version, live) | Visual and motion polish for phone and desktop. No wording or function changes. Details below. |
| **3. Redesign and reworded** (not live) | Version 2 plus plain-language copy on every page, one call-to-action system ("Get a free quote" / "Schedule a call"), search titles and descriptions for every page, social sharing tags and chat answer fixes. |

### What Version 2 Changed

- **Hover effects:** Card lifts appear only on devices with a mouse, only on cards you can click, and move a subtle 4px.
- **Animations:** Scroll reveals no longer flash content that is already on screen, tab and pulse animations are smoother, and finished animations release the page so it stays responsive.
- **Type and layout on phones:** A phone-sized type scale, buttons that fit narrow screens, a two-column footer, and a 50px chat button that stays out of the way.
- **Header and forms:** A near-solid header so text stays readable while scrolling, and a cleaner quote form layout.
- **Dark mode:** A lighter crimson (`#F2705F`) and darker tab styling so text and accents keep their contrast.
- **Font loading:** A matched fallback font, so the page doesn't jump when Poppins finishes loading.
- **Error page:** Works at any address, so its styles and links load on every live preview.

## Contents

1. [Brand Identity and Core Positioning](#1-brand-identity-and-core-positioning)
2. [Site Architecture and Core Pages](#2-site-architecture-and-core-pages)
3. [UI/UX and Content Standards](#3-uiux-and-content-standards)
4. [Pre-Deployment and Publishing QA Checklist](#4-pre-deployment-and-publishing-qa-checklist)
5. [Contact and Ownership](#5-contact-and-ownership)

---

## 1. Brand Identity and Core Positioning

**Tagline:** *Human Capital, Upgraded.*

### Who We Are

Key HR is an **ESAC-accredited, nationwide Professional Employer Organization (PEO)** operating across all 50 states. Founded 10 years ago by seasoned industry veterans, Key HR was built to solve the common frustrations businesses face with traditional providers, replacing impersonal call centers and rigid software with radical transparency, dedicated Subject Matter Experts (SMEs) and enterprise-grade HCM infrastructure.

### Critical Positioning Guardrails (Strict Enforcement)

- **True single-source PEO:** Key HR operates as a direct, nationwide co-employment PEO (alongside ASO and Key Connect offerings). **Never** describe Key HR as a "PEO broker," "master aggregator" or "third-party alignment organization."
- **White-glove service model:** Always emphasize direct access to dedicated Subject Matter Experts (SMEs) across payroll, HR, benefits and risk management, never automated ticket queues or 1-800 call centers.

### Key Credentials and Trust Signals

- **ESAC Accredited:** [Employer Services Assurance Corporation](https://www.esacorp.org), the gold standard for PEO financial stability, ethical conduct and operational compliance.
- **3x Inc. 5000 Honoree:** Recognized three times among America's fastest-growing private companies.
- **50-State Coverage:** Seamless multi-state payroll, tax administration, compliance and risk management.
- **National Affiliations:** Active member of [NAPEO](https://www.napeo.org) (National Association of Professional Employer Organizations), [IFA](https://www.franchise.org) (International Franchise Association), [SHRM](https://www.shrm.org) (Society for Human Resource Management) and premier nationwide trade associations.

---

## 2. Site Architecture and Core Pages

The site is one page (`index.html`) with in-page routes. Each route also has a clean link in `pages/`.

### Pages in This Build

| Page | Route | Clean link |
|---|---|---|
| Home | `#home` | `index.html` |
| Services and Solutions | `#services` | `pages/services.html` |
| Payroll | `#payroll` | `pages/payroll.html` |
| Human Resources | `#hr` | `pages/hr.html` |
| Compliance | `#compliance` | `pages/compliance.html` |
| Risk Management and Workers' Comp | `#risk` | `pages/risk.html` |
| Employee Benefits | `#benefits` | `pages/benefits.html` |
| PEO Services | `#peo` | `pages/peo.html` |
| Additional Solutions | `#additional-solutions` | `pages/additional-solutions.html` |
| Who We Serve | `#who-we-serve` | `pages/who-we-serve.html` |
| Comprehensive Assessment | `#approach` | `pages/approach.html` |
| Partnerships | `#brokers` | `pages/brokers.html` |
| Resources | `#resources` | `pages/resources.html` |
| Employment Law Updates | `#legal-updates` | `pages/legal-updates.html` |
| About Us | `#about` | `pages/about.html` |
| Careers | `#careers` | `pages/careers.html` |
| Client Center | `#client-center` | `pages/client-center.html` |
| W-2 Retrieval | `#w2` | `pages/w2.html` |
| Privacy Notice and Terms of Use | `#privacy` | `pages/privacy.html` |

### Core Navigation and Solution Pages

#### Home (`#home`)

Hero positioning (*"Human Capital, Upgraded"*), interactive solution highlights, unified HCM technology overview, white-glove client service callouts and comprehensive business assessment CTA.

#### Solutions Overview and Core Pillars

- **Payroll and Tax Administration:** Multi-state payroll processing, tax filing, W-2s, garnishments and integrated timekeeping.
- **HR and Regulatory Compliance:** Proactive protection across FLSA, FICA, FUTA/SUTA, OSHA, EEO, ACA, FMLA and COBRA.
- **Risk Management and Workers' Compensation:** A-rated nationwide coverage, pay-as-you-go policies, workplace safety programs, site surveys, OSHA reporting and active claims management.
- **Employee Benefits:** Custom major medical and life insurance, no-cost ancillary options (dental, vision, 401(k), HSA, FSA), electronic onboarding and turnkey open enrollment and ACA administration.
- **Workforce Technology and Add-On Tools:** Powered by our cloud-based HCM infrastructure, delivering 24/7 employee self-service, manager approvals and analytics, time and attendance, applicant tracking (ATS), LMS, E-Verify and background and drug screening.

#### Who We Serve (`#who-we-serve`)

Strategic, tailored workforce solutions built around the specific operational workflows, labor laws and safety risks of 16 key sectors.

#### About Us (`#about`)

The 10-year Key HR origin story, mission, vision and values, executive leadership overview, ESAC and Inc. 5000 credentials, and national affiliations.

#### Partnerships (`#brokers`)

Six-step non-competing referral workflow, dedicated Partner Manager commitment, and separated **Broker Submission** and **Direct Client Quote** routing.

#### Careers (`#careers`)

*"Life at Key HR: Where People Come First"* culture overview and open role listings.

#### Resources (`#resources`)

Blog articles, HR compliance guides and company news, with search and filters, plus Employment Law Updates (`#legal-updates`).

### Planned, Not in This Build

#### Interactive Calculators

- PEO ROI Calculator
- True Employee Cost Calculator
- Workers' Comp Estimator
- Payroll Tax Calculator
- HR Compliance Audit

#### Competitor Comparison Pages

Direct PEO comparison landing pages:

| Page | Page | Page |
|---|---|---|
| `/gusto-alternative` | `/rippling-alternative` | `/justworks-alternative` |
| `/adp-totalsource-alternative` | `/trinet-alternative` | `/deel-alternative` |
| `/vensurehr-alternative` | `/vensure-alternative` | `/coad-alternative` |
| `/coadvantage-alternative` | `/decisionhr-alternative` | `/prestigepeo-alternative` |
| `/frankcrum-alternative` | `/alphastaff-alternative` | `/peoplease-alternative` |
| `/paychex-alternative` | `/alcotthr-alternative` | `/questco-alternative` |
| `/engagepeo-alternative` | | |

#### Franchise Resource Portal

A dedicated resource hub for franchise clients.

### Search Engine Limit

Search engines ignore everything after `#` in an address, so every route's canonical link collapses to the home page and only the home page can rank today. To rank individual pages (Payroll, Workers' Comp, Benefits), each route needs its own HTML file at its own address (pre-rendering the routes).

---

## 3. UI/UX and Content Standards

- **Portal and login cleanliness:** All client and employee portal links must reflect unified Key HR Workforce Management branding. Do not expose raw third-party vendor logos or legacy partner login clutter on public-facing portal gateways.
- **Submission routing:** Maintain strict separation between the **Direct Business Assessment / Quote Questionnaire** (for prospective clients) and the **Partner / Broker Submission Packet** page (for referral partners) to prevent cross-linking loops.
- **Brand palette and styling:**
  - Poppins is the only typeface.
  - Logo red `#DF3726` (`--red`) for accents.
  - Button fill `#C82E1E` (`--red-fill`), deep enough for white text to pass WCAG AA.
  - Crimson `#990000` (`--crimson`) for light-mode hover states, and `#F2705F` in dark mode. Earlier versions of this guide listed `#990000` as the primary accent; confirm with Key HR whether to keep it.
  - Clean, high-contrast executive typography paired with scannable feature grids and clear, action-oriented CTAs.
- **Spanish:** The Español toggle swaps exact English text for entries in `assets/spanish.js`. Every English wording change needs a matching entry, or that text stays in English when Spanish is on.
- **Lead capture and CRM governance:** All web forms, interactive tool completions and broker submissions must route cleanly into **Salesforce** (the organization's system of record) with complete source attribution. In this preview build the quote and call forms are not connected yet.

---

## 4. Pre-Deployment and Publishing QA Checklist

Before pushing page updates or layout changes live to [keyhro.com](https://keyhro.com):

- [ ] Verify all copy reflects Key HR as a **true, ESAC-accredited nationwide PEO** (zero aggregator or broker terminology).
- [ ] Confirm separated routing between Direct Quote forms and Broker/Partner Submission forms.
- [ ] Test mobile responsiveness across all pages, forms and multi-column service grids.
- [ ] Validate that all form submissions map accurately to Salesforce lead and opportunity fields.
- [ ] Check all meta titles, OpenGraph tags and schema markup across every page.
- [ ] Switch the canonical links and `sitemap.xml` from `key-hr.github.io/1/` to `keyhro.com`.
- [ ] Add a Spanish entry for every English wording change, check it with the Español toggle, and have a native Spanish speaker review.

---

## 5. Contact and Ownership

| | |
|---|---|
| **Domain** | [keyhro.com](https://keyhro.com) |
| **Headquarters** | Orlando, Florida (serving clients nationwide across all 50 states) |
| **Ownership** | Key HR Executive and Sales Leadership Team |
