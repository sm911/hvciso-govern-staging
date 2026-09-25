# Hudson Valley CISO — Govern homepage (STAGING)

**Status:** Staging mockup only · **NOT for Vercel** · **NOT production**

Static rewrite of the Hudson Valley CISO homepage so it reads as **Security Medic’s Govern chapter** — one consulting voice, NIST CSF 2.0 spine, vendor-neutral / MSP-safe.

## Files

| File | Role |
|------|------|
| `index.html` | Complete single-page homepage |
| `styles.css` | Shared styles (navy/slate + amber accent) |
| `ALIGNMENT.md` | How this page closes Partial-alignment gaps |
| `README.md` | This file |

No `package.json`, no Next.js, no build step, no framework.

## How to view locally

**Option A — open the file**

```bash
# From this folder, or Finder / file manager:
open index.html
# or double-click index.html
```

**Option B — local static server (preferred for sticky nav / relative CSS)**

```bash
cd /workspace/securitymedic/staging/hvciso-govern
python3 -m http.server 8765
```

Then open [http://127.0.0.1:8765/](http://127.0.0.1:8765/) in a browser.

Any other static server works the same way.

## What Jim should evaluate

1. **Voice handoff** — Does this feel like Security Medic’s Govern chapter, or still like a generic regional CISO brochure?
2. **Program chrome** — Is the sticky Govern → Identify–Recover → Privacy strip clear as *one program*?
3. **Outcomes vs. checklist** — Do board cadence / risk decisions / exam-insurance readiness / audit design lead better than an 8-item service menu?
4. **Tiers** — Starter 8–12 / Standard 15–20 / Comprehensive 25–35 — calm, matching Security Medic packaging?
5. **MSP callout** — Explicit “we don’t take the stack” — partner-safe enough?
6. **CTA** — Conversation / `support@securitymedic.com` (+ “Book a conversation” → securitymedic.com) — right primary action?
7. **Hard no’s** — Confirm: no “enterprise-grade without the enterprise cost,” no fabricated metrics, no fake Calendly URL, no tool sales tone.
8. **Ship readiness** — Is copy production-candidate (tweak-and-approve), or does anything need a rewrite before a real site build?

## Explicit non-goals

- Do **not** deploy this folder to Vercel or any live domain.
- Do **not** treat sister-site links (CyberIntelPro, Privacy Medic) as a rebuild of those sites.
- AI governance deep page is **referenced only** (`/services/ai-governance` note); this mockup does not host that page.

## Contact (canonical)

- Email: support@securitymedic.com  
- Location: Hudson Valley, New York  
