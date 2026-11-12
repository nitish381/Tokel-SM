# Tokel — Brand Guidelines & Design System

> Single source of truth for anything Tokel: website, product UI, social media, decks, ads.
> Built from the Figma file **Tokel-LP-Redesign** (`IcLJaFxcYcFIMWzKDBgR32`) — https://www.figma.com/design/IcLJaFxcYcFIMWzKDBgR32/Tokel-LP-Redesign
> Values are exact Figma output unless marked *(inferred)* or *(recommended)*.

---

## 0. Quick reference (read this first)

| Need | Answer |
|---|---|
| Website | **https://tokel.org/** (contact email in Figma footer: `info@tokel.com`) |
| Brand font | **Space Grotesk** (Light / Regular / Medium / SemiBold / Bold) |
| Primary color | Navy `#000088` · Deep navy `#001D6B` · Midnight `#010115` |
| Accent / light | Ice blue `#A6C2D3` → `#F2FAFF` |
| Signature gradient | `linear-gradient(to bottom, #000088, #001D6B)` |
| Visual style | 3D abstract architecture — glass/chrome blue cubes, towers, blocks. **No generic stock photography.** |
| Shape language | Big radii (30–60), pill buttons (radius 39), glassmorphism |
| Logo files (Figma) | `White-Logo` 1413:300 · `Blue-Logo` 1413:302 |

---

## 1. Brand

### 1.1 Who Tokel is
**Tokel — the institutional infrastructure for tokenized real-world assets.**
Issue, distribute, and govern compliant tokenized securities across real estate, private equity, funds, and beyond — at institutional scale, under your brand.

- **Products:** Marketplace (compliance-gated venue) · SaaS Platform (Starter / Business) · White-Label (your cloud, your domain) · Custom / Enterprise.
- **Asset classes:** Real Estate · Private Equity & Funds · Fixed Income / Bonds · Mortgage-Backed Securities · Commodities · Art & Collectibles.
- **Proof points:** 40+ institutional clients · 15+ blockchains supported · Billions in assets tokenized · 10+ asset classes.
- **Regions:** New Zealand · Australia · UAE · Canada · USA · India · Europe.
- **Audience:** issuers, fintechs, asset managers, banks, transfer agents, institutional and accredited investors.

### 1.2 Voice & tone
- **Institutional, confident, precise.** Talk like regulated infrastructure, not like a crypto hype project.
- Short declarative sentences, often in pairs or triplets: *"Your brand. Your cloud. Our infrastructure."* · *"Pay once. Own every stage."* · *"Start lean. Scale to enterprise."*
- Lead with compliance, control and ownership. Words to use: compliant, institutional, governed, auditable, production-ready, under your brand.
- Avoid: "to the moon", memes, emoji-heavy copy, price speculation, "guaranteed returns".
- Headlines: Title Case or sentence case with a period at the end. Two-tone headings put the key phrase in navy `#001D6B` and the rest in ink `#121213`.

### 1.3 Logo
- Wordmark "tokel" with a circular striped mark (vertical bars inside a circle).
- **White logo** on navy, midnight, photo or gradient backgrounds. **Blue logo** on white or light ice backgrounds.
- Web size 118 × 52. Clear space ≥ the height of the circle mark on all sides *(recommended)*.
- Don't recolor, stretch, add shadows, or place it on busy imagery without an overlay.

---

## 2. Graphic style & imagery

**Core rule: Tokel visuals are 3D abstract architecture, not realistic third-party stock photos.**

| Use ✅ | Avoid ❌ |
|---|---|
| 3D abstract building shapes: stacked glass cubes, extruded towers, isometric blocks, modular grids that suggest real estate and infrastructure | Generic stock photos (handshakes, people pointing at screens, random offices) |
| Materials: frosted glass, translucent blue acrylic, chrome, soft reflections | Bitcoin coins, rockets, neon "crypto" clichés |
| Palette in-image: navy `#000088` → electric blue `#143FAD` → ice `#A6C2D3`, white highlights | Warm, orange or multicolor palettes |
| Lighting: soft studio light, blue rim light, subtle depth-of-field | Hard flat illustration or cartoons |
| Product UI mockups in frosted glass frames (dashboards, marketplace, code editor) | Low-resolution screenshots without a frame |
| Floating glass "investment cards" ($10k, NAV, AUM, Subscribe) as hero objects | |

