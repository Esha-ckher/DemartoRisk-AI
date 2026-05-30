
# DermatoRisk AI 🧴

> Pre-usage skincare risk assessment tool for adolescents and young adults (15–30) in Pakistan who rely on social media for skincare decisions.

## Live Demo
🔗 [Try it here](https://your-netlify-url.netlify.app)

---

## Problem
76% of young adults in Pakistan discover skincare products through social media. Most purchase and apply products without understanding ingredient risks, skin compatibility, or whether influencer claims are clinically accurate.

## Solution
DermatoRisk AI provides instant, evidence-based risk assessment before purchasing or applying any skincare product — combining ingredient science, dermatology literature, and AI-powered claim detection.

---

## Core Features
- **Ingredient Risk Detection** — flags harmful components (steroids, bleaching agents, irritants, comedogenic substances) with skin-type specific warnings
- **Social Media Claim Analysis** — evaluates influencer/TikTok claims as Realistic, Exaggerated, Misleading, or Unverifiable
- **Trend vs Clinical Dual View** — shows what social media says versus what dermatology actually shows
- **Personalized Risk Classification** — Safe / Caution / High Risk based on your skin type and concerns
- **Skincare Education** — clinically accurate dermatology fact after every analysis
- **Search Any Product** — AI analyzes any skincare product in real time

---

## User Research Validation
Survey of 100+ respondents confirmed demand for:
- 82% — personalized skin-type recommendations ✅ Built
- 76% — ingredient analysis and safety transparency ✅ Built
- 68% — side effects and risk awareness ✅ Built
- 58% — social media claim fact-checking ✅ Built
- 29% — skincare education and awareness ✅ Built

---

## Technology
- Frontend: Vanilla HTML/CSS/JS — no framework, no installation
- AI Model: Llama 3.3 70B via Groq API
- Backend Proxy: Cloudflare Workers (API key protection)
- Hosting: Netlify

---

## Project Files
- `DermatoRisk_AI.html` — Latest version, AI-powered search for any product
- `DermatoRisk_AI_mvp.html` — Original MVP with 5 clinically researched Pakistani market products, works fully offline

---

## Data Sources
INCIDecoder · PubMed · Acne.org · CosDNA · Daraz Reviews · Folliculitis Scout · TikTok Community Analysis · Kiboclinics · Derma.pk · AAD Guidelines

---

## Ethics & Disclaimer
This tool is a decision-support and awareness system only. It does not store personal data, does not diagnose skin conditions, and does not replace professional dermatological consultation. Users are advised to patch test all products and consult a qualified dermatologist for clinical concerns.

---

## Project Context
Developed as part of an interdisciplinary AI project combining dermatological risk analysis with social media influence detection. Original approach integrating ingredient-level risk assessment, claim detection, review pattern analysis, and personalized skin classification in a single lightweight tool.
