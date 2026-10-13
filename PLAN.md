# DG9.com Typeless Pages: Keywords, Images, Traffic Plan

## 1. Keywords

### English (US intent)
- **Primary:** AI dictation app
- **Secondary:**
  - voice to text app
  - dictation software for Mac and Windows
  - voice typing app
  - dictate prompts to ChatGPT
  - dictation for dyslexia
  - speech to text for emails

### Spanish (neutral Latin American, chosen for Spanish search intent, not translated)
- **Primary:** dictado por voz con IA
- **Secondary:**
  - voz a texto
  - escribir con la voz
  - app para dictar textos
  - dictado por voz en Windows y Mac
  - dictarle a ChatGPT
  - dictado para dislexia

Keyword volumes were not measured. Check them in Google Keyword Planner or Search Console after launch and adjust titles if a secondary term pulls more clicks.

## 2. Images (done)

12 original illustrations in `/images/`, with keyword file names in each language. Plus 2 JPG share images (1200 x 630) for LinkedIn, Facebook, and WhatsApp previews: ai-dictation-app-share.jpg and dictado-por-voz-con-ia-share.jpg.

| Section | English file | Spanish file | Size | Sales message |
|---|---|---|---|---|
| Hero (also the social share image) | ai-dictation-app.webp | dictado-por-voz-con-ia.webp | 1600 x 900 | Stop typing. Start talking. / Nearly 70% less typing time |
| Problem | typing-wastes-time.webp | perder-tiempo-tecleando.webp | 1200 x 900 | Hours lost to the keyboard? |
| How it works | voice-to-text-3-steps.webp | voz-a-texto-3-pasos.webp | 1200 x 900 | Ready in 3 steps / Free plan available |
| Professionals card | dictation-for-business-owners.webp | dictado-para-duenos-de-negocio.webp | 1200 x 675 | Your proposal, done before your coffee gets cold. |
| Talk to AI | dictate-prompts-to-chatgpt.webp | dictarle-a-chatgpt.webp | 1200 x 900 | Talk to AI. Don't type to it. |
| Final CTA | voice-typing-app.webp | escribir-con-la-voz.webp | 1200 x 675 | Your voice is your fastest keyboard. / Free plan, free Pro trial |

All under 60 KB each. No Typeless logo used, so no brand-asset permission needed.

## 3. Traffic plan

**Target:** 35,000 to 50,000 visitors a year, both languages, about 3,000 to 4,000 a month.

**Reality check:** A single landing page on a non-keyword domain will not rank fast. Year 1 traffic comes mostly from channels you control. SEO grows in year 2.

| Channel | What to do | Monthly visitors goal (by month 6) |
|---|---|---|
| YouTube + Shorts (EN and ES) | 2 short demos a week: "I dictated this email in 40 seconds," before/after prompts. Link to dg9.com in description. | 1,000 |
| LinkedIn (your profile) | 2 posts a week on "Talk to AI, don't type to it." Show the before/after prompt. | 600 |
| NiceJobs.com | Banner and blog post: "Write your resume by voice." Replaces the old DG9 forward. | 400 |
| Email signature + newsletter | One line: "I write by voice. Here's how: dg9.com" | 150 |
| Communities (EN and ES) | Helpful answers in dyslexia, job search, and productivity groups. Share the workflow first, link second. Follow each group's rules. | 400 |
| SEO articles (add pages) | 1 article per month per language on the secondary keywords, each linking to the main page. | 300, growing to 1,500+ in year 2 |
| Pinterest / Facebook groups (ES) | Simple visual of the before/after prompt. | 300 |
| **Total** | | **~3,150 a month (about 38,000 a year)** |

**Conversion math:** 38,000 visitors x 2.5% = about 950 sign-ups a year. Hitting 1,000 paying customers depends on how many free users upgrade to Pro. Track it in your Typeless affiliate dashboard monthly.

**Before any paid ads:** read the Typeless affiliate terms. Many programs ban bidding on the brand name.

## 4. Launch steps (GitHub Pages)

1. Create a new public repo, for example `dg9-site`.
2. Upload: `index.html`, `es/index.html`, `images/` (6 files), `CNAME`, `robots.txt`, `sitemap.xml`.
3. Settings > Pages > Deploy from branch `main`, folder `/root`. Custom domain: `dg9.com`.
4. In GoDaddy DNS for DG9.COM:
   - Remove the forwarding to NiceJobs.com.
   - A records for `@`: 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
   - CNAME for `www`: `<your-github-username>.github.io`
5. Wait for the HTTPS certificate, then tick "Enforce HTTPS."
6. Add dg9.com to Google Search Console and submit `sitemap.xml`.

## 5. Self-check results

- Titles under 60 characters: EN 55, ES 57. Pass.
- Meta descriptions under 155: EN 131, ES 141. Pass.
- Canonical, hreflang (en, es, x-default), viewport, Open Graph, Twitter card: Pass.
- Identical CSS on both pages: Pass. No JavaScript used.
- Disclosure under hero CTA and in footer, both pages: Pass. One line on desktop at 1300px+ wide.
- Affiliate links: 3 per page, marked `rel="sponsored"`. Pass.
- Product claims: verified facts list, plus owner-stated "up to 3 languages at once." Time savings ("nearly 70%") is sourced to the Stanford study (speech about 3x faster than typing = about 67% less typing time) and linked on the page. Privacy and cancellation FAQs point to Typeless pages instead of guessing. Pass.
- No horizontal scroll at phone width (390px): Pass.
- Banned words: none found. Pass.
- Speed claim: "about 3x faster, up to two-thirds less typing time," cited to the 2016 Stanford / University of Washington / Baidu study, with a link on the page. Pass.
