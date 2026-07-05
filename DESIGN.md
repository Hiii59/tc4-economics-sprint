---
name: TC4 Economics Sprint
description: A sharp, electric, rigorous study product for TC4 economics review and exam drills.
colors:
  ink: "#eff8f5"
  muted: "#bfd1ce"
  line: "#39545a"
  paper: "#17272b"
  soft: "#0f1a1d"
  soft-2: "#132226"
  surface: "#1d3034"
  surface-2: "#243b40"
  graph: "#111d22"
  teal: "#35d8c7"
  teal-dark: "#8ceee4"
  coral: "#ff8068"
  amber: "#ffd66e"
  green: "#7cdda0"
  violet: "#aaa0ff"
  blue: "#7ebaff"
typography:
  display:
    fontFamily: "TH Sarabun New, THSarabunNew, TH SarabunPSK, THSarabunPSK, Sarabun, Noto Sans Thai, Leelawadee UI, Tahoma, Arial, sans-serif"
    fontSize: "4.18rem"
    fontWeight: 700
    lineHeight: 1.03
    letterSpacing: "0"
  headline:
    fontFamily: "TH Sarabun New, THSarabunNew, TH SarabunPSK, THSarabunPSK, Sarabun, Noto Sans Thai, Leelawadee UI, Tahoma, Arial, sans-serif"
    fontSize: "3.05rem"
    fontWeight: 700
    lineHeight: 1.08
    letterSpacing: "0"
  title:
    fontFamily: "TH Sarabun New, THSarabunNew, TH SarabunPSK, THSarabunPSK, Sarabun, Noto Sans Thai, Leelawadee UI, Tahoma, Arial, sans-serif"
    fontSize: "2.05rem"
    fontWeight: 700
    lineHeight: 1.14
    letterSpacing: "0"
  body:
    fontFamily: "TH Sarabun New, THSarabunNew, TH SarabunPSK, THSarabunPSK, Sarabun, Noto Sans Thai, Leelawadee UI, Tahoma, Arial, sans-serif"
    fontSize: "1.58rem"
    fontWeight: 400
    lineHeight: 1.55
    letterSpacing: "0"
  label:
    fontFamily: "TH Sarabun New, THSarabunNew, TH SarabunPSK, THSarabunPSK, Sarabun, Noto Sans Thai, Leelawadee UI, Tahoma, Arial, sans-serif"
    fontSize: "1.26rem"
    fontWeight: 900
    lineHeight: 1.2
    letterSpacing: "0"
rounded:
  md: "8px"
spacing:
  xs: "8px"
  sm: "12px"
  md: "16px"
  lg: "24px"
  xl: "34px"
  section: "76px"
components:
  button-primary:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.paper}"
    rounded: "{rounded.md}"
    padding: "11px 16px"
  button-ghost:
    backgroundColor: "{colors.paper}"
    textColor: "{colors.ink}"
    rounded: "{rounded.md}"
    padding: "11px 16px"
  tag:
    backgroundColor: "#e8f7f4"
    textColor: "{colors.teal-dark}"
    rounded: "{rounded.md}"
    padding: "4px 9px"
  panel:
    backgroundColor: "{colors.paper}"
    textColor: "{colors.ink}"
    rounded: "{rounded.md}"
    padding: "18px"
---

# Design System: TC4 Economics Sprint

## 1. Overview

**Creative North Star: "The Night Study Control Room"**

The system should feel like a focused night-study command center: graph instruments on one side, clean controls on the other, and enough visual voltage to keep a tired student awake without glare. It is a product interface with a brand-level first impression. The page may feel dramatic, but it must always help the learner read, remember, calculate, or check an answer faster.

This design rejects the dry PDF dump, the generic SaaS landing page, the childish quiz game, and the dark visual gimmick that sacrifices readability. The interface earns its energy through animated graphs, crisp state feedback, and confident hierarchy rather than decorative clutter.

**Key Characteristics:**
- Sharp Thai-first readability with English economics terms left intact.
- High-contrast study surfaces with energetic teal, coral, amber, violet, blue, and green accents.
- Dense but organized product panels for calculation, drills, and active recall.
- Motion that supports graph comprehension and state changes, with reduced-motion support.
- Exam credibility: formulas, labels, and worked examples must look exact and calm even inside a vivid composition.

## 2. Colors

The palette is a cool study surface anchored by dark ink, with saturated teaching colors assigned to graph roles and learning states.

### Primary
- **Control-Room Ink** (`#182033`): Primary text, top-level buttons, brand mark fill, and high-trust UI chrome.
- **Circuit Teal** (`#13a99a`): Supply lines, success accents, active learning cues, and the main fresh accent.
- **Teal Signal Dark** (`#0b756e`): Small labels and accent text where teal needs to remain readable.

### Secondary
- **Exam Coral** (`#f06449`): Demand lines, warnings, attention points, and short urgent labels.
- **Recall Amber** (`#f6bd41`): Equilibrium highlights, producer surplus, and active recall emphasis.
- **Welfare Green** (`#4c9f70`): Correct states, welfare gains, and positive externality cues.

### Tertiary
- **Ceiling Violet** (`#7567c8`): Price ceiling, constraints, alternate states, and focused interventions.
- **Graph Blue** (`#2f80ed`): PPF, secondary graph annotation, and neutral analytical emphasis.

### Neutral
- **Paper White** (`#ffffff`): Main cards, panels, nav, and readable content surfaces.
- **Cool Study Surface** (`#f5f7fb`): Page background and quiet reading field.
- **Fine Divider** (`#dbe2ee`): Borders, grid lines, and input outlines.
- **Muted Explanation** (`#5c667a`): Secondary prose and helper text only.

