**Live site:** [https://key-hr.github.io/1/](https://key-hr.github.io/1/)

# Key HR Corporate Website

**Key HR website revisioning** for [keyhro.com](https://keyhro.com)

This repository holds the redesigned Key HR website and serves as its content governance guide. This README is the single source of truth for developers, designers and content contributors managing the redesigned Key HR web presence.

| | |
|---|---|
| **Live preview** | [key-hr.github.io/1](https://key-hr.github.io/1/) |
| **Production domain** | [keyhro.com](https://keyhro.com) |
| **Site file** | [`index.html`](index.html) (single-file site with in-page routing) |
| **Error page** | [`404.html`](404.html) (shown for any missing page) |

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

### Core Navigation and Solution Pages

#### Home (`/`)

Hero positioning (*"Human Capital, Upgraded"*), interactive solution highlights, unified HCM technology overview, white-glove client service callouts and comprehensive business assessment CTA.

#### Solutions Overview and Core Pillars

- **Payroll and Tax Administration:** Multi-state payroll processing, tax filing, W-2s, garnishments and integrated timekeeping.
- **HR and Regulatory Compliance:** Proactive protection across FLSA, FICA, FUTA/SUTA, OSHA, EEO, ACA, FMLA and COBRA.
- **Risk Management and Workers' Compensation:** A-rated nationwide coverage, pay-as-you-go policies, workplace safety programs, site surveys, OSHA reporting and active claims management.
- **Employee Benefits:** Custom major medical and life insurance, no-cost ancillary options (dental, vision, 401(k), HSA, FSA), electronic onboarding and turnkey open enrollment and ACA administration.
- **Workforce Technology and Add-On Tools:** Powered by our cloud-based HCM infrastructure, delivering 24/7 employee self-service, manager approvals and analytics, time and attendance, applicant tracking (ATS), LMS, E-Verify and background and drug screening.

#### Industries We Serve (`/industries`)

Strategic, tailored workforce solutions built around the specific operational workflows, labor laws and safety risks of key sectors, including a dedicated **Franchise Resource Portal**.

#### About Us (`/about`)

The 10-year Key HR origin story, mission, vision and values, executive leadership overview, ESAC and Inc. 5000 credentials, and national affiliations.

#### Channel Partners and Brokers (`/partners`)

Six-step non-competing referral workflow, dedicated Partner Manager commitment, and separated **Broker Submission** and **Direct Client Quote** routing.

#### Careers (`/careers`)

*"Life at Key HR: Where People Come First"* culture overview and open role listings.

### Resources, Interactive Tools and Competitor Comparisons

#### Interactive Calculators (`/tools`)

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

#### Media and Insights Hub

Consolidated blog articles, downloadable HR compliance guides and company news.

---

## 3. UI/UX and Content Standards

- **Portal and login cleanliness:** All client and employee portal links must reflect unified Key HR Workforce Management branding. Do not expose raw third-party vendor logos or legacy partner login clutter on public-facing portal gateways.
- **Submission routing:** Maintain strict separation between the **Direct Business Assessment / Quote Questionnaire** (for prospective clients) and the **Partner / Broker Submission Packet** page (for referral partners) to prevent cross-linking loops.
- **Brand palette and styling:**
  - Primary brand accent: Key HR Crimson Red (`#990000` / `#A30000`)
  - Clean, high-contrast executive typography paired with scannable feature grids and clear, action-oriented CTAs.
- **Lead capture and CRM governance:** All web forms, interactive tool completions and broker submissions must route cleanly into **Salesforce** (the organization's system of record) with complete source attribution.

---

## 4. Pre-Deployment and Publishing QA Checklist

Before pushing page updates or layout changes live to [keyhro.com](https://keyhro.com):

- [ ] Verify all copy reflects Key HR as a **true, ESAC-accredited nationwide PEO** (zero aggregator or broker terminology).
- [ ] Confirm separated routing between Direct Quote forms and Broker/Partner Submission forms.
- [ ] Test mobile responsiveness across all interactive calculators and multi-column service grids.
- [ ] Validate that all form submissions map accurately to Salesforce lead and opportunity fields.
- [ ] Check all meta titles, OpenGraph tags and schema markup across core solution and comparison pages.

---

## 5. Contact and Ownership

| | |
|---|---|
| **Domain** | [keyhro.com](https://keyhro.com) |
| **Headquarters** | Orlando, Florida (serving clients nationwide across all 50 states) |
| **Ownership** | Key HR Executive and Sales Leadership Team |