**Exceptions already in the design:** the website hero uses a blurred city skyline with a navy overlay (`#012D5E` → transparent), and the Leadership section uses real team portraits with a navy scrim. Keep real photography to those two cases.

**Image treatments**
- Navy overlay on photos: `linear-gradient(to bottom, #012D5E 0%, rgba(1,45,94,0) 57.6%)`.
- Hard-light tint for dark sections: `linear-gradient(219.5deg, #2E89B0 7.3%, #143FAD 91.6%)`, blend mode hard-light.
- Portrait scrim: `linear-gradient(to bottom, rgba(10,35,67,0) 65%, #0A2343)`.
- Glass frame for UI screenshots: white 70% + backdrop blur 16, radius 29.
- 3D objects can bleed off the canvas edge and rotate ~13.5° (as in the CTA banner).

**Iconography:** thin line icons in navy (on light) or white (on dark), ~40–80px in feature contexts. 20px circular check icon for bullet lists.

---

## 3. Social media sizes & templates

Always design at the exact pixel size below, export PNG (graphics/text) or JPG ≥ 85% quality (photo-heavy), sRGB. Keep text and logo inside the **safe zone**.

### 3.1 LinkedIn
| Asset | Size (px) | Ratio | Notes / safe zone |
|---|---|---|---|
| Personal profile cover | **1584 × 396** | 4:1 | Profile photo covers the bottom-left (~400px wide). Keep text in the right ~2/3 and the middle 70% of height. |
| Company page cover | **1128 × 191** | ~6:1 | Logo overlaps bottom-left. Keep text centered and short; mobile crops the sides. |
| Profile / company logo | 400 × 400 | 1:1 | Shown as a circle (people) or square (company). |
| Post — landscape / link | **1200 × 627** | 1.91:1 | Default for link previews and announcements. |
| Post — square | **1080 × 1080** (or 1200 × 1200) | 1:1 | Safe, all-device format. |
| Post — portrait (best reach) | **1080 × 1350** | 4:5 | Max height LinkedIn shows without cropping. |
| Carousel / document (PDF) | 1080 × 1350 (or 1080 × 1080) | 4:5 / 1:1 | Export slides as a single PDF. |
| Article / newsletter cover | 1920 × 1080 | 16:9 | Keep text in the center. |
| Event cover | 1776 × 444 | 4:1 | |
| Video | 1920 × 1080 / 1080 × 1080 / 1080 × 1350 | 16:9 / 1:1 / 4:5 | |

### 3.2 X (Twitter)
| Asset | Size (px) | Ratio | Notes / safe zone |
|---|---|---|---|
| Header / cover | **1500 × 500** | 3:1 | Avatar overlaps bottom-left. Top and bottom ~60px can crop; keep content in the center 1500 × 360. |
| Profile photo | 400 × 400 | 1:1 | Shown as a circle. |
| Post — landscape | **1600 × 900** | 16:9 | Best single-image format in the timeline. |
| Post — square | 1080 × 1080 | 1:1 | |
| Post — portrait | 1080 × 1350 | 4:5 | Cropped in the timeline preview; key content at the center. |
| Link card | 1200 × 628 | 1.91:1 | |
| Multi-image (2 images) | 700 × 800 each | 7:8 | |

### 3.3 Instagram
| Asset | Size (px) | Ratio | Notes |
|---|---|---|---|
| Feed — portrait (recommended) | **1080 × 1350** | 4:5 | Most screen space. |
| Feed — square | 1080 × 1080 | 1:1 | |
| Feed — tall / grid native | 1080 × 1440 | 3:4 | The profile grid now previews at 3:4. |
| Feed — landscape | 1080 × 566 | 1.91:1 | |
| Story / Reel | **1080 × 1920** | 9:16 | Keep text out of the top 250px and bottom 340px. |
| Reel cover | 1080 × 1920 | 9:16 | The grid crops it to 3:4 at the center. |
| Profile photo | 320 × 320 | 1:1 | Circle. |

### 3.4 Facebook
| Asset | Size (px) | Ratio | Notes |
|---|---|---|---|
| Page cover | **851 × 315** (upload **1640 × 624** for sharpness) | ~2.7:1 | Mobile shows the center ~640 × 360. Keep text centered. |
| Post — landscape / link | 1200 × 630 | 1.91:1 | |
| Post — square / portrait | 1080 × 1080 / 1080 × 1350 | 1:1 / 4:5 | |
| Story | 1080 × 1920 | 9:16 | |
| Event cover | 1920 × 1005 | ~1.91:1 | |
| Profile photo | 320 × 320 | 1:1 | |

