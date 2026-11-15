 <div align="center">

<img src="./logo-mark.svg" width="88" alt="SatisCorp mark" />

# SatisCorp

**Software you actually own.**

Independent software. No AI. No telemetry. No internet required.

[Website](https://livepreview.usecartouche.com/satiscorp/brand) · [Brand Guidelines](https://livepreview.usecartouche.com/satiscorp/brand) · [GitHub Organization](https://github.com/SatisCorprperation)

<img src="./header-1500x500.png" width="100%" alt="SatisCorp brand identity" />

</div>

---

# 01 — Introduction

## About SatisCorp

SatisCorp is an independent software studio creating small, focused and accessible tools.

It started from one frustration: AI creeping into everything. We believe software does not need artificial intelligence, permanent internet access, cloud accounts or unnecessary complexity to be useful.

Our products are designed around a simple idea:

**Your software should belong to you.**

We build tools that run on your machine, respect your privacy and give you control over your files and settings.

Our software is open source and free. Its design follows the same principles as its engineering: clarity, simplicity and independence.

## Our principles

Five ideas guide every decision we make.

| Principle | Meaning |
|---|---|
| **Small** | Tools you can understand. Few features, done well, easy to read and run. |
| **Offline** | Everything works without the internet. Nothing needs a server to start. |
| **Yours** | Your files, your machine, your settings. No account, no lock-in. |
| **Plain** | Clear words and calm design. We explain what a tool does and what it does not do. |
| **Open** | Open source and free, so anyone can read the code and check what we say. |

---

# 02 — Naming

## How to write our name

The name is always written as **SatisCorp**.

One word, two capital letters, no space.

Our products share the "Satis" prefix so that they are clearly recognizable as part of the same family.

| Correct | Incorrect |
|---|---|
| SatisCorp | Satiscorp |
| SatisCode | SATISCODE |
| SatisCode Web | Satis Code Web |
| SatisReader | Satis-Reader |
| SatisDocs | Satis Docs |
| SatisPalette | Satis Palette |

Never write "SatisCorp's AI". SatisCorp does not offer AI-powered products.

---

# 03 — Logo system

## The mark

The SatisCorp mark is a bold, geometric letter S.

It is deliberately simple, compact and easy to recognize. It is designed to remain readable even at very small sizes.

<img src="./logo-mark.svg" width="120" alt="SatisCorp mark" />

### Construction

The mark is constructed on a 64 × 64 grid.

- Overall proportions: 56 × 56 units.
- Internal margin: 4 units.
- The two bars of the S have the same thickness.
- Corners share a consistent radius.
- The mark uses one solid colour.
- No outlines, gradients or internal effects.

It must remain aligned to its original grid when reproduced.

### Logo variations

**Primary horizontal lockup**

<img src="./logo-lockup.svg" width="340" alt="SatisCorp horizontal logo" />

**Dark horizontal lockup**

<img src="./logo-lockup-dark.svg" width="340" alt="SatisCorp dark logo" />

**Standalone mark**

<img src="./logo-mark.svg" width="100" alt="SatisCorp standalone mark" />

**Dark standalone mark**

<img src="./logo-mark-dark.svg" width="100" alt="SatisCorp dark standalone mark" />

### Which version to use?

| Version | Recommended use |
|---|---|
| Horizontal lockup | Websites, documentation and general communication |
| Stacked lockup | Square spaces and profile cards |
| Standalone mark | Favicons, app icons and compact interfaces |
| PNG versions | Applications that cannot use SVG |

The horizontal lockup is the preferred version. The standalone mark can be used when the SatisCorp name is already visible nearby.

### Minimum sizes

- Horizontal lockup: 96 px.
- Stacked lockup: 72 px.
- Product lockup: 120 px.
- Standalone mark: readable down to 16 px.

### Clear space

Keep a margin around the mark equal to half its width.

No text, graphic or other element should enter this protected area.

### Logo restrictions

Never:

- Stretch or distort the mark.
- Rotate it.
- Change its geometry.
- Apply unapproved colours.
- Add shadows or decorative effects.
- Place it on a busy photograph.
- Use insufficient contrast.

---

# 04 — Product identity

Each product shares the SatisCorp mark and receives one dedicated accent colour.

The accent should appear as a thin line, a dot or a highlight. It should not become a full background behind text.

## SatisCode

<sub>DEVELOPMENT · WINDOWS</sub>

An offline code editor for Windows.

<text style="color:#FF8A3D">**Accent — `#FF8A3D`**</text>

## SatisReader

<sub>READING · RSS / ATOM</sub>

A small RSS and ATOM feed reader.

<text style="color:#52A8FF">**Accent — `#52A8FF`**</text>

## SatisDocs

<sub>DOCUMENTS · MARKDOWN</sub>

Markdown files presented as clean web pages.

<text style="color:#50E3C2">**Accent — `#50E3C2`**</text>

## SatisPalette

<sub>DESIGN · WEB</sub>

A search palette for any website.

<text style="color:#BF7AF0">**Accent — `#BF7AF0`**</text>

---

# 05 — Colour system

The SatisCorp identity is primarily black and white.

The website supports dark and light themes. Product colours are reserved for meaning and identification.

## Dark theme

| Token | HEX | Usage |
|---|---|---|
| Black | `#000000` | Page background |
| Surface 0 | `#050505` | Cards |
| Surface 1 | `#0A0A0A` | Panels |
| Surface 2 | `#111111` | Chips and inputs |
| Soft white | `#EDEDED` | Main text |
| Grey | `#A1A1A1` | Secondary text |
| Dim | `#8A8A8A` | Labels and captions |
| White | `#FFFFFF` | Strong text and buttons |

## Light theme

| Token | HEX | Usage |
|---|---|---|
| Paper | `#FAFAFA` | Page background |
| Surface | `#F4F4F5` | Cards |
| Surface 2 | `#EFEFF1` | Panels |
| Surface 3 | `#E6E6E9` | Chips |
| Ink | `#171717` | Main text |
| Muted | `#4F4F55` | Secondary text |
| Dim | `#707078` | Labels |
| Black | `#000000` | Strong text and buttons |

## Accent colours

| Colour | HEX | Usage |
|---|---|---|
| Orange | `#FF8A3D` | SatisCode |
| Blue | `#52A8FF` | SatisReader |
| Green | `#50E3C2` | SatisDocs |
| Violet | `#BF7AF0` | SatisPalette |
| Red | `#FF6166` | Errors and warnings |
| Amber | `#F5A623` | Cautions |

Use black or white text on accent backgrounds according to contrast.

Product colours should not replace the main monochromatic identity.

---

# 06 — Design tokens

These are the core CSS values used by the SatisCorp website.

```css
/* SatisCorp design tokens: dark theme */

:root {
  --bg: #000;
  --s0: #050505;
  --s1: #0a0a0a;
  --s2: #111;

  --ink: #ededed;
  --muted: #a1a1a1;
  --dim: #8a8a8a;

  --line: rgba(255, 255, 255, .10);
  --line2: rgba(255, 255, 255, .20);

  --ok: #50e3c2;

  --font: 'Geist', system-ui, sans-serif;
  --mono: 'Geist Mono', ui-monospace, monospace;

  --satiscode: #ff8a3d;
  --satisreader: #52a8ff;
  --satisdocs: #50e3c2;
  --satispalette: #bf7af0;
}

/* Light theme */

html[data-theme="light"] {
  --bg: #fafafa;
  --s0: #f4f4f5;
  --s1: #efeff1;
  --s2: #e6e6e9;

  --ink: #171717;
  --muted: #4f4f55;
  --dim: #707078;

  --line: rgba(0, 0, 0, .12);
  --line2: rgba(0, 0, 0, .24);

  --ok: #067a62;
}
```

---

# 07 — Typography

## Geist. And nothing else.

Typography is one of the most important parts of the SatisCorp identity.

The entire visual system uses two typefaces:

- **Geist** — the primary interface and editorial typeface.
- **Geist Mono** — the monospace typeface for technical information.

No additional typefaces are required.

Both fonts are free and distributed under the SIL Open Font License. They are served directly from the SatisCorp website.

## Geist

<sub>PRIMARY TYPEFACE</sub>

<text weight="light">**Geist Light**</text>

<text weight="normal">**Geist Regular**</text>

<text weight="semibold">**Geist Semibold**</text>

<text weight="bold">**Geist Extra Bold**</text>

ABCDEFGHIJKLMNOPQRSTUVWXYZ

abcdefghijklmnopqrstuvwxyz

0123456789 .,:;!?&@#%

Geist is used for headings, paragraphs, navigation, buttons and general interface text.

## Geist Mono

<sub>MONOSPACE TYPEFACE</sub>

**Geist Mono Regular**

**Geist Mono Semibold**

```text
git clone https://github.com
const answer = 42;
0123456789 -> => !=
```

Geist Mono is used for labels, technical details, keyboard shortcuts, code-related content and small metadata.

## Type scale

| Element | Size | Weight | Style |
|---|---:|---|---|
| Heading 1 | 76 px | Bold | Tight spacing |
| Heading 2 | 32 px | Bold | Clear hierarchy |
| Body | 18 px | Regular | Comfortable reading |
| Labels | 12 px | Mono | Uppercase or technical labels |

### Typography rules

- Keep large headings tightly spaced.
- Use normal spacing for paragraphs.
- Maintain clear contrast between headings and body text.
- Avoid unnecessary font variations.
- Use Geist Mono sparingly for technical emphasis.
- Prioritize readability over decoration.

---

# 08 — Shape and spacing

## Rounded geometry

SatisCorp uses generously rounded corners and consistent geometric proportions.

| Radius | Usage |
|---:|---|
| 8 px | Chips and small buttons |
| 12 px | Inputs and list rows |
| 16 px | Cards |
| 20 px | Large cards and panels |
| 99 px | Buttons and pills |

## Spacing scale

Use a consistent spacing scale based on multiples of four.

```text
4 · 8 · 12 · 16 · 24 · 32 · 48 · 72
```

These values should be reused across layouts, components and interfaces.

## Borders

Prefer subtle borders over heavy shadows.

- Primary border: 10% opacity.
- Secondary border: 20% opacity.
- Default border thickness: 1 px.

---

# 09 — Iconography

SatisCorp icons use simple outlines without decorative fills.

### Icon specifications

| Property | Specification |
|---|---|
| Grid | 24 × 24 px |
| Stroke width | 1.8 px |
| Ends | Rounded |
| Fill | None |
| Colour | Inherits text colour |

Icons should remain recognizable at small sizes and work in both light and dark themes.

The same stroke weight should be used when creating new icons.

---

# 10 — Interface design

The interface is built from a small collection of reusable components.

### Buttons

Clear labels, restrained styling and obvious interaction states.

### Chips

Used for short metadata, versions, platforms and statuses.

### Alerts

Messages should be concise and informative.

Example:

```text
Good to know
Nothing here is sent anywhere.
```

### Number cards

Use large numbers with short explanatory labels.

### Keyboard shortcuts

Display shortcuts in compact monospace elements.

### General interface rules

- Use colour to communicate meaning.
- Keep interfaces visually quiet.
- Prefer thin borders to heavy shadows.
- Maintain consistent rounded corners.
- Make interactive states obvious.
- Never add visual decoration without a purpose.

---

# 11 — Motion

## Motion explains. It does not decorate.

Every animation should communicate an action, a transition or a change.

| Category | Duration | Usage |
|---|---:|---|
| Fast | 150 ms | Hover and press |
| Base | 250 ms | Fades and menu opening |
| Slow | 480 ms | Colour wipes and theme changes |
| Scene | 900 ms+ | Scroll scenes and logo reveals |

### Easing

The standard easing curve is:

```css
cubic-bezier(.3, .7, .3, 1)
```

It starts quickly and settles gently.

### Motion rules

- One main visual moment per page.
- Short movements for interactions.
- Longer movements for scenes.
- Respect the user's reduced-motion preference.
- Remove or shorten animations when reduced motion is enabled.
- Nothing should animate without a reason.

The logo reveal uses the liquid glass animation and plays once per visit.

---

# 12 — Imagery

## Real screens. No stock photos.

The best picture of a tool is the tool itself.

SatisCorp uses genuine product screenshots and real interface elements.

### Presentation rules

- Show the actual application, not a fabricated mockup.
- Keep the real window frame and text.
- Use a rounded frame.
- Add a subtle border.
- Use a 5 px product-colour strip at the top.
- Prefer 3D scenes made from real interface parts over generic illustrations.

Do not use stock photography.

Do not use photographs of people unless they are the people who made the tool and have agreed to it.

---

# 13 — Voice and writing

## Plain, calm and honest.

SatisCorp communicates with short sentences and everyday words.

We explain what a tool does and what it does not do.

### We write

- Clearly.
- Honestly.
- Briefly.
- Without unnecessary technical jargon.
- Without exaggerated claims.

### We avoid

- Hype words such as "revolutionary", "next-generation" and "seamless".
- Made-up statistics.
- Claims we cannot demonstrate.
- Fear-based messaging about AI.
- Excessive exclamation marks.
- Emojis in interfaces.

### Example

**Good**

> SatisCode is an editor that works offline. It has no AI and no telemetry.

**Avoid**

> Unleash the power of our revolutionary, seamless coding experience!

---

# 14 — Accessibility

SatisCorp interfaces should be usable by everyone.

### Contrast

The following contrast ratios are measured using the WCAG 2 formula.

| Combination | Ratio | WCAG |
|---|---:|---|
| Soft white on black | 17.9:1 | AAA |
| Secondary grey on black | 8.1:1 | AAA |
| Dim labels on black | 6.1:1 | AA |
| White on black | 21.0:1 | AAA |
| Ink on paper | 17.2:1 | AAA |
| Muted on paper | 7.8:1 | AAA |
| Dim on paper | 4.7:1 | AA |
| Orange on black | 9.0:1 | AAA |
| Blue on black | 8.4:1 | AAA |
| Green on black | 13.1:1 | AAA |
| Violet on black | 7.3:1 | AAA |

### Interaction

- Every control must have a visible keyboard focus state.
- All interfaces must work with a keyboard.
- Colour must never be the only indicator of status.
- Status should include an icon or a word.
- Body text should be at least 16 px.
- Touch targets should be at least 38 px.
- Line length should remain below 70 characters.
- Respect reduced-motion settings.
- Nothing should play sound automatically.

---

# 15 — Social identity

Official communication assets are provided in this repository.

| Asset | Dimensions | Usage |
|---|---:|---|
| `avatar-400.png` | 400 × 400 | Profile picture |
| `github-social-1280x640.png` | 1280 × 640 | GitHub social preview |
| `header-1500x500.png` | 1500 × 500 | Social header |
| `linkedin-banner-1584x396.png` | 1584 × 396 | LinkedIn banner |
| `story-1080x1920.png` | 1080 × 1920 | Vertical story |

The visual identity should remain consistent across platforms.

---

# 16 — Official badges

Four official badges are available for use in READMEs and websites.

- No AI
- Works offline
- No telemetry
- Edited with SatisCode

They are SVG assets designed to match the SatisCorp visual identity.

Use the official hosted versions rather than recreating them.

[View official badges and usage instructions](https://livepreview.usecartouche.com/satiscorp/brand)

---

# 17 — Email signature

The official email signature is intentionally simple.

It contains:

- Name.
- Role.
- Website.
- SatisCorp mark.

No unnecessary quotes or long disclaimers.

---

# 18 — Brand usage

The brand assets are intended for official SatisCorp projects, documentation, interfaces and communication.

Always:

- Use the official logo files.
- Preserve the original proportions.
- Maintain sufficient contrast.
- Follow the spacing rules.
- Use the correct product accent.
- Respect the typography system.

Never:

- Modify the official mark.
- Invent alternative brand colours.
- Introduce additional typefaces.
- Add unnecessary effects.
- Misrepresent product capabilities.
- Make claims that cannot be demonstrated.

---

# 19 — Repository assets

All official assets are stored at the root of this repository.

```text
Branding/
│
├── README.md
│
├── avatar-400.png
├── github-social-1280x640.png
├── header-1500x500.png
├── linkedin-banner-1584x396.png
├── story-1080x1920.png
│
├── logo-icon.svg
├── logo-lockup.svg
├── logo-lockup-dark.svg
├── logo-lockup.png
├── logo-mark.svg
├── logo-mark-dark.svg
├── logo-mark-1024.png
└── logo-mark-dark-1024.png
```

---

# 20 — History

### November 2026

**Version 2 — A bold, squared S**

The previous mark, an S inside a circle, was replaced by a single solid S constructed on a grid.

The new mark is simpler, remains readable at 16 px and fits the black-and-white identity.

**November 2026 — Brand kit and guide**

Official logo files, icons, social images, badges and design tokens collected into one place.

---

# Official resources

| Resource | Link |
|---|---|
| Brand Guidelines | [Open the official guide](https://livepreview.usecartouche.com/satiscorp/brand) |
| GitHub Organization | [SatisCorp](https://github.com/SatisCorprperation) |
| Branding Repository | [GitHub repository](https://github.com/SatisCorprperation/Branding) |

For the complete visual identity, examples and interactive specifications, the official Brand Guidelines website remains the primary reference.

---

<div align="center">

<img src="./logo-mark.svg" width="64" alt="SatisCorp" />

# SatisCorp

**Software you actually own.**

Small. Offline. Yours. Plain. Open.

[Website](https://livepreview.usecartouche.com/satiscorp/brand)

© 2026 SatisCorp

</div>
