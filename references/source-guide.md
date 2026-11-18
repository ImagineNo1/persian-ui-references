# Source routing and verification

Discovery notes checked on 2026-11-18. These are starting points, not a permanently current catalog. Reopen relevant pages for new projects; do not hard-code counts, prices, capabilities, or licensing from these notes.

## Supahero

- Entry: https://supahero.io/
- Role: curated hero examples; inspect composition and headline/image/action relationships.
- Example detail page: https://supahero.io/hero/anubi includes a preview and an outbound project link. This illustrates the detail format, not a default reference for every project.
- At inspection, Supahero announced it was part of Screensdesign while its hero gallery remained accessible. Follow actual current links if navigation changes; do not silently substitute another catalog.
- A preview captures an appearance, not necessarily current interaction. Check the outbound site when behavior matters. Gallery membership does not establish asset licensing.

## 21st.dev

- Entry: https://21st.dev/
- Role: components, sections, themes, and templates. Search for the interface need; inspect each candidate's preview, source, and dependencies.
- The inspected site describes React/TypeScript, Tailwind CSS, and shadcn registry conventions. Verify each item's requirements and license; a catalog description does not prove compatibility.
- For other stacks, extract the pattern and implement within the existing stack. Do not add React solely to use a reference.
- Access/copy limits may change. Do not assume unlimited source access, an installed MCP server, or permission to run suggested commands.

## Originkit

- Entry: https://www.originkit.dev/
- Verified category: https://www.originkit.dev/category/background-animation
- Verified category: https://www.originkit.dev/category/interactive-elements
- Role: motion and visual interaction candidates. Inspect detail pages and live behavior where available rather than selecting only by thumbnail.
- Example: https://www.originkit.dev/components/popcorn-text describes letter-based motion and Framer font controls. Treat it as an adaptation problem for Persian; prefer intact-word/line motion.
- Example: https://www.originkit.dev/components/tornado describes a WebGL effect. Consider GPU cost, touch, reduced motion, and fallback for this class of treatment.
- At inspection, homepage extraction returned no readable body, but category/detail pages were readable. Try this fallback before declaring the site inaccessible.

## Kawai Text Animation

- Entry: https://kawai-text-animation.pages.dev/
- Role: text-motion gallery for exploring short-text rhythm and treatment.
- Initial extraction exposed a loading shell and gallery controls rather than animation details. Inspect individual patterns in a rendered browser. Do not infer effect names, source availability, or Persian compatibility from the page title.
- Record the visible pattern label/identifier and entry URL if there is no permalink. Adapt Latin letter-splitting effects at word/line level or reject them for connected Persian text.

## Fontshare

- Entry: https://www.fontshare.com/
- About: https://www.fontshare.com/about
- Role: type character and Latin companion families. Verify the chosen family's character set, weights, web-use terms, and distribution conditions.
- Its About page describes Indian Type Foundry's free font service for personal/commercial use. That does not prove every family supports Persian or all font files share a license.
- Main-app extraction required JavaScript. Inspect a rendered specimen or accessible family details when selecting a font.
- Verify Persian support using the actual font resource and rendered sample, not a system fallback that displays the text. If absent/unverified, retain the Persian font and label the Fontshare choice as Latin-only inspiration/companion.

## Example routing

- Service landing page: relevant Supahero composition, 21st service/CTA patterns, type direction; consider Originkit/Kawai only when motion serves the brief.
- Dashboard: functional navigation, tables/forms, and states from relevant 21st candidates, aligned with product tokens. Hero galleries and expressive text motion can be excluded after triage.
- Creative portfolio: Supahero composition with an appropriate Originkit treatment or Kawai idea; validate intact Persian shaping and calm mobile/reduced-motion alternatives.

Select actual current items for each case. These routes and example URLs are not mandatory choices.