### 3.5 YouTube
| Asset | Size (px) | Ratio | Notes |
|---|---|---|---|
| Channel banner | **2560 × 1440** (min 2048 × 1152) | 16:9 | Safe area for text and logo: center **1546 × 423**. |
| Video thumbnail | **1280 × 720** | 16:9 | Under 2MB. |
| Profile photo | 800 × 800 | 1:1 | |
| Shorts | 1080 × 1920 | 9:16 | |

### 3.6 Others
| Platform / asset | Size (px) | Ratio |
|---|---|---|
| Threads post | 1080 × 1350 / 1080 × 1080 | 4:5 / 1:1 |
| Telegram channel post | 1280 × 720 (or 1080 × 1080) | 16:9 / 1:1 |
| Telegram / WhatsApp profile | 640 × 640 | 1:1 |
| Medium / blog header | 1400 × 788 | 16:9 |
| Website OG / share image | 1200 × 630 | 1.91:1 |
| Email header | 1200 × 400 (shown at 600px) | 3:1 |
| Pitch deck slide | 1920 × 1080 | 16:9 |

*Sizes reflect platform guidance current as of Nov 2026; platforms change specs, so re-check before a major campaign.*

### 3.7 How to build a Tokel social graphic
**Cover / banner (LinkedIn, X, YouTube, Facebook)**
1. Background: midnight `#010115` or the brand gradient `#000088 → #001D6B`.
2. 3D abstract building / glass-cube cluster on the **right**, bleeding off the edge.
3. Headline on the **left-center** in Space Grotesk Bold, white or gradient text (`#FFFFFF → #999999`), tracking −2% to −4%.
4. One supporting line in Regular, `#A6C2D3`.
5. Optional pill CTA (white fill, `#000088` text, fully rounded).
6. Logo: white version, top-left or bottom-right. Never under the profile-photo overlap area.

**Post (1:1, 4:5, 1.91:1)**
- **Dark variant:** `#010115` background, 3D object, white heading, `#A6C2D3` body.
- **Light variant:** ice gradient `144.5deg #A6C2D3 → #F2FAFF`, navy `#000088` heading, body `#2C3438`.
- **Stat post:** a big number in Medium 100-style scale (e.g. "40+") with a label underneath.
- **Carousel:** slide 1 is the hook, then one idea per slide with a large index numeral ("01", "02"…), and the last slide is a CTA with the logo.

**Type scale for social canvases** *(recommended, for a 1080-wide canvas)*

| Role | Size | Weight | Tracking |
|---|---|---|---|
| Headline | 72–96 | Bold | −2% |
| Subhead | 36–44 | Medium | −1.5% |
| Body | 26–32 | Regular | −1% |
| Caption / CTA | 22–26 | Medium | 0 |

Scale proportionally for wider canvases (e.g. ×1.4 for 1500-wide headers). Keep text to 8–12 words on covers.

---

## 4. Foundations — Typography, Color, Layout

### 4.1 Typography
**Family:** Space Grotesk — Light 300, Regular 400, Medium 500, SemiBold 600, Bold 700.
Secondary (non-core): Bricolage Grotesque Medium (decorative big numerals), Outfit (legacy cards on the Extra page only).

**Letter-spacing rule:** body/UI ≈ −2% of size (18→−0.36, 20→−0.4, 22→−0.44, 26→−0.52, 34→−0.68, 40→−0.8). Display 50–80 → −2px; 100 → −4px.

