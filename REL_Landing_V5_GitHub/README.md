# RestoEnLigne — Landing page V5 · FR / EN

## Preview
Run `python3 -m http.server 8000` from this folder, then open `http://localhost:8000/fr/` and `/en/`. Root `/` redirects to `/fr/`.

## Content and structure
- `fr/index.html` and `en/index.html`: fully rendered semantic copy in each language; CSS and JS shared in `assets/`.
- `assets/`: images, responsive stylesheet, flip-card JS.
- `REL_Copies_FR_EN_V5.xlsx`: editorial content, card copy, SEO metadata, feature comparison, launch checklist.
- `translations.json`: general copy reference; HTML pages contain final text and must also be updated if text changes.
- `content_cards.json`: card content reference.

## Design decisions
- Mobile-first responsive breakpoints; Hero photo and text are separate columns to avoid overlap; image uses object-fit with face-safe crop. Challenge copy is right on desktop; team section copy left and photo right.
- Six cards: problem front and solution back; touch and keyboard (buttons), reduced-motion preference. Click **Let's talk / Parlons-en** on an open card to pre-select need in form.
- Six-plan feature-only comparison, no detailed prices. Spotlight free listing / paid plans from $29/month in hero.
- Testimonials and logos are honest placeholders, with no fabricated client claims. A female restaurant owner photo can be substituted once supplied and approved.
- GIF and Microsoft Bookings intentionally unconnected. Contact form is a DEMO only and does not transmit or store data. Phone is required. Privacy policy URL pending.

## Critical production tasks
1. **Do not remove `noindex,nofollow`** until ALL placeholders, integrations, claims, policies and SEO deployment URLs are resolved.
2. Replace Microsoft Bookings placeholder with an actual 15-minute booking embed, including the appropriate lead fields, or change primary CTA to a connected form.
3. Connect form server-side with spam protection and Law 25 consent/privacy notice; never claim that demo form submits anything.
4. Replace product GIF placeholder with approved product capture of available features; hide if unavailable on published page.
5. Obtain real testimonial approvals, proper client photography and logos; hide this section until valid proof exists.
6. Validate 26,000+ restaurants, 6,000+ visitors/day and since 2003, and clarify what 'qualified' means.
7. Verify feature matrix with internal approved pitch deck. Check Performance support and operational availability of creator partnerships.
8. Confirm who pays the 10% fee; disclose precise conditions before purchase.
9. Replace `hreflang` URLs in each HTML with the actual production URLs; add canonical, sitemap, OG image and JSON-LD with grounded facts. The current example URLs should NOT be left in production.
10. Validate breakpoints 320/375/390/768/1024/1440 and forms with real browsers, and meet WCAG AA.
11. Keep this GitHub repository private if storing unpublished commercial material. No secrets or API keys.

## Sharing with developer
GitHub repository settings → Collaborators → invite developer to **this repository only**. README + Excel serve as full handoff.
