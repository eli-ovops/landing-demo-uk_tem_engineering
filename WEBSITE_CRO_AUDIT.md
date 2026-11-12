# Website and CRO audit

**URL:** https://tem-engineering.co.uk/  
**Visual review:** Chrome headless browser, 2026-08-29.  
**Evidence files:** `tem-desktop-1440x900.png` (1440×900) and `tem-mobile-390x844.png` (390×844). These are browser-rendered captures, not a claim of customer acceptance.

## What a visitor currently sees

| Area | Desktop 1440×900 | Mobile 390×844 | Consequence |
| --- | --- | --- | --- |
| Hero | Large industrial workshop image, company name, and generic “Innovating Engineering Solutions” headline. | Wordmark/headline visibly overflow/crop; top builder promotion appears above the site. | The business category is broadly legible from image, but specific capability is not conveyed quickly enough. |
| Capability hierarchy | No CNC machining, fabrication, design, project-management, or sector/service breakdown appears in the inspected initial view before the contact section. | Same absence; image and cropped headline consume the initial view. | A technical buyer cannot efficiently self-qualify TEM for an enquiry. |
| CTA | The next dominant section is “Contact Us” / “Drop us a line!” form. | Cookie panel overlays the lower contact view and clips the accept control at viewport edge. | Contact exists, but lacks a prior reason-to-enquire and has a real mobile interaction obstruction. |
| Trust/proof | No visible selected work, inspection/quality process, project story, client sector, certification, lead time, or delivery evidence in initial view. | Same in the capture. | The existing real industrial image creates atmosphere but not adequate buyer reassurance. |
| Accessibility/readability | Light text over image; visual audit found mobile clipping. | Large content cuts at right edge and cookie notice reduces usable viewport. | Mobile continuity risk is material. |

## Bounded surface audit (supporting evidence, not the buying thesis)

`squirrel` was already available at `/Users/USER/.local/bin/squirrel`; it was used only in this new research directory. It crawled three URLs (surface scope, max 25) and saved `surface-audit.llm`. The tool announced an automatic self-update from 0.0.87 to 0.0.88; no installation, login, project-root initialisation, or configuration was requested or performed.

- Overall surface score: **46/F**; Performance 95, Core SEO 34, Accessibility 42, Security 43.
- Relevant detected issues: missing meta descriptions/canonicals, duplicate short titles, two H1s, thin content (105 words), invalid ARIA values, form-label/input-type issues, possible contrast issues, and a non-HTTPS HTTP endpoint that redirects to HTTPS.
- The scan reported no crawl-cap limit and 3 audited pages. A visible GoDaddy/Airo builder artefact in the mobile capture reinforces the presentation issue.
- Technical findings are **not** positioned as the reason to buy. The purchase case is capability communication, trust sequencing, and a direct enquiry path.

## Information architecture gap and static remedy

| Current state | Static concept response | Boundaries |
| --- | --- | --- |
| Generic hero statement | Specific, verified capability signal: CNC machining + metal fabrication + design/project delivery | Do not invent tolerances, sectors, certifications, lead times, or capacity. |
| Contact form immediately after hero | Put 3 verified capability lanes and one buyer-oriented quote prompt before contact | Keep a contact action only; do not create a real submission backend. |
| No proof sequence | Use only cleared future proof: verified process, quality evidence, project facts, or neutral original concept imagery | No invented projects/reviews/logos/certifications. |
| Broken mobile continuity | Mobile-first hierarchy, uncut type, unobstructed CTA, no lateral overflow | Validate later in a real browser; this research is not a finished Demo. |

## Link and interaction status

- Page loaded in Chrome at both specified viewports.
- No form was completed or submitted.
- Current visible page places a contact form on the landing page; no independent quote CTA was observed in the captured region.
- The Squirrel surface scan found no decisive broken-link evidence in its summary, but its `/ols/products` discovery should not be treated as a verified customer-facing product catalogue without further review.

## Audit conclusion

**H0.5 PASS — MEANINGFUL DEMO OPPORTUNITY VERIFIED.** The opportunity is a factual, static, buyer-facing reorganisation, not an SEO repair proposal. `CLIENT-SHOWABLE DEMO` remains inapplicable: no Demo has been authorised or made.
