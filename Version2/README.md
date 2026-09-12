# StrongerHer V2

Open `StrongerHer-V2.html` to review the complete page. It embeds all images and fonts and needs no installation. The self-contained review file is about 14.3 MB because it preserves the full original media files.

For implementation, use `index.html` alongside the `assets` folder. Upload that version and the screenshots to Lovable with `LOVABLE-HANDOFF-V2.md`.

## Changes from V1

- Larger 64–68px main CTA controls with 17–18px labels.
- More readable body copy, FAQ questions, testimonial text, captions, and supporting labels.
- A desktop header CTA; larger, unclipped language navigation on mobile.
- The existing women-only audience label is visible in the hero.
- Testimonials appear immediately after the hero.
- The community screenshot gallery follows the coaching section.
- A stronger signup panel and an optional WhatsApp contact route.
- Original brand palette and typography, original images, complete testimonials, and all FAQ answers retained.

V1 has not been overwritten. The page remains a waitlist preview because final commercial details and an enrollment destination have not been supplied. The website has not been published, and no live subscriptions or payments have been made.

## Marketing, editing, and payment advice

Read `LAUNCH-AND-CONVERSION-PLAN.md` for the proposed WhatsApp/Instagram funnel, two-week preparation sequence, required offer details, lean follow-up plan, editing options, and the distinction between paying Naeem and taking participant payments.

The HTML is a design artifact, not a shared CMS or an installed automation. Any authenticated editing interface, confirmed signup workflow, payment integration, and analytics setup must be implemented and tested separately in the client's production project.

## Content checks

`content-check.json` compares the design against the original page and complete story/FAQ data. All original paragraph, heading, and caption blocks are present. All 11 full testimonial records and 14 FAQ answers match the source.

## Browser verification

- No horizontal document overflow at 320, 390, 580, 581, 768, 800, 1024, 1250, and 1440px.
- Desktop, tablet, narrow-mobile, and final-signup previews inspected.
- All 16 image elements load; the portable HTML makes zero external asset requests.
- Testimonial dialog: Tab, Shift+Tab, Escape, and focus restoration pass.
- Testimonial and community next controls advance their respective galleries.
- FAQ expansion, signup navigation, and invalid-email validation pass.
- Mobile sticky CTA hides at signup; mobile hero CTA measures 66px tall.
- Final browser console has no errors or warnings.
- No live signup or payment was submitted. Email delivery and paid enrollment remain production integration checks.

## Maintainable styling

V2 CSS appears in `<style id="v2-design">`. The top-level variables `--v2-body`, `--v2-button`, `--v2-button-height`, `--v2-heading`, and `--v2-space` provide a starting point for design adjustments. Responsive rules refine those values by element and screen size. The Lovable implementation should consolidate V1 and V2 styling into one clean page-scoped stylesheet rather than retaining two layers of overrides.