| Token | Size / LH | Weight | Tracking | Usage |
|---|---|---|---|---|
| `display-xxl` | 270 | Bold | −2 | Carousel slide index numerals (outlined/gradient) |
| `display-xl` | 100 / 110 | Medium | −4 | Hero headline, stat numbers, animated word ticker |
| `display-lg` | 80 / normal | Bold | −2 | Section headings (two-tone or gradient) |
| `display-md` | 60 / normal | Bold | −2 | Feature card titles, CTA banner, Enterprise plan |
| `display-sm` | 50 / normal | Bold | −2 | Engineered panel titles, carousel titles |
| `heading-lg` | 40 / 40.888 | Medium | −0.8 | Plan names, workflow titles, footer column headers |
| `heading-md` | 34 / 40.888 | Medium | −0.68 | Asset class card titles, dashboard names, KPIs |
| `heading-sm` | 30 / 38–40.888 | Bold/Medium | −0.6/−0.72 | Leadership names, testimonial authors, phone-card titles |
| `lead` | 26 / 36 | Regular | −0.52 | Hero right-column copy, stat labels |
| `body-xl` | 24 | Medium | 0 | Large button labels |
| `body-lg` | 22 | Medium | −0.44 | Checklist items, tab labels |
| `body-md` | 20 | Regular | −0.4 | Section subtitles, card descriptions, plan features |
| `body` | 18 / 26 | Regular | −0.36 | Paragraphs, footer links, small button labels (Medium) |
| `ui` | 16 / 24 | Regular/Medium | −0.32 | Nav items, badges |
| `caption` | 14 | Regular | 0 | Data labels (Min investment, NAV, …) |

### 4.2 Color palette

**Brand**
| Token | Value | Usage |
|---|---|---|
| `navy-900` | `#010115` | Dark sections (Engineered, carousel slides, footer, stats band) |
| `navy-800` | `#0A2343` | Photo scrims |
| `navy-700` | `#030A82` | Engineered panels, plan badges |
| `navy-600` (primary) | `#000088` | Headline accents, CTA text, primary filled buttons, active tab |
| `navy-500` ("main solid") | `#001D6B` | Two-tone heading accent, button text on white, gradient end |
| `blue-300` | `#A6C2D3` | Borders, muted text on dark, gradient start |
| `blue-200` | `#C4D3FA` | Row dividers, chips |
| `blue-150` | `#C8D7FF` | Leadership card gradient |
| `blue-100` | `#E8ECF6` | Light surface |
| `blue-50` | `#F2FAFF` / `#F2F7FE` | Gradient end, light cards |

**Neutrals:** ink `#121213`, body `#2C3438`, muted `#707EAE`, disabled `#A3ACB2`, gradient grey `#999999`, footer border `#1D1F24`, white `#FFFFFF`, black `#000000`.

**Status:** success `#34C759` (Open/Live), success-alt `#49A948` / `#429945` / `#7DB142`, danger `#FF3B30` (Close), warning `#F29339` (KYC pending). Tinted pill bg = color at 20% alpha.

**Hero overlay:** `linear-gradient(to bottom, #012D5E 0%, rgba(1,45,94,0) 57.6%)` over skyline photo.

### 4.3 Gradients
| Token | Value |
|---|---|
| `grad-brand-dark` | `linear-gradient(to bottom, #000088, #001D6B)` — CTA banner, Enterprise card |
| `grad-surface` | `linear-gradient(144.5deg, #A6C2D3 0%, #F2FAFF 101.5%)` — feature cards |
| `grad-surface-inv` | `linear-gradient(135.4deg, #F2FAFF 11.7%, #A6C2D3 92.6%)` — inner listing cards |
| `grad-text-light` | `linear-gradient(to right, #FFFFFF, #999999)` — headings on dark |
| `grad-text-brand` | `linear-gradient(to right, #001D6B, #000088)` — animated text (Var 2) |
| `grad-glass-light` | `linear-gradient(150deg, rgba(255,255,255,.9), rgba(255,255,255,.6))` |
| `grad-overlay-hardlight` | `linear-gradient(219.5deg, rgb(46,137,176) 7.3%, rgb(20,63,173) 91.6%)` blend hard-light |
| `grad-scrim` | `linear-gradient(to bottom, rgba(10,35,67,0) ~65%, #0A2343)` |
| `grad-leader` | `linear-gradient(181.2deg, rgb(200,215,255) 9.8%, rgb(166,194,211) 98.9%)` |

### 4.4 Radius
`10` · `13` (chips) · `20` · `22` · `24` (stat card) · `26` (list rows) · `30` (tabs, panels, leadership cards) · `35.4` (small pill) · `39` (**pill button**) · `40` (phone card, asset cards) · `42` (badge) · `44` (footer top) · `50` (**section cards**) · `60` (dark sections/slides) · `64` (chips)

