---
style_id: academic-lecture
kind: style
summary: High-school mathematics and STEM lecture method sequencing objective roadmap, real-world hook, foundation concepts, 3D geometry axioms, step-by-step methods, mindmap recap, 2x2 quiz checks, and practical homework.
keywords: [lecture, mathematics, stem, high-school, k12, teaching, geometry, quiz, proof]
---

# Academic Lecture — Style Specification

> Method and design defaults only. No project communication contract, brand identity, page structure, or SVG prototypes.

## I. Style Overview

| Property | Value |
|---|---|
| Style Name | Academic Lecture |
| Best Fit | High-school (K12) mathematics, spatial geometry, physics, STEM curriculum lectures, university tutorials, and board-exam prep decks |
| Reusable Intent | Guide students from intuitive real-world observation to rigorous mathematical definitions, theorem-grounded spatial visualizations, step-by-step algorithmic solutions, and instant self-verification |
| Sources | Distilled from Vietnamese national curriculum (KNTT) grade 11–12 spatial geometry courseware (`ban_mau.pptx`), refined for modern widescreen lecture halls |

## II. Communication Method

- **Preferred Mode**: instructional
- **Argument Flow**:
  1. *Contract & Destination*: State observable lesson objectives alongside a 4-pillar chapter roadmap.
  2. *Real-world Hook*: Pose an intuitive real-life phenomenon (e.g. 3-legged tripod stability vs 4-legged table wobble, crane cable tension vectors) that only spatial geometry can resolve.
  3. *Theory Formulation*: Unfold core concepts with precise mathematical definitions, notation rules, and drawing conventions (visible solid lines vs hidden dashed lines).
  4. *Axiomatic Properties*: Introduce each theorem or axiom with direct spatial illustrations before expanding to secondary corollaries.
  5. *Method & Worked Example*: Present the general solution protocol (`PHƯƠNG PHÁP`) immediately followed by an exemplary problem (`VÍ DỤ`) solved step-by-step.
  6. *Taxonomy & Extension*: Classify geometric shapes (tetrahedrons, pyramids, prisms) by their base polygon.
  7. *Synthesis & Consolidation*: Synthesize the entire lesson into a structured mindmap.
  8. *Active Retrieval*: Test understanding with high-density 2x2 multiple-choice question grids with highlighted correct solutions.
  9. *Transfer & Homework*: Assign stratified textbook exercises (basic, intermediate, advanced) plus a real-world exploratory challenge.
- **Page Message Discipline**: One concept, property, or worked example per slide. Multi-step solutions must show Step 1, Step 2, and Conclusion clearly delineated rather than running into continuous walls of text.
- **Mathematical Integrity**: Distinguish geometric entities strictly — points (capital letters $A, B$), lines ($d, a, b$), planes ($(P), (\alpha)$), lengths ($|AB|$), and vectors ($\vec{a}, \vec{AB}$). Never confuse scalar quantities with vector quantities.

## III. Page Role Vocabulary

| Role | Communication Job | Evidence Obligation | Composition Tendency |
|---|---|---|---|
| `Learning objective & roadmap` | Frame lesson goals and 4 thematic modules | State 2–4 observable student competencies; summarize lesson modules with colored numbered badges (1: Navy, 2: Green, 3: Purple, 4: Orange) | Left: objective bullets; Right: 4 stacked rounded cards with colored circle numbers |
| `Real-world hook` | Spark curiosity via everyday spatial puzzles | Present 2 contrasting physical objects or photos (e.g. tripod vs 4-leg desk) with a guiding inquiry | Side-by-side comparative cards with real-world photographs and prompt callout |
| `Geometric concept` | Define spatial entities and conventions | State standard definition, symbolic notation, and projection/drawing rules | Left: definition card with floating badge; Right: geometric diagram with dashed/solid edges |
| `Axiom & property` | Establish foundational geometric truths | Quote official textbook axiom verbatim; state deductive consequences | Split layout: property card on left, 3D geometric figure with highlighted elements on right |
| `Problem method` | Provide general algorithmic solution protocol | State the exact 2-to-3-step mathematical procedure to solve the question type | Floating purple badge (`PHƯƠNG PHÁP`); ordered steps with bold operative verbs |
| `Worked example` | Demonstrate complete step-by-step application | State full problem hypothesis; demonstrate derivation without skipping intermediate steps | Floating navy badge (`VÍ DỤ`); left: problem & step-by-step proof; right: annotated 3D figure |
| `Taxonomy & classification` | Compare geometric solids and families | Enumerate definitions, vertices, edges, faces, and naming conventions | Grid of 3–4 cards, each showing solid name, symbol ($S.ABC$), and 3D wireframe |
| `Mindmap summary` | Consolidate cross-topic relationships | Group the 4 lesson pillars with interconnected conceptual anchors | 4-column card grid or centralized hub with color-coded thematic categories |
| `Multiple-choice check` | Rapid formative assessment for classroom response | Present 4 questions per slide; each with 4 distinct options (A, B, C, D) | 2x2 quadrant grid; correct answer highlighted with green border `#059669` and soft green fill `#DCFCE7` |
| `Homework & transfer` | Guide self-study and real-world connection | Detail textbook exercise numbers by difficulty level; pose open observation task | Left: dual stacked cards (`HOẠT ĐỘNG` in peach, `BÀI THÊM` in soft navy); Right: real-world photo & prompt |

