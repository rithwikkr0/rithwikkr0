# Rithwik K R — GitHub Profile Strategy Report
*Prepared as Senior SWE / Technical Recruiter / GitHub Consultant / OSS Mentor review*

> **Note on data:** I attempted to pull your live GitHub profile (`github.com/rithwikkr0`) directly
> for this report but couldn't get a clean fetch of current repo list/stats in this session — search
> results returned other people's similarly-named profiles instead of yours. Everything below is
> built from your resume plus the project context we've built up over our past sessions (the README
> generation pass covering 12 public repos including Ridermate, campus-security, and
> smart-traffic-dashboard). **Before you publish anything, sanity-check the repo names and pinning
> recommendations below against what's actually live** — slot in real repo slugs wherever you see
> `REPO_NAME` placeholders in the README and template files.

---

## 1. Profile Analysis

**Strengths showing up in your resume:**
- Real hardware shipped (Memo-Chan, traffic system prototype) — most 1st-year profiles have zero working hardware
- Hackathon traction (OpenAI Buildathon Finalist is a genuinely strong line)
- Range — embedded, mobile, AI tooling, web — signals versatility
- Active, documented building habit (not just coursework)

**Gaps a recruiter will notice in under 10 seconds on your GitHub:**
- No profile README currently → first impression is just a repo grid, no narrative
- Project names/descriptions likely undersell scope (e.g., "Smart Traffic Dashboard" doesn't say *ESP32, RFID, real-time OLED, override logic*)
- No visible demo media (GIFs/screenshots) on hardware projects — these are the single highest-leverage addition for embedded work, since code alone can't show a servo moving or an OLED face animating
- Skill claims ("Python basics," "SQL basics") undersell what you've actually built — the resume's own hedging language works against you
- No pinned-repo curation — recruiters give a profile ~30 seconds; pins do the curating for them

---

## 2. Repository Recommendations

### 📌 Pin these 6 (your strongest signal, by category)
1. **FlowForge Ultimate** — most ambitious/current, shows independent product thinking, browser extension dev
2. **Memo-Chan** — best demo potential (cute robot + multi-protocol connectivity = memorable), strong embedded depth
3. **Ridermate** — shows mobile/Flutter + Firebase, a different stack than your embedded work (breadth signal)
4. **Smart Traffic Dashboard** — strongest "social good + technical depth" combo, good for both IoT and AI internship framing
5. **Campus Security System** (RFID auth) — directly relevant to your *actual degree* (Cybersecurity Engineering), don't bury this
6. One AI/ML notebook project (Kaggle-style or coursework-adjacent) once you have one polished enough to stand alone — even a clean, well-commented Colab-to-repo port of your LSTM/autoencoder coursework would work as a 6th pin today

### 🗄️ Archive or consolidate
- **Arduino OLED Game Experiments** (Snake/Flappy Bird) — fine as a learning exercise, weak as a standalone repo. Either fold into a single "embedded-experiments" monorepo with a clear README explaining it's exploratory, or archive it. Don't pin it.
- **Python Practice Projects** — same logic. Beginner exercise repos read as noise next to your real builds. Archive, or merge into a single `learning-notebooks` repo if you want the commit history visible.
- Any auto-generated/template repos with no customization (default Create-React-App, unedited tutorial clones) — archive these outright; they currently dilute your contribution graph.

### 🔧 Improve before showing
- **Blind Stick concept** — currently described as concept-only. Either build the minimal prototype (even breadboard-level with photos) or move the writeup into a `docs/ideas.md` section of a broader portfolio repo rather than a standalone empty-feeling repo.
- **OLED Display Interface System** — this is a *technique*, not a product. Consider merging it as a documented module/library inside Memo-Chan or the traffic dashboard repo (where it's actually used) rather than a standalone repo with no real application.
- Every repo you keep: add a README using the template provided, and at minimum one screenshot/GIF for hardware projects.

---

## 3. Branding & Visual Theme

**Recommended palette:** Dark theme, blue/cyan accent — reads as "technical/security" without being generic green-terminal hacker cliché.
- Primary accent: `#0d6efd` (confident blue) or `#00b4d8` (cyan, pairs well with embedded/IoT branding)
- Stat card theme: `tokyonight` or `dracula` (both used in the README above) — clean, widely recognizable, not overdone like `radical`
- Badge style: `flat-square` throughout for consistency — avoid mixing badge styles across sections, it's the #1 thing that makes profile READMEs look thrown-together
- Avatar/banner: if you make a banner graphic, keep it to name + 2–3 word tagline max. Avoid stock "coding gif" banners — they're overused and don't differentiate you.

**Voice/tone for your bio and About Me:** Confident but specific. Replace generic phrases like *"passionate about technology"* (resume currently has several of these) with concrete claims — *"built a robot that talks over BLE"* beats *"passionate about IoT"* every time. Recruiters skim past adjectives and stop at verbs + nouns.

---

## 4. 90-Day Roadmap

### Days 1–15: Foundation
- [ ] Publish the profile README (provided)
- [ ] Re-pin repositories per recommendations above
- [ ] Archive/merge the 2–3 weak repos identified
- [ ] Add README (using template) + at least one screenshot to your top 3 pinned repos
- [ ] Record a 15–30 sec demo clip of Memo-Chan or the traffic system — even a phone video converted to GIF works

### Days 16–45: Depth (pick 2 of 3 tracks based on target internships)
- **AI track:** Take one ML coursework project (LSTM/autoencoder/CV) and turn it into a clean, standalone, well-documented repo — this is currently your weakest visible category relative to your actual IITG AIML coursework
- **Cybersecurity track:** Complete 2–3 rooms on TryHackMe (free tier) covering web app basics or network fundamentals; document key learnings in a `security-notes` repo — directly reinforces your degree
- **IoT track:** Extend Memo-Chan or the traffic system with one new feature (e.g., add a simple ML inference on-device, or add a security feature like encrypted BLE pairing) — shows growth on existing work rather than just starting new things

### Days 46–75: Visibility
- [ ] Write one technical blog post (dev.to or Hashnode, both free) on a project you actually solved a hard problem in — the WebSocket/AsyncTCP debugging from Memo-Chan is a genuinely good write-up candidate
- [ ] Make your first external open-source contribution — even a docs fix or small bug report on a library you've used (e.g., `links2004/WebSockets`) counts and shows on your contribution graph
- [ ] Update LinkedIn to match the new GitHub narrative; cross-link both

### Days 76–90: Application-ready
- [ ] Final pass: every pinned repo has README + demo media + clean commit history (squash embarrassing "fix typo" commit spam if needed)
- [ ] Verify GitHub stats/streak widgets are rendering correctly (these depend on public contribution activity — make sure you're not committing only to private repos)
- [ ] Start applying — AI/ML and IoT internships first, given current project strength; cybersecurity internships once the TryHackMe track has visible output

---

## 5. Profile Rating

| Category | Before | After (post-90-day plan) |
|---|---|---|
| First impression / narrative | 3/10 (no profile README) | 8/10 |
| Project presentation | 4/10 (sparse descriptions, no demos) | 8/10 |
| Repo curation / signal-to-noise | 4/10 (practice repos mixed with real work) | 9/10 |
| Skill-to-resume alignment | 5/10 (degree is cybersecurity, GitHub shows mostly embedded/AI) | 8/10 (security track added) |
| Visual polish | 2/10 (no badges, stats, or theme) | 8/10 |
| **Overall recruiter-readiness** | **4/10** | **8/10** |

The gap is entirely closeable with curation and presentation — you're not short on real substance, you're short on packaging it. That's the good kind of problem to have at this stage.

---

## 6. What I Built For You (Files in This Pack)

1. `PROFILE_README.md` — copy-paste ready profile README (goes in a repo named exactly `rithwikkr0`)
2. `REPO_README_TEMPLATE.md` — reusable template for every individual project repo
3. `STRATEGY_REPORT.md` — this document

**Next step:** Replace every `REPO_NAME` placeholder with real repo slugs once you confirm them, swap in your actual LinkedIn URL, and push.