### 4.5 Spacing & layout
- Canvas 1920; side gutter **70** → content width **1780**.
- Section heading block: heading → subtitle gap **40**; subtitle width ~946; heading → content ~**120–200**.
- Common gaps: 10, 16, 20, 24, 30, 40, 50, 60, 80.
- Feature card: two columns, 868 media + 775 text, gap **80**; stacked cards gap **50** (sticky stacking).
- Pricing container padding **60**; Engineered panel inner gap 30.

### 4.6 Effects
- Glass dark: `rgba(12,66,98,.5)` + blur 8.2 · `rgba(0,0,0,.5)` + blur 24.5 + 1px white border.
- Glass light: `rgba(255,255,255,.1)` + blur 14.3 (ghost button) · `rgba(255,255,255,.7)` + blur 16.25 (mockup frame).
- Dark card: `rgba(255,255,255,.06)` + 1px `rgba(255,255,255,.6)` + blur 10.45.
- Page background: blurred ellipses under white 90% + blur 137.
- Shadow (Enterprise card): `0 52px 24.9px rgba(0,29,107,.25)`.
- Inactive opacities: .1 (off-screen slider panels), .3 (ticker), .5 (nav/tabs), .6 (meta values).

---

## 5. Components

### Buttons (all pills)
| Variant | Spec |
|---|---|
| Primary (on dark/gradient) | bg `#FFF`, text `#000088` Medium 24, h60, px44, r39 |
| Primary filled (on light) | bg `#000088`, text white Medium 18–24, h60, r39 |
| Outline (on light) | 1px `#000088`, text `#000088`, h60, r39 |
| Outline (on dark) | 1px `#FFF`, text white, h60, r39 |
| Ghost glass | 1px `#FFF`, bg white 10% + blur 14.3, text white 24 |
| Small | h50 (or 36), px20–40, r35.4, Medium 18, text `#001D6B` on white |

Button pairs: gap 10–20 (e.g. WhatsApp outline + Telegram filled).

### Navigation
- **Var 1 (on hero):** logo 118×52 left; links 16/24, gap 33, active white Medium, others white 50% Regular; "Book a Demo" outline-white pill 192×60 (18px).
- **Var 2:** white pill container r50, px10 py8; items px10 py6, active has 1px `#001D6B` border r40.

### Stat card (`Hover` 104:1166)
445 wide, flex-col gap 36, py46, r24, blur 10.45; number 100/110 Medium −4, label 26/36. Hover: bg white 6% + 1px white border. Placed on `#010115` band (381h).

### Region pill
213×70, 2px `#A6C2D3` border, r50, pl9 pr57, gap 21; 53px flag; label Regular 18 `#2C3438`. Row gap 48.

### Feature card (sticky stack)
1780×735, r50, `grad-surface`, blur 4.1. Media: 868×735 r50 photo + framed product screenshot (white 70% glass r29). Text column 775: icon ~78 → title `display-md` `#000088` → body 18 `#2C3438` → checklist (20px tick, gap 20, Medium 22 black) → white primary button. Alternates media left/right.

### CTA banner
1780×379, r50, `grad-brand-dark`, decorative 3D image rotated 13.5° bleeding right; heading 60 Bold gradient text; white "View Demo" button.

### Tabs + slider panel (Engineered)
- Tab: h80, p40, r30, Medium 22. Active bg `#000088` white text; inactive bg `rgba(217,217,217,.1)` text white 50%.
- Panel: 1564×741, bg `#030A82`, r30; next panel peeks at opacity .1 (gap 30).
- Panel = 551×440 image (hard-light overlay) + floating glass dashboard card 427×621 r40 + text column (title 50 Bold, body 18 `#A6C2D3`, 5 checklist rows Regular 20 white).
- Status pill "Approved": bg green 20%, text `#49A948`, h50, r35.4. Action chips: bg white 20%, h50, r35.4.

### Asset-class card (dark grid)
r40, bg white 6%, 1px white 60% border, blur 10.45, h435. Bento grid: row1 434/434/882, row2 882/434/434, gap 16. Content p40/45: 40px icon, title Medium 34, desc Regular 20 `#A6C2D3`. Image right, blend screen.

### Workflow list
Rows 1781×128, px30 py20, border-bottom 1px `#C4D3FA`; number "01" Regular 20 `#2C3438`, gap 60, title Medium 40 `#000088`; right description Regular 18 width ~504.