## IV. Evidence & Data Expression

- **3D Spatial Geometry Drawings**:
  - Pure native DrawingML vector rendering (never raster screenshots).
  - Explicit edge occlusion: visible edges solid (`stroke-width=1.5-2px`, `#1F2937`), hidden edges dashed (`stroke-dasharray="4 3"`, `#1F2937` or `#64748B`).
  - Auxiliary and newly constructed lines emphasized with chromatic accent (`#EA580C` amber or `#0284C7` blue).
  - Vertex labels set in italic serif (*Times New Roman*) offset 8–12px from vertices.
- **Mathematical Formula Representation**:
  - Key formulas enclosed in designated contrast formula boxes (`fill="#F0FDF4"` or `#EFF6FF`).
  - Use exact Unicode mathematical symbols (`→`, `·`, `°`, `√`, `⊥`, `∈`, `ℝ`, `Δ`, `∠`).
  - Proof steps structured with leading operational bullets (`• Bước 1:`, `• Bước 2:`, `• Suy ra:`).

## V. Visual System Defaults

- **Preferred Visual Style**: `academic-lecture`
- **Deck Frame Architecture**:
  - *Left Spine*: Constant vertical accent bar at `x=0, y=0, width=13pt, height=100%` filled with primary Deep Navy (`#1E3A8A`).
  - *Header Structure*: Kicker/breadcrumb in warm amber all-caps (`#EA580C`, 11–13pt) + Main title (`#1E3A8A`, 20–24pt) + Underline accent pill (`w=72pt, h=4.3pt`, `#EA580C`).
  - *Footer Running Frame*: Hairline divider (`#CBD5E1`) at bottom + Curriculum metadata on left + Single page number on right (`#64748B`, 11–12pt).
- **Card & Floating Pill Badge System**:
  - Content containers: Rounded rectangle (`rx=10-14px`) in `#FFFFFF` with `#CBD5E1` border.
  - Floating pill badge: `Rounded Rectangle` (`rx=12-14px`, height `24-28px`, white bold all-caps text) placed overlapping top border (`y_badge = y_card - 12px`):
    - `ĐỊNH NGHĨA` / `TÍNH CHẤT`: `#1E3A8A` / `#059669`
    - `HOẠT ĐỘNG` / `LUYỆN TẬP`: `#EA580C`
    - `PHƯƠNG PHÁP`: `#7C3AED`
    - `VÍ DỤ`: `#1E3A8A`
    - `CHÚ Ý` / `LƯU Ý`: `#DC2626`
- **Color Identity Tokens**:
  - Primary: Deep Navy `#1E3A8A`
  - Accent: Warm Amber Orange `#EA580C`
  - Success/Correct: Emerald Green `#059669`
  - Method/Algebra: Royal Purple `#7C3AED`
  - Warning/Pitfall: Crimson Red `#DC2626`
  - Text Primary: Charcoal Dark `#1F2937`
  - Text Secondary/Muted: Slate `#64748B`
  - Card Border: Slate Light `#CBD5E1`
  - Card Tints: Peach `#FCEEE6`, Navy `#E8EBF3`, Cool Gray `#F1F5F9`, Soft Green `#DCFCE7`
- **Typography Pairing**:
  - Headings, UI, Body: `Arial, 'Segoe UI', Tahoma, sans-serif`
  - Math & Geometric Symbols: `Times New Roman, serif` (italic for variables)

## VI. Image & Icon Direction

- **Preferred Image Rendering**: `minimalist-swiss` / `flat`
- **Image Usage**: Reserved for authentic real-world engineering, nature, architecture, and physics applications (e.g. surveying tripods, Egyptian pyramids, suspension bridges, industrial cranes) that ground the abstract geometry. All geometric diagrams remain native vector shapes.
- **Icon Usage**: Minimalist line icons (Tabler/Lucide outline style) at 24–32px to accompany section milestones or instructions.

## VII. Review Focus
<!-- visual-review-trigger: explicit-user-only -->
> Apply this section only after the user explicitly activates visual review. It never triggers that stage.

- Left spine accent bar (`#1E3A8A`) is present and consistent on all content slides.
- Header hierarchy contains the 3 layers: amber kicker, bold title, and orange underline pill.
- Floating pill badges cleanly overlap card top borders without clipping or misalignment.
- Spatial drawings use proper solid/dashed line occlusion standards and offset italic vertex labels.
- Formulas and vector notations use exact Unicode characters without corrupted font glyphs.
- 2x2 quiz questions display clear option pills with verified emerald green highlights on the correct answers.
- Footers maintain unbroken hairline dividers with accurate page numbering.
