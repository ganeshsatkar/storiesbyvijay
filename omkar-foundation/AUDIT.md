# Omkar Foundation — Digital Presence Audit & Identity Brief

_Audit date: 6 Oct 2026_

**Assets reviewed**

| Channel | URL |
|---|---|
| Website | https://omkarfoundation.org/ |
| Facebook | https://www.facebook.com/profile.php?id=61586401400338 |
| Instagram | https://www.instagram.com/omkar_foundation7/ |
| YouTube | https://www.youtube.com/channel/UC39nb1UcwxFASwRhWl1lmlQ |

> **Method note.** The audit environment's network policy blocked direct access to
> omkarfoundation.org, facebook.com, instagram.com and youtube.com, and the
> Facebook page is not among the pages connected to our Meta account. Findings
> below come from search-engine indexes, public registries and news coverage.
> Items marked **[verify]** need a 10-minute manual check in a browser
> (follower counts, last post dates, page speed, mobile layout).

---

## मराठी सारांश (Quick summary)

1. **Navacha clash (sagla motha problem):** "Omkar Foundation" ya navane kamit kami
   4 vegvegalya sanstha online aahet — Ahmedabad chi *Omkar Foundation Trust*
   (Omguru, divyang seva), *Onkar Foundation*, US madhli *Omkar Foundation*, ani
   apli Mumbai chi CSR foundation. Google var apla brand vegla disat nahi.
2. **Website juni aahe:** content "last 36 months" sarkhe relative numbers vaprte
   (kadhi che te kalat nahi), search index madhe `http://` URLs disat aahet, ani
   site fakt 4–5 pages chi aahe (Home, Our Works, Partners, Contact).
3. **Social handles ekmekanshi jult nahit:** FB la username nahi (`profile.php?id=`),
   Insta handle madhe "7" aahe, YouTube la @handle URL nahi. Ek common handle
   pahije.
4. **Parent brand cha risk:** Foundation che directors Omkar Realtors che promoters
   aahet; 2021 madhe tyanchya virudhh ED case zali hoti (nantar court ne PMLA
   charges discharge kele). Foundation chi swatantra, impact-first identity
   banvli tar ha baggage kami hoto.
5. **Strength:** Impact numbers khup strong aahet (33,808+ youth mobilised,
   2,000+ scholarships, 479+ placements, 37 training partners, 500+ eco-chulas,
   5,500+ health beneficiaries) — pan te stories ani photos madhe disat nahit.

---

## 1. Who the foundation is (as the internet sees it)

- **What:** CSR wing of Omkar Realtors & Developers. Works in Mumbai slum /
  SRA communities on four pillars: skill development, women empowerment,
  health awareness, environment. Positioning line on the site: going
  *"beyond structures"*.