### Pricing
White container 1782×758 r50 blur 33. Plan column 396: "One Time Cost" 20 → price Bold 80 + badge (bg `#030A82`, r42, Regular 16 white) → name Medium 40 `#000088` → tagline 20 → checklist 20 → full-width CTA. Enterprise card 594 wide, `grad-brand-dark`, r50, shadow, lifted 16px above container.

### Leadership card
~544×510, r30, `grad-leader` bg, photo + `grad-scrim`; caption pl42 pb30: name Bold 30 white, role Regular 24 white. Gap 75.

### Carousel slide ("Start lean")
1632×751, bg `#010115`, r60, gap 16. Index numeral Bold 270 outlined; text block left 60, top 473, w623: title Bold 50 `grad-text-light`, body 18 `#A6C2D3`; image fills right.

### Testimonial card
583×491, notched bottom-left shape filled with `grad-surface`*(inferred)*; quote glyph 89×71; quote Regular 20 `#2C3438`; author name Medium 30 `#000088` + sector 20. Gap 17.

### Phone / glass investment card (Final-Animation 332:193)
408×640, 5px white border, r40; inner glass 372 wide r30 `rgba(12,66,98,.5)` blur 8.2. Shows $10k (Light "$", Bold "10", Light "k"), key/value rows Medium 15.4, white button h50 r35.4. 7 variants cycle Preview → Wallet → Subscribe states.

### Animated text (60:100 / 80:96)
Vertical word ticker: Real Estate. → Private Equity. → Securities. → Funds. Active line 100%, others 30%.

### Footer
bg `#010115`, top radius 44, padding top 80 / sides 68. Columns: brand (logo, blurb 18/26 `#A6C2D3`, address, 45px social circles with 1px `#1D1F24` border) · Platform · Call Now · For General Inquiries — headers Medium 40 white, links Regular 18 `#A6C2D3`. Divider + "© 2026 Tokel" Regular 22 white centered.

### Listing cards (Extra page, Outfit font)
- **Card-01** 375×543: image 48.6% top r30; title Medium 20 `#001D6B`; stats label 14 `#707EAE` / value Medium 16 `#001D6B`; pills "Primary market" (navy 10%) and "Open" (`#7DB142` 20%); small button `#001D6B` h36 r39.
- **Detail** 375×848: label/value grid with dividers, country chips h26 r13, "KYC pending" warning pill, CTA `#001D6B` h50 r39.

---

---

## 6. Interactions & animation

Figma defines the states and component variants. Timings marked *(recommended)* are implementation guidance because Figma does not store them.

### 6.1 Motion principles
- **Calm and institutional.** Smooth ease-out, no bounce, no spin.
- **Default easing** *(recommended)*: `cubic-bezier(0.22, 1, 0.36, 1)` (ease-out-quint) for entrances, `cubic-bezier(0.65, 0, 0.35, 1)` for state swaps.
- **Durations** *(recommended)*: hover 150–200ms · tab/panel swap 400–500ms · section reveal 600–800ms · ticker hold 2000–2500ms.
- Animate only `transform` and `opacity`, plus `backdrop-filter` sparingly.
- Respect `prefers-reduced-motion`: turn off the ticker, carousels and parallax, and show final states.

