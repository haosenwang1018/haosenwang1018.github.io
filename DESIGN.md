# Sense Wang Website Design Strategy

This document records the current visual direction for `sensewang.com`, especially the homepage and the will page. It is meant to preserve the aesthetic strategy behind the current version so future edits do not drift into generic portfolio design, decorative sci-fi, or overbuilt personal-brand pages.

## North Star

The site should feel minimal, dark, deep, and civilizational.

The reference is not "space themed." The reference is closer to the first impression of a SpaceX mission page: real aerospace imagery, black space, restrained typography, few words, high conviction, and a sense that the work points beyond ordinary software.

The site should communicate:

- I like no-more design.
- I like black and white.
- I like SpaceX-like mission gravity.
- I care about AI, space, civilization, dignity, and extraordinary work.
- I do not want decoration for decoration's sake.

## Core Aesthetic Principles

1. **Real imagery, not symbolic decoration**
   Use real NASA/spaceflight imagery as atmosphere. Avoid icons, vector rockets, fake stars, moon stickers, sci-fi gradients, glowing UI panels, and decorative illustrations.

2. **Darkness as space, not as a theme**
   The black background should feel like depth. Use near-black (`#050505`) rather than a flat pure black when possible. Let image texture appear only where it supports scale.

3. **Text is the object**
   The site is mostly language. Images should never compete with the words. The strongest visual elements are the sentences, spacing, and hierarchy.

4. **No cards, no bento, no startup dashboard**
   This is not a SaaS homepage, portfolio template, or productivity app. Avoid rounded cards, boxed panels, badges, colorful chips, and UI-heavy decoration.

5. **Industrial clarity**
   Typography should feel like Apple/SF Pro and SpaceX: clean, sans-serif, crisp, direct. Prefer the system font stack:
   `-apple-system, BlinkMacSystemFont, "SF Pro Text", "SF Pro Display", "PingFang SC", "Helvetica Neue", Arial, sans-serif`.

6. **Austere but not empty**
   Minimalism here is not blankness. It should have scale, gravity, and visual pressure from real space imagery and strong mission text.

7. **High contrast, low ornament**
   Use off-white text on near-black. Secondary text should be muted. Lines should be thin and quiet. Any highlight should come from hierarchy, not color.

## Shared Visual System

### Palette

- Background: `#050505`
- Primary text: `#f5f5f0`
- Muted text: `rgba(245, 245, 240, 0.64-0.66)`
- Quiet metadata: `rgba(245, 245, 240, 0.42-0.43)`
- Lines: `rgba(245, 245, 240, 0.18)`

Avoid saturated colors unless there is a specific reason. The site should remain black, white, and near-gray.

### Typography

Use system sans fonts. Do not return the homepage or will page to serif typography.

Headlines should be large, dense, and confident. Letter spacing should stay at `0` for large titles. Small labels may use uppercase with positive letter spacing around `0.08em-0.12em`.

### Layout

Desktop pages should use a full-viewport composition:

- top navigation
- mission or document content anchored low enough to feel cinematic
- quiet footer
- no floating cards

Mobile pages may scroll. Mobile should preserve the same feeling, but text must wrap cleanly and avoid horizontal overflow.

### Imagery

Use public-domain NASA imagery, compressed locally into `assets/`. Each asset must be documented in `assets/README.md` with source, reference URL, license/status, and local processing.

Images should be placed as background atmosphere with strong black overlays. They should never read as stock photos or page banners.

## Homepage Strategy

The homepage is the public front door. It should feel like a mission cover, not a resume.

### Current Direction

The homepage uses a real ISS Earth-limb image. This avoids an obvious moon/rocket cliche while giving the page orbital depth. The image is pushed behind black overlays so the primary experience remains text.

The homepage message is intentionally short:

```text
Build great works.
Do extraordinary things.
```

Supporting language should stay compact and directional:

```text
I build AI infrastructure and agent systems for a future where intelligence
expands human capability beyond Earth.
```

### Content Hierarchy

1. Brand: `Sense Wang`
2. Navigation: `Writing / Will / GitHub / X`
3. Small mission label: `AI Systems / Space Intelligence / Civilization`
4. Main mission statement
5. One supporting sentence
6. Selected work list
7. Quiet footer

### What To Avoid On The Homepage

- Long self-introduction
- Dense project descriptions
- Resume-like sections
- Colorful value tags
- Decorative moon, stars, rockets, or planets
- Marketing hero layout with split cards
- Anything that feels like a personal website template

## Will Page Strategy

The will page is not a legal document and not a blog post. It is a mission document written to the living self.

It should feel serious, final, and alive. It should have the gravity of a private commitment made public.

### Current Direction

The will page uses a real Apollo full-moon image. The moon element is intentionally present because the content mentions bringing intelligence into space and deep-space capability. The Moon should appear as a complete celestial body, not as dirty surface texture, a decorative icon, or an abstract sci-fi motif.

The first screen should make these lines unavoidable:

```text
Build great works.
Do extraordinary things.
```

The Chinese and English versions should be switched with a language control. Do not stack the full Chinese version above the English version; that makes the page feel low-effort and document-dump-like.

### Content Hierarchy

1. Brand and navigation
2. Kicker: `Will / Moon / Civilization`
3. Title: `遗书 / Will`
4. Mission lines:
   `Build great works.`
   `Do extraordinary things.`
5. Metadata: `Sense Wang · 2026.05.25 · sensewang.com`
6. Document area with language switch
7. The will content
8. Signature area

### Interaction

The language switch should be understated:

- plain text buttons
- active language indicated by a thin underline
- no pill buttons
- no flags
- no dropdown unless the page gains more languages

The selected language may persist in `localStorage`.

### Signature

A real signature image can be added later, but it must be treated as a serious personal mark, not decoration.

If added:

- use a web-sized version, not a high-resolution signature scan
- place it in the signature area only
- keep text name and date visible
- do not use fake handwritten fonts

## Maintenance Rules

- Keep homepage and will page visually aligned.
- Keep writing pages quieter and more essay-like, but they may evolve separately.
- Keep all space imagery local and documented.
- Prefer one strong image per page over multiple visual motifs.
- If a new design element is added, ask whether it increases mission gravity or merely adds decoration.
- Before shipping visual changes, check both desktop and mobile screenshots.
