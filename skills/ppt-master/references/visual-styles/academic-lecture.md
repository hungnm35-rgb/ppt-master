# Visual style: academic-lecture

Structured, rigorous, and highly legible educational lecture style distilled from Vietnamese high-school mathematics and STEM courseware. Clean card framing, floating pill badges, left spine identity, and precise 3D vector geometry.

---

## 1. Shape & decoration

- **Left spine accent bar**: Every content slide carries a vertical accent bar at the left edge (`x=0, y=0, width=12-14px, height=100%`) filled with the primary deep navy tone. It creates an unbroken deck-wide identity spine.
- **Header structure with accent underline**:
  - Top category/breadcrumb tracker in bold all-caps (warm amber accent).
  - High-contrast slide title (deep navy or dark charcoal).
  - Compact horizontal underline pill (`width=65-80px, height=4-5px`, rx=2px) in warm amber accent directly under the title.
- **Card system with floating pill badges**:
  - Container card: Rounded rectangle (`rx=10-14px`) in crisp white (`#FFFFFF`) or subtle semantic pastels (`#FCEEE6` peach for activities, `#E8EBF3` soft navy for examples, `#F1F5F9` cool gray for options), bordered with a hairline stroke (`#CBD5E1`).
  - **Floating pill badge (signature motif)**: An all-caps label pill (`rx=12-14px`, height `24-28px`, padding `12-16px`) placed floating and overlapping the card's top border (`y_badge = y_card - 12px` to `14px`) filled with a solid semantic hue and white text:
    - `"ĐỊNH NGHĨA"` / `"TÍNH CHẤT"`: Deep Navy or Emerald Green.
    - `"HOẠT ĐỘNG"` / `"LUYỆN TẬP"`: Warm Amber Orange.
    - `"PHƯƠNG PHÁP"`: Royal Purple or Deep Navy.
    - `"VÍ DỤ"`: Deep Navy.
    - `"CHÚ Ý"` / `"LƯU Ý"`: Crimson Red.
- **Footer running frame**:
  - Subtle hairline separator line (`height=1px`, `#CBD5E1`) at `y ≈ 504pt` (or `y ≈ 675px` on 720p).
  - Left breadcrumb: Grade, curriculum, chapter, and lesson title in muted slate (`#64748B`, 11-12pt).
  - Right page indicator: Single page number in muted slate (`#64748B`, 11-12pt), right-aligned.
- **2x2 Interactive quiz grid**:
  - Four independent question cards in a 2x2 quadrant layout.
  - Each question card contains a concise question stem and 4 option pills (A, B, C, D) arranged in 2 columns x 2 rows.
  - Correct option highlighted with emerald green stroke (`#059669`) and soft green tint (`#DCFCE7`), while incorrect options remain neutral cool gray (`#F1F5F9`).
- **Whitespace rhythm**:
  - Balanced padding (16-24px inside cards), clear 20-30px gutters between columns.
  - Asymmetric 2-column split (50/50 or 55/45) pairing formal theory on the left with spatial geometric drawings on the right.

## 2. Typography character

- **Dual-font academic pairing**:
  - **UI, headings, prose, and instructions**: Clean, neutral, high-legibility sans-serif (`Arial`, with `'Segoe UI'`, `Tahoma` fallbacks).
  - **Mathematical variables and geometric notation**: Classical serif italic (`Times New Roman`) for point labels ($A, B, C, D, S$), lines ($d, a, b$), planes ($(P), (Q), (\alpha)$), vectors ($\vec{a}, \vec{u}$), and algebraic variables ($x, y, z$).
- **Strict typographic hierarchy**:
  - Slide title: 20–24pt, Bold.
  - Section subheads / Card headings: 16–18pt, Bold.
  - Primary body text: 14–16pt, Regular/Medium, line spacing 1.2–1.3.
  - Floating pill badge text: 11–13pt, Bold, ALL-CAPS.
  - Secondary metadata & footers: 11–12pt, Regular.

## 3. Using the deck's colors

- **Primary tone**: Deep Navy Blue (`#1E3A8A`) — left spine bar, main titles, core theory cards, example headers.
- **Accent tone**: Warm Amber Orange (`#EA580C`) — tracker kicker, title underline pill, activity/exercise badges, key callout boxes.
- **Categorical semantic tones**:
  - Emerald Green (`#059669`): Correct answer highlights, positive definitions, verified properties.
  - Royal Purple (`#7C3AED`): Mathematical method steps, vector transformations, decomposition rules.
  - Crimson Red (`#DC2626`): Warnings, common pitfalls, non-coplanar / perpendicularity counter-examples.
  - Charcoal (`#1F2937`): Primary high-contrast body text.
  - Slate Muted (`#64748B`): Running footers, secondary annotations, subtle coordinate axes.
  - Border Slate (`#CBD5E1`): Card frames, dividers, hairline rules.

## 4. Texture / elevation

- Crisp flat vector cards with deliberate hairline borders (`#CBD5E1`, 1-1.5px).
- Zero artificial blur or skeuomorphic drops; elevation is achieved through the physical overlap of the floating pill badge across the card boundary and clean background contrast (`#F8FAFC` canvas vs `#FFFFFF` cards).

## 5. 3D Geometry drawing language

- **DrawingML Native Vector Fidelity**: All geometric figures (tetrahedrons, pyramids, parallelepipeds, intersecting planes, coordinate frames) are built from native SVG lines, polygons, and text elements.
- **Edge conventions**:
  - Visible edges: Solid lines (`stroke-width=1.5-2px`, color `#1F2937` or `#1E3A8A`).
  - Hidden / occluded edges: Dashed lines (`stroke-dasharray="4 3"` or `"3 3"`, `stroke-width=1.2-1.5px`, color `#1F2937` or `#64748B`).
  - Auxiliary lines & intersection lines: Highlighted with accent color (`#EA580C` or `#0284C7`), solid or dashed.
- **Vertex points & labels**:
  - Vertex labels positioned 8–12px away from the vertex point in italic *Times New Roman*, ensuring no line intersection.
  - Planes represented by skewed parallelograms with semi-transparent tints (`fill-opacity=0.08-0.15`).

## 6. Paired image-rendering

`minimalist-swiss` or `flat` — clean geometric vector figures and photographic real-world hook imagery.

## 7. Illustration propensity

**supportive** — real-world photography used selectively for the opening hook (tripod, architecture, crane, physics forces) and closing real-world application; mathematical geometry remains pure native vector.