### 6.2 Inventory (from Figma)
| Interaction | Component / node | Behaviour |
|---|---|---|
| **Hero word ticker** | `Animated-Text` 60:100 / `Animated text` 80:96 (4 variants) | A vertical list cycles **Real Estate. → Private Equity. → Securities. → Funds.** The active line is at 100% opacity, the next line at 30%. Slide up one line (~108–130px) every ~2.5s *(recommended)*. Variation 2 fills the text with a gradient `#001D6B → #000088`. |
| **Hero phone card** | `Final-Animation` 332:193 (7 variants) | A 408×640 glass phone card loops through investment steps: asset preview (Real Estate, $10k) → wallet address + jurisdiction → "$10k Minimum / Invest" → "Sign & Continue" / "Subscribe". Cross-fade plus a slight upward move between states. Side cards (AstroNots NFT – Open, L&T Realty – Close) slide in from the sides. |
| **Stat card hover** | `Hover` 104:1166 | Default: transparent. Hover: bg white 6% + 1px white border, radius 24, blur 10.45. Optional count-up on scroll into view *(recommended)*. |
| **Navigation** | Hero nav | Active item is white Medium 100%, others 50% opacity. Hover brings the item to 100%. Var 2 shows the active state as a 1px navy pill outline. |
| **Buttons** | Pill buttons | Hover *(recommended)*: primary white → `#F2FAFF` bg; filled navy → `#001D6B`; outline → fills with 8% navy; ghost glass → white 20%. Press: scale 0.98. Focus: 2px outline `#A6C2D3` with a 2px offset. |
| **Feature cards (sticky stack)** | 362:631 | Four 1780×735 cards are `position: sticky; top: 0`. Each card scrolls over the previous one; optionally scale the covered card to 0.95 and dim it *(recommended)*. Media alternates left/right. |
| **Engineered tabs + slider** | 362:746 / `Enginnered` 172:1126 | Six tabs. Active tab: bg `#000088`, white text. Inactive: white 10% bg, text at 50%. Selecting a tab slides the panel track horizontally (panel 1564 + gap 30). Non-active panels sit at opacity 0.1 so the next one peeks in. Dashboard bars can grow from 0 on enter *(recommended)*. |
| **Asset-class bento cards** | Dark grid | Glass cards (white 6%, 1px white 60% border). Hover *(recommended)*: border to 100%, image scales 1.05, lift −4px. |
| **Workflow list** | 1551:690 | Five numbered rows with a `#C4D3FA` divider. Expand-on-hover or click is optional *(recommended)*; Figma has only the default state. |
| **Pricing** | 362:1150 | The Enterprise card is lifted 16px with shadow `0 52px 24.9px rgba(0,29,107,.25)`. The "Most Popular" badge is on Business. |
| **"Start lean" carousel** | Component 3 362:1281 | Six slides (1632 wide, gap 16) on a horizontal track with a peek of the next slide. Drag/swipe, arrows or autoplay ~5s *(recommended)*. The large index numeral 1–6 can fade or slide in. |
| **Variation 2 hero tab bar** | 80:372 | Three bottom cells (Operator / Marketplace / ATS-Secondary). The active cell gets navy glass with white text; inactive cells are white glass with `#A3ACB2` text. |
| **Scroll reveals** | All sections *(recommended)* | Headings and cards fade up 24px with a stagger of 60–80ms. |

### 6.3 Social & video motion *(recommended)*
- Logo reveal: the striped circle mark draws its bars left→right, then the wordmark fades in (≤1.2s).
- 3D buildings: slow orbit or a 5–10° rotation over 6–8s, with glass highlights sweeping across.
- Text: words rise in one by one (mask reveal), matching the hero ticker.
- Loops of 6–15s for LinkedIn/X video; 9:16 versions for Reels/Shorts.

---

## 7. Page structure (Variation - 1)
1. Hero (1045) — skyline photo + overlay, nav, headline + ticker, phone card center, copy right, 2 CTAs
2. Stats band (`#010115`, 381) — 40+ / 15+ / Billions / 10+
3. Region pills — New Zealand, Australia, UAE, Canada, USA, India, Europe
4. "One platform. Every deployment model." + 4 sticky feature cards (Marketplace, SaaS, White-Label, Custom)
5. CTA banner — "Start tokenizing real-world assets under your own brand"
6. Dark block — Engineered tabs/slider (6 panels) + asset-class bento grid (6 classes)
7. Workflow list (5 steps) + WhatsApp / Telegram buttons
8. Pricing — Starter $30k / Business $45K / Enterprise
9. Our Leadership Team (3)
10. "Start lean. Scale to enterprise." carousel (6 slides)
11. Testimonials (3)
12. Footer

**Variation - 2** differs in the hero only: white/desaturated photo, light glass card, Light 80 + Bold 100 headline in black, and a 3-cell bottom tab bar (Operator / Marketplace / ATS-Secondary, 640×82, active navy glass).

---

## 8. Design debt / cleanup notes
- Only ~6 Figma variables exist; most values are hard-coded. Two navies compete (`#000088` vs `#001D6B`) plus `#030A82` — consolidate into one navy scale.
- Fractional values (15.446, 35.374, 40.888, 27.21) come from scaled components; round to 15/16, 36, 40, 28 in code.
- Three green success tones and two light-blue tints (`#F2FAFF`, `#F2F7FE`) should be merged.
- Mixed fonts (Outfit on Extra-page cards) should be moved to Space Grotesk.
