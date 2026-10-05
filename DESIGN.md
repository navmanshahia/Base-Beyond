# Base & Beyond — Design System

## Overview
A cinematic digital-studio identity combining editorial scale, technical precision and restrained futuristic depth. The page should feel authored, not templated.

## Colors
- Ink: #080808
- Paper: #f0efe6
- Electric lime: #dfff86
- Violet: #a98aff
- Supporting neutrals are warm rather than blue-gray.

Use electric lime as the primary interactive accent. Violet is a secondary depth cue, not a competing CTA color.

## Typography
- Display: Manrope for structural display with Georgia / Times New Roman reserved for italic editorial accents.
- Body/UI: Manrope.
- Technical labels: DM Mono.
- Display text uses strong scale contrast and tight tracking. UI labels remain compact and legible.

## Layout
- Desktop composition is deliberately asymmetric.
- Sections use large negative space followed by concentrated information.
- Real project work receives the largest visual territory.
- Mobile removes decorative offsets but preserves hierarchy and project richness.
- Container max width is approximately 1480px.

## Elevation & Depth
Depth comes from WebGL, cursor-responsive lighting, tonal layering, perspective and selective shadows. Avoid generic glass-card stacking. Flat surfaces are preferred until interaction or emphasis earns depth.

## Shapes
- Main project frames are close to square-edged / small-radius.
- Utility controls may use pills when their compact interactive role benefits from it.
- Avoid using the same rounded rectangle silhouette for every section.

## Components
- CTAs use spring squeeze feedback on tap/click.
- Project cards reveal rich product mockups and open details.
- The experience rail communicates page progress on larger screens.
- Hover lighting is desktop-only; touch devices receive tap feedback instead.
- Focus-visible states must be obvious.
- Tappable controls target at least 44px.

## Motion
Motion thesis: “physical digital material.”
- Hero/WebGL is the focal authored moment.
- Supporting motion uses spring feedback, scroll-linked progress, selective parallax and section reveals.
- Avoid animating every static element just because it exists.
- Routine feedback should feel immediate.
- Reduced-motion users keep state/opacity feedback while spatial motion is removed.

## Do's and Don'ts
Do:
- Use asymmetric editorial tension.
- Let one interaction dominate a section rather than stacking effects.
- Keep pricing and service information scannable.
- Make mobile feel deliberate.
- Preserve performance by favoring transform and opacity.

Don't:
- Repeat generic cards inside cards.
- Use blue-purple SaaS gradients as the default aesthetic.
- Add decorative motion with no hierarchy or feedback role.
- Hide critical functionality on mobile.
- Use OpenAI or other vendor names as decorative credibility markers.