### Named Rules

**The Graph Role Rule.** Demand is coral, supply is teal, constraints are violet, and welfare/correctness is green. Do not swap these roles for decoration.

**The Energy Budget Rule.** Saturated colors should explain state, category, or graph meaning. If a color does not teach, calculate, warn, or confirm, remove it.

## 3. Typography

**Display Font:** TH Sarabun New, TH SarabunPSK, Sarabun, Noto Sans Thai, Leelawadee UI, Tahoma, Arial, sans-serif  
**Body Font:** TH Sarabun New, TH SarabunPSK, Sarabun, Noto Sans Thai, Leelawadee UI, Tahoma, Arial, sans-serif  
**Label/Mono Font:** TH Sarabun for interface labels; formulas use compact inline code styling for numeric clarity.

**Character:** The TH Sarabun-first system gives the site a more formal Thai academic register while keeping English economics terms readable. Weight, spacing, and panel rhythm carry hierarchy instead of decorative font pairing.

### Hierarchy
- **Display** (700, `3.48rem`, `1.03`): Hero headline only. It should feel decisive but never overflow mobile widths.
- **Headline** (700, `2.5rem`, `1.08`): Major section headings and exam-lab titles.
- **Title** (700, `1.66rem`, `1.14`): Card, panel, visual, and quiz headings.
- **Body** (400, `1.34rem`, `1.55`): Notes, explanations, answer feedback, and Thai prose. Keep long reading blocks within a comfortable measure.
- **Label** (900, `1.12rem`, uppercase where already used): Kicker labels, form labels, tags, and compact status text.

### Named Rules

**The Thai Legibility Rule.** Never reduce line-height or letter spacing to create drama. Thai reading clarity beats density.

**The Formula Calm Rule.** Formulas can be highlighted, but their typography stays stable, aligned, and unambiguous.

## 4. Elevation

The system uses a hybrid of tonal layering and measured shadow. Most surfaces are flat white with a clear border. Shadow appears on large panels and hero pieces to separate working zones from the background, not to make every card float.

### Shadow Vocabulary
- **Hero / Major Panel Shadow** (`0 10px 14px rgba(24, 32, 51, 0.10)`): Use only for major immersive surfaces like the hero graph or primary panels.
- **Soft Card Shadow** (`0 4px 10px rgba(24, 32, 51, 0.05)`): Use for repeated visual cards or practice containers when separation is needed.
- **Subtle Lift Shadow** (`0 8px 14px rgba(24, 32, 51, 0.08)`): Use sparingly for hover lift states.

### Named Rules

**The Workbench Rule.** Panels can feel solid and elevated; small controls should rely on border, fill, and focus state rather than wide decorative shadows.

## 5. Components

### Buttons
- **Shape:** Gently squared controls (`8px` radius).
- **Primary:** Control-Room Ink background with Paper White text, bold label, and `11px 16px` padding.
- **Hover / Focus:** Subtle translate lift on hover; focus should use a visible outline or color ring, not only movement.
- **Secondary / Ghost:** Paper White background, Fine Divider border, and Control-Room Ink text.

### Chips
- **Style:** Light teal field (`#e8f7f4`) with Teal Signal Dark text and compact pill-like padding.
- **State:** Use chips for formula families, graph roles, and status labels, not random decoration.

### Cards / Containers
- **Corner Style:** Consistent `8px` radius.
- **Background:** Paper White or Cool Study Surface depending on hierarchy.
- **Shadow Strategy:** Major containers may use the shadow vocabulary; repeated small content should prefer borders.
- **Border:** Fine Divider (`#dbe2ee`) anchors most panels and cards.
- **Internal Padding:** Small cards use `14px-18px`; major sections use broad vertical space.

### Inputs / Fields
- **Style:** Cool Study Surface fill, Fine Divider border, `8px` radius, and at least `42px` height.
- **Focus:** Teal border plus a soft teal focus ring.
- **Error / Disabled:** Error states must pair color with feedback text. Disabled controls should visibly reduce contrast without becoming unreadable.

### Navigation
- **Style:** Sticky white topbar with brand mark, compact nav links, and a blurred surface.
- **Typography:** Bold, small product labels.
- **Default / Hover:** Muted explanation color at rest; ink text on hover with a light teal background.
- **Mobile:** Topbar becomes a stacked layout with wrap-safe links.

### Graph Canvas
- **Style:** Graph canvases are framed working surfaces with labels, grids, and role colors.
- **Behavior:** Animation may make equilibrium and welfare feel alive, but labels must remain readable and reduced-motion must preserve the content.

## 6. Do's and Don'ts

### Do:
- **Do** keep the hybrid promise: product-grade controls with brand-level energy.
- **Do** use coral for demand, teal for supply, violet for price controls, and green for correctness/welfare.
- **Do** keep Thai prose comfortably spaced and formulas visually calm.
- **Do** attach every animated or saturated element to a learning purpose.
- **Do** make active recall easy to reach: quiz, blanks, flashcards, and calculation drills should feel like core product surfaces.

### Don't:
- **Don't** make this feel like a dry PDF dump.
- **Don't** make this feel like a generic SaaS landing page.
- **Don't** make this feel like a childish quiz game.
- **Don't** use a dark visual gimmick that sacrifices readability.
- **Don't** use decorative effects that distract from formulas, graphs, or answer feedback.
- **Don't** ship inaccurate or unverified economics statements, even if the visual result looks stronger.