- **Legal entity:** OMKAR FOUNDATION, Section 8 company, CIN
  `U85310MH2014NPL256635`, incorporated 26 Dec 2014, ROC Mumbai, status Active.
  Directors: Nilesh Palande, Gaurav Gupta, Rajendra Varma, Babulal Varma,
  Kamalkishore Gupta. Registered address: Sion (E), Mumbai 400022.
  ([ZaubaCorp](https://www.zaubacorp.com/OMKAR-FOUNDATION-U85310MH2014NPL256635))
- **Office on website:** Omkar House, Off Eastern Express Highway, Sion (E),
  Mumbai 400022.

**Impact claims currently on the site** ([Our Works](http://www.omkarfoundation.org/our-works))

| Pillar | Claim |
|---|---|
| Skilling | 160+ courses (MSC-IT, CCTV tech, driving, welding…), 5th-std dropouts → graduates |
| Skilling | 37 training partners (Godrej & Boyce, ICICI Foundation, Asian Paints, L&T, Save the Children…) + 25 NSDC partners, 50 centres |
| Skilling | 2,000+ scholarships "in the last 36 months"; 33,808+ youth mobilised; 1,200+ jobs sourced; 479+ placed (Zicom, L&T, ASMAC, HDFC Life) |
| Women | 1,500+ women in jewellery-making, beautician, tailoring, self-defence classes in SRA buildings |
| Women/Env | 500+ smokeless eco-chulas to tribal women around Mumbai |
| Health | Free check-ups + hospital follow-up for 5,500+ beneficiaries |
| Environment | Rainwater harvesting, STPs in slum-rehab buildings |

These are genuinely strong numbers. The problem is presentation, not substance.

---

## 2. Website audit — omkarfoundation.org

| # | Finding | Severity | Fix |
|---|---|---|---|
| W1 | Indexed URLs are `http://www.…`; confirm HTTPS + redirect **[verify]** | High | Force HTTPS, single canonical host |
| W2 | Only ~4 indexed pages (Home, Our Works, Partners, Contact) | High | Full IA below |
| W3 | Time-relative claims ("last 36 months") with no date / year | High | Every number gets an "as of" date and a source year |
| W4 | No visible compliance block in indexed content: 12A, 80G, CSR-1 reg. no., annual reports, audited financials, board list | High | Add **Transparency** page — mandatory for CSR partners & donors |
| W5 | No donate / partner / volunteer flow found in index | High | Add clear CTAs: *Partner with us (CSR)*, *Volunteer*, *Donate (80G receipt)* |
| W6 | Page titles are generic ("Omkar Foundation", "Contact Omkar Foundation") | Med | Unique `<title>` + meta description per page, local keywords (Mumbai, SRA, skilling) |
| W7 | No beneficiary stories, names, photos or video in index | Med | Story-led pages (see §5) |
| W8 | English only | Med | Marathi + English (Hindi optional) — beneficiaries and volunteers are Marathi/Hindi speaking |
| W9 | No links to social channels found in index **[verify]** | Med | Footer + header social links, Open Graph tags |
| W10 | Brand collision in search results (see §4) | High | Schema.org `NGO` markup with CIN, address, `sameAs` social links; Google Business Profile |
| W11 | Page speed, mobile layout, accessibility **[verify]** | — | Run PageSpeed Insights + Lighthouse after access |

**Proposed sitemap**

```
Home
About ─ Our story · Leadership & board · Approach ("beyond structures")
Programmes ─ Skills & Livelihoods · Women Empowerment · Health · Environment
Impact ─ Numbers dashboard (dated) · Stories · Annual reports
Partners ─ Current partners · Partner with us (CSR)
Get involved ─ Volunteer · Donate (80G) · Careers
Transparency ─ Registrations (CIN, 12A, 80G, CSR-1) · Financials · Policies
Media ─ News · Photo/video gallery
Contact
```

---

## 3. Social media audit

| Channel | Finding | Fix |
|---|---|---|
| **Facebook** | URL is `profile.php?id=61586401400338` → no username set. ID range indicates a recently created page/profile. Not connected to our Meta Business account, so no insights access. Confirm it is a **Page** (not a personal profile) **[verify]** | Claim username, set category = Nonprofit, add website, WhatsApp, address, CIN; connect to Meta Business Suite and give us access |
| **Instagram** | Handle `omkar_foundation7` — the "7" looks like a workaround because the clean name was taken. Hard to remember, looks unofficial | Move to a unified handle (see below); switch to Professional → Nonprofit; link-in-bio to website |
| **YouTube** | Shared as `/channel/UC…` ID, no @handle in use | Claim matching @handle, banner, About with links, playlists per programme |
| **All** | No evidence in search of cross-linking, consistent bio, or consistent logo/cover **[verify]** | One bio, one logo, one cover system across all three |
| **All** | Follower counts, posting frequency, last post date, engagement **[verify]** | Fill in the table below |

**Fill-in table (manual check)**

| Channel | Followers | Posts | Last post | Avg likes/views |
|---|---|---|---|---|
| Facebook | | | | |
| Instagram | | | | |
| YouTube | | | | |

**Handle unification — candidates to check (availability not verified)**

Pick one and use it everywhere:
- `@omkarfoundation.mumbai`
- `@omkarfoundationindia`
- `@omkar.foundation`
- `@beyondstructures` (campaign / sub-brand handle)

---

## 4. The identity problem

### 4.1 Name collision

| Organisation | Where | Focus |
|---|---|---|
| **Omkar Foundation (ours)** | Mumbai | CSR — SRA skilling, women, health, environment |
| Omkar Foundation Trust | Ahmedabad | Persons with disabilities; founded by Omguru (national award 2016) — has its own site + FB `omkarsampraday` |
| Onkar Foundation | — | "Creating Healthy Bharat" |
| Omkar Foundation | USA (EIN 22-3796086) | Listed on Charity Navigator |
| OmKar Charitable Trust | — | Child education, on DonateKart |

Anyone searching "Omkar Foundation" sees a mix of all of these. Our foundation
has no distinct visual or verbal signature to separate it.

### 4.2 Parent-brand risk

The foundation's directors include Omkar Realtors' promoters. In Jan 2021 the
ED arrested the group's chairman and MD in an SRA-linked PMLA case
([Business Today](https://www.businesstoday.in/latest/corporate/story/ed-arrests-omkar-realtors-chairman-md-in-rs-22000-crore-sra-scam-285580-2021-01-27));
a special court later discharged them under PMLA
([Scroll](https://scroll.in/latest/1031241/ed-a-vengeful-complainant-says-mumbai-court-while-discharging-case-against-two-men-under-pmla)).
A foundation that works *in SRA communities* and is visibly tied to the
developer will get that question. Best answer: radical transparency
(financials, board, third-party impact numbers) and an identity built around
the **communities**, not the company.

### 4.3 Recommended identity direction

**Core idea — "Beyond Structures" / "इमारतीच्या पलीकडे"**
The foundation already owns this phrase. Build the whole identity on it: a
building gives a family a roof; the foundation gives the family a future.

- **Name lock-up:** *Omkar Foundation* + descriptor line
  *"Beyond Structures · Mumbai"* — the descriptor does the disambiguation work
  in every search result, bio and thumbnail.
- **Logo concept:** a window grid from an SRA building where one window opens
  into a person / rising line. Avoid the "ॐ" glyph — it's the generic
  visual for every "Omkar" org and reads religious.
- **Colour:** move away from corporate realty blues. Suggested: deep indigo
  (trust) + marigold/saffron accent (Mumbai, warmth) + off-white. Final
  palette to be tested for contrast.
- **Type:** bilingual pairing — a Devanagari face with a matching Latin face
  (e.g. Mukta / Hind family) so Marathi and English look like one brand.
- **Voice:** first-person stories from beneficiaries, Marathi-first on social,
  numbers always dated.
- **Photo rule:** real faces from SRA sites, with consent; no stock images.

---

## 5. Content engine (where storytelling fits)

Recurring formats, same template on all channels:

| Format | Channel | Cadence |
|---|---|---|
| *Ek Kahani* — 60-sec beneficiary story (trainee → job) | IG Reels, YT Shorts, FB | Weekly |
| *Skill of the Month* — course spotlight + enrolment CTA | IG carousel, FB | Monthly |
| *Number that matters* — one dated impact stat | All | Fortnightly |
| *Partner spotlight* (Godrej, L&T, ICICI Fdn…) | LinkedIn, FB | Monthly |
| Long-form documentary (5–8 min) per pillar | YouTube, website | Quarterly |
| Annual impact report | Website PDF + carousel | Yearly |

---

## 6. Priority roadmap

**Week 1–2 (hygiene)**
- [ ] Get admin access to FB, IG, YT, domain/hosting
- [ ] Fill §3 fill-in table; run PageSpeed / Lighthouse
- [ ] Lock one handle; claim it on all platforms
- [ ] Fix bios, links, category, contact on all channels
- [ ] Collect registration docs (12A, 80G, CSR-1, CIN) and latest annual report

**Week 3–6 (identity)**
- [ ] Logo + colour + type exploration (3 routes) around "Beyond Structures"
- [ ] Brand guide (1 page) + social templates
- [ ] Shoot photo/video bank at 2–3 SRA sites and one training centre

**Week 6–12 (website)**
- [ ] New site per sitemap in §2, bilingual, HTTPS, schema.org NGO markup
- [ ] Transparency page live
- [ ] Partner / Volunteer / Donate flows
- [ ] Google Business Profile for Omkar House office

**Ongoing**
- [ ] Content engine in §5, monthly review of reach and enquiries

---

## 7. Open questions for the client

1. Should the identity stay visibly linked to Omkar Realtors, or stand apart?
2. Does the foundation accept public donations (80G), or only CSR partnerships?
3. Who owns the FB page `61586401400338` and IG `omkar_foundation7` — are these
   official, and who has admin access?
4. Are the impact numbers on the current site up to date? What is the latest
   year's data?
5. Budget and timeline for photo/video shoot.

---

**Sources:**
[omkarfoundation.org](http://www.omkarfoundation.org/) ·
[Our Works](http://www.omkarfoundation.org/our-works) ·
[Partners](http://www.omkarfoundation.org/partners) ·
[Contact](http://www.omkarfoundation.org/contact) ·
[ZaubaCorp — CIN record](https://www.zaubacorp.com/OMKAR-FOUNDATION-U85310MH2014NPL256635) ·
[National Skills Network — UDAY × Omkar Foundation](https://nationalskillsnetwork.in/uday-omkar-skill-center/) ·
[Omkar Foundation Trust, Ahmedabad](https://www.omkarfoundationtrust.org/) ·
[Onkar Foundation](https://onkarfoundation.org/) ·
[Charity Navigator — Omkar Foundation (US)](https://www.charitynavigator.org/ein/223796086) ·
[Business Today — ED arrests (2021)](https://www.businesstoday.in/latest/corporate/story/ed-arrests-omkar-realtors-chairman-md-in-rs-22000-crore-sra-scam-285580-2021-01-27) ·
[Scroll — PMLA discharge](https://scroll.in/latest/1031241/ed-a-vengeful-complainant-says-mumbai-court-while-discharging-case-against-two-men-under-pmla)
