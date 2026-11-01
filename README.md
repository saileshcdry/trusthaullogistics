# Trust Haul Logistics Pvt. Ltd. — Website Documentation

**Official website for Trust Haul Logistics Pvt. Ltd.**
A Nepal-based 4-wheeler drive-away transport company specialising in dealership-to-customer and dealership-to-dealership vehicle delivery.

**Live site:** https://your-site.netlify.app *(replace with live URL)*
**Repository:** https://github.com/YOUR-USERNAME/trust-haul-website
**Owner:** Trust Haul Logistics Pvt. Ltd., Kathmandu, Nepal
**Last updated:** November 2026

---

## Table of Contents

1. [Business Context](#1-business-context)
2. [Project Overview](#2-project-overview)
3. [File Structure](#3-file-structure)
4. [Technical Stack](#4-technical-stack)
5. [Design System](#5-design-system)
6. [Page-by-Page Guide](#6-page-by-page-guide)
7. [Content Management](#7-content-management)
8. [Placeholders to Replace](#8-placeholders-to-replace)
9. [Quote Form Documentation](#9-quote-form-documentation)
10. [Deployment](#10-deployment)
11. [Netlify Settings Checklist](#11-netlify-settings-checklist)
12. [GitHub Settings Checklist](#12-github-settings-checklist)
13. [SEO Checklist](#13-seo-checklist)
14. [Content Voice & Tone Guide](#14-content-voice--tone-guide)
15. [Troubleshooting](#15-troubleshooting)
16. [Roadmap](#16-roadmap)
17. [Support & Contact](#17-support--contact)
18. [License](#18-license)

---

## 1. Business Context

### What the company does

Trust Haul Logistics Pvt. Ltd. is a **4-wheeler specialist** transport company based in Kathmandu, Nepal. We move cars, SUVs, jeeps and passenger vans between dealerships and to end customers.

### Two core services

| Service | Description | Typical Customer |
|---|---|---|
| **Dealership → Customer** | Last-mile delivery from a dealer showroom to the buyer's home or office | Dealerships, individual car buyers |
| **Dealership → Dealership** | Stock movement between dealer showrooms | Dealer principals, inventory managers |

### How vehicles are moved

Vehicles are **driven** from pickup to delivery by vetted professional drivers — not carried on carriers. This is deliberate:

- **Faster** for single vehicles than waiting for a carrier slot
- **Cheaper** on most domestic Nepal routes
- **Door-to-door** by design — no depot transfers
- **Documented** with photos and odometer readings at every handover

### What we do NOT do

The website explicitly filters out non-service work to save customer service time:

- ❌ Two-wheelers, bikes, scooters
- ❌ Buses, minibuses
- ❌ Trucks and heavy commercial vehicles
- ❌ Construction equipment
- ❌ Household or general cargo
- ❌ Cross-border / import clearance jobs
- ❌ Any transport outside Nepal

### Why this positioning matters

General transporters in Nepal move cement, furniture, and scrap alongside vehicles. Dealerships lose trust in that model because cars share space with building materials. **The website's core selling point is that we never do this.**

Every page reinforces: *"We only move 4-wheelers. That's the point."*

---

## 2. Project Overview

| Attribute | Value |
|---|---|
| **Site type** | Static multi-page website |
| **Pages** | 8 (Home, Services, For Dealers, For Owners, Pricing, FAQ, Contact, Thanks) |
| **Language** | English with Nepali hero tagline |
| **Build system** | None — plain HTML/CSS |
| **JavaScript** | None — 100% CSS-driven interactions |
| **Form backend** | Netlify Forms (no server) |
| **Hosting** | Netlify (free tier) |
| **Version control** | GitHub |
| **Auto-deploy** | On push to `main` branch |
| **SSL** | Automatic via Netlify |
| **Analytics** | Not yet installed (see Roadmap) |
| **Languages** | English only (Nepali toggle planned) |

### Design philosophy

1. **Mobile-first** — majority of Nepali buyers browse on phones
2. **Trust over flash** — no animations, no carousel; just clear information
3. **Specific over vague** — real numbers, real routes, real prices
4. **Fast over fancy** — total site weight under 100KB

### Performance targets

| Metric | Target | Current |
|---|---|---|
| Total page weight | < 100 KB | ✅ ~85 KB |
| First Contentful Paint | < 1.5s | ✅ ~0.8s |
| Lighthouse score (mobile) | > 95 | ✅ ~98 |
| JavaScript size | 0 KB | ✅ 0 KB |

---

## 3. File Structure
