# 1
Key HR Website Revisioning
# Key HR Corporate Website (`keyhro.com`)

Welcome to the official repository and content governance guide for **Key HR (`keyhro.com`)**. This README serves as the single source of truth for developers, designers, and content contributors managing the redesigned Key HR web presence.

---

## 1. Brand Identity & Core Positioning

**Tagline:** *Human Capital, Upgraded.*

**Who We Are:**
Key HR is an **ESAC-accredited, nationwide Professional Employer Organization (PEO)** operating across all 50 states. Founded 10 years ago by seasoned industry veterans, Key HR was built to solve the common frustrations businesses face with traditional providers—replacing impersonal call centers and rigid software with radical transparency, dedicated Subject Matter Experts (SMEs), and enterprise-grade HCM infrastructure.

### Critical Positioning Guardrails (Strict Enforcement)
* **True Single-Source PEO:** Key HR operates as a direct, nationwide co-employment PEO (alongside ASO and Key Connect offerings). **Never** describe Key HR as a "PEO broker," "master aggregator," or "third-party alignment organization."
* **White-Glove Service Model:** Always emphasize direct access to dedicated Subject Matter Experts (SMEs) across payroll, HR, benefits, and risk management—never automated ticket queues or 1-800 call centers.
* **Key Credentials & Trust Signals:**
  * **ESAC Accredited** (Employer Services Assurance Corporation — the gold standard for PEO financial stability, ethical conduct, and operational compliance).
  * **3x Inc. 5000 Honoree** (Recognized three times among America's fastest-growing private companies).
  * **50-State Coverage** (Seamless multi-state payroll, tax administration, compliance, and risk management).
  * **National Affiliations:** Active member of **NAPEO** (National Association of Professional Employer Organizations), **IFA** (International Franchise Association), **SHRM** (Society for Human Resource Management), and premier nationwide trade associations.

---

## 2. Site Architecture & Core Pages

### Core Navigation & Solution Pages
* **Home (`/`)**
  * Hero positioning (*"Human Capital, Upgraded"*), interactive solution highlights, unified HCM technology overview, white-glove client service callouts, and comprehensive business assessment CTA.
* **Solutions Overview & Core Pillars**
  * **Payroll & Tax Administration:** Multi-state payroll processing, tax filing, W-2s, garnishments, and integrated timekeeping.
  * **HR & Regulatory Compliance:** Proactive protection across FLSA, FICA, FUTA/SUTA, OSHA, EEO, ACA, FMLA, and COBRA.
  * **Risk Management & Workers' Compensation:** A-rated nationwide coverage, Pay-As-You-Go policies, workplace safety programs, site surveys, OSHA reporting, and active claims management.
  * **Employee Benefits:** Custom major medical and life insurance, no-cost ancillary options (dental, vision, 401(k), HSA, FSA), electronic onboarding, and turnkey open enrollment/ACA administration.
  * **Workforce Technology & Add-On Tools:** Powered by our cloud-based HCM infrastructure delivering 24/7 Employee Self-Service, Manager Approvals & Analytics, Time & Attendance, Applicant Tracking (ATS), LMS, E-Verify, and Background/Drug Screening.
* **Industries We Serve (`/industries`)**
  * Strategic, tailored workforce solutions built around the specific operational workflows, labor laws, and safety risks of key sectors—including a dedicated **Franchise Resource Portal**.
* **About Us (`/about`)**
  * The 10-year Key HR origin story, Mission/Vision/Values, Executive Leadership overview, ESAC & Inc. 5000 credentials, and national affiliations.
* **Channel Partners & Brokers (`/partners`)**
  * 6-step non-competing referral workflow, Dedicated Partner Manager commitment, and separated **Broker Submission** vs. **Direct Client Quote** routing.
* **Careers (`/careers`)**
  * *"Life at Key HR: Where People Come First"* culture overview and open role listings.
* **Resources, Interactive Tools & Competitor Comparisons**
  * **Interactive Calculators (`/tools`):** PEO ROI Calculator, True Employee Cost Calculator, Workers' Comp Estimator, Payroll Tax Calculator, and HR Compliance Audit.
  * **Competitor Comparison Pages:** Direct PEO comparison landing pages (`/gusto-alternative`, `/rippling-alternative`, `/justworks-alternative`, `/adp-totalsource-alternative`, `/trinet-alternative`, `/deel-alternative`, `/vensurehr-alternative`, `/coad-alternative`, `/coadvantage-alternative`, `/vensure-alternative`, `/decisionhr-alternative`, `/prestigepeo-alternative`, `/frankcrum-alternative`, `/alphastaff-alternative`, `/peoplease-alternative`, `/deel-alternative`, `/paychex-alternative`, `/alcotthr-alternative`, `/questco-alternative`, `/engagepeo-alternative`).
  * **Media & Insights Hub:** Consolidated blog articles, downloadable HR compliance guides, and company news.

---

## 3. UI/UX & Content Standards

* **Portal & Login Cleanliness:** All client and employee portal links must reflect unified Key HR Workforce Management branding. Do not expose raw third-party vendor logos or legacy partner login clutter on public-facing portal gateways.
* **Submission Routing:** Maintain strict separation between the **Direct Business Assessment / Quote Questionnaire** (for prospective clients) and the **Partner / Broker Submission Packet** page (for referral partners) to prevent cross-linking loops.
* **Brand Palette & Styling:**
  * Primary Brand Accent: Key HR Crimson Red (`#990000` / `#A30000`)
  * Clean, high-contrast executive typography paired with scannable feature grids and clear, action-oriented CTAs.
* **Lead Capture & CRM Governance:** All web forms, interactive tool completions, and broker submissions must route cleanly into **Salesforce** (the organization's system of record) with complete source attribution.

---

## 4. Pre-Deployment & Publishing QA Checklist

Before pushing page updates or layout changes live to `keyhro.com`:
- [ ] Verify all copy reflects Key HR as a **true, ESAC-accredited nationwide PEO** (zero aggregator/broker terminology).
- [ ] Confirm separated routing between Direct Quote forms and Broker/Partner Submission forms.
- [ ] Test mobile responsiveness across all interactive calculators and multi-column service grids.
- [ ] Validate that all form submissions map accurately to Salesforce lead/opportunity fields.
- [ ] Check all meta titles, OpenGraph tags, and schema markup across core solution and comparison pages.

---

## 5. Contact & Ownership

* **Domain:** [https://keyhro.com](https://keyhro.com)
* **Headquarters:** Orlando, Florida (Serving Clients Nationwide Across All 50 States)
* **Ownership:** Key HR Executive & Sales Leadership Team
