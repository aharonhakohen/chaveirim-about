# Chaveirim of Central Jersey — Official Information & Verification Site (`about.cjchaveirim.org`)

Permanent, zero-maintenance static website for **Chaveirim of Central Jersey** (legally incorporated as **Chaveirim Volunteer Services Inc.**, IRS 501(c)(3) EIN `43-1987913`), hosted at **`https://about.cjchaveirim.org`**.

## Purpose & Plain-English Overview
While root `cjchaveirim.org` forwards directly to the Banquest donation checkout (`https://pay.banquest.com/chaveirim`) for zero-click donor convenience, **`https://about.cjchaveirim.org`** serves as the permanent official public profile and compliance website for **Chaveirim of Central Jersey**:

- **For Residents & Motorists:** Quick tap-to-call access to the 24/7 hotline (`(732) 370-2229`), a breakdown of free volunteer roadside and community services, coverage areas across Central New Jersey, and a direct **Donate** button.
- **For Apple Business & Carrier / Twilio Verification:** Explicitly connects the public brand (**Chaveirim of Central Jersey**) with its verified legal nonprofit entity (**Chaveirim Volunteer Services Inc.**), registered address (`139 Carol Street, Lakewood, NJ 08701`), and primary 24/7 hotline (`(732) 370-2229`), alongside permanent `/privacy/` and `/terms/` pages.
- **Automatic System Theme:** Automatically adapts to each visitor's phone or computer Light/Dark system theme (`prefers-color-scheme`).

## Structure
- `index.html` — Official brand profile, services, coverage map tags, 24/7 hotline card, corporate details, and `EmergencyService` / `NGO` JSON-LD schema
- `privacy/index.html` — Official Privacy Policy (`https://about.cjchaveirim.org/privacy/`)
- `terms/index.html` — Official SMS & Communication Terms (`https://about.cjchaveirim.org/terms/`)
- `styles.css` — Responsive, system-theme-aware stylesheet
- `CNAME` — Custom domain binding (`about.cjchaveirim.org`)
- `robots.txt` — Crawler allow rules (`Applebot`, `Googlebot`, `*`)
- `public/version.json` — Release metadata and plain-English changelog
