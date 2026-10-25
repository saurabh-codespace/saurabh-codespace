# Profile motion

Read this file before changing the profile artwork.

## Palette and typography

Colors come from the original banner: navy #0b1220, deep teal #112b37, surface #122d37/#153239/#193d47, borders #2b535b/#367267, mint #63e6be/#8ee6cf, sky #67d4f7/#93c5fd, white #f1f5f9, supporting text #b8cad9/#8aa4b7. Teal #0d9488 matches the existing repository badge. Segoe UI, Arial, sans-serif; name 88px, role 31px, body 19px, diagram labels 14–15px in the 1200×460 viewBox.

## Motion and finish

Adapt motion-effects recipe 13, Perspective Shift, to a GitHub image: three illustrated planes share an oblique projection, separate by 2.2 seconds, hold through 6.6 seconds, then return by 8 seconds. Subtle signal lights remain active during the hold. Every loop returns to the same state. Native SVG CSS keeps the artwork self-contained without scripts or downloaded fonts. GIF and MP4 exports are unnecessary for this profile embed.

The foreground is an interface, the middle is an API, and the base is data. Shallow extruded edges and guides suggest depth. Background and identity text stay still. Scale the whole composition without changing its aspect ratio.

## Accessibility and boundaries

Honor prefers-reduced-motion with a static separated stack. The README's picture/source selects a PNG still, because media preferences do not reliably propagate into SVG image contexts. The SVG also includes a reduced-motion rule for direct viewing. Provide a standalone PNG link and descriptive image text. Keep the bio and project links in Markdown. No flashes, fake statistics, external animation services, pointer-following effects, or fabricated work history. Do not add JavaScript to the README.
