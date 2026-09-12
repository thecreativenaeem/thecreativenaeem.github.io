# Implement the approved StrongerHer V2

Use the supplied V2 `index.html`, `assets` folder, and V2 desktop/mobile screenshots as the visual source of truth. Implement this version in the existing `/strongerher` route. Do not invent another design.

Preserve all original marketing text, images, captions, colors, full testimonials, FAQ answers, and external link destinations. Copy changes to pricing, dates, weekly schedule, guarantees, or enrollment language require separately approved content. Keep the Arabic and home destinations pointing to their existing pages.

The client specifically requested larger buttons and stronger hierarchy. Match the 64–68px main buttons with 17–18px labels, the more legible supporting text, early testimonials, and the clearer final signup panel. On mobile, place the primary action before the portrait and hide the bottom sticky action when signup is visible. Preserve the responsive rules at 320, 390, 768, 1024, and 1440px.

Create maintainable React components according to this project's conventions. Keep the original design tokens. Consolidate the two stylesheet layers into a clean page-scoped implementation. Use normal asset files, not base64-embedded images, for production. Retain correct image dimensions, optimize delivery without changing the visuals, and check sharing previews and in-app browsers.

Retain accessible FAQ disclosures, labelled controls, visible keyboard focus, meaningful headings, and the testimonial dialog's Tab/Shift+Tab containment, Escape dismissal, and focus restoration. Keep all 11 stories and 14 complete FAQs.

Integrate the real MailerLite form. Display success only when the service confirms it, provide a retry path on failure, and preserve entered email text. The HTML preview opens the provider response in a separate tab; do not treat this as a finished confirmation/onboarding experience. Do not submit real test subscribers without authorization.

Before publishing, confirm the commercial details and whether the campaign is pre-enrollment or open for enrollment. A waitlist CTA should not remain the only action during a campaign intended to accept purchases. Do not fabricate an enrollment URL, payment provider, or sales video.

Walk Coach Hebah through the current Lovable preview toolbar using the actual project. Verify direct text edits, show the actual method for font-size changes, demonstrate mobile preview and recovery, and document the steps. Do not claim that this HTML file contains a shared CMS. If she needs predefined non-AI style controls, propose and scope that settings interface explicitly.

Prepare a preview for review. Do not publish merely because the implementation is complete.
