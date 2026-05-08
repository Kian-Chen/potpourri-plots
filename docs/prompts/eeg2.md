A scientific figure for a NeurIPS 2026 paper, aspect ratio approximately 5:2 
(very wide horizontal banner, e.g., 2400×1000 or 2500×1050 pixels), white 
background, minimalist Nature-journal aesthetic, refined sans-serif typography 
(Inter or Helvetica Neue), generous whitespace.

LAYOUT: three panels arranged as:
- Panel c: top, full-width horizontal strip, internal aspect ratio 5:1
- Panel a: bottom-left, square (1:1)
- Panel b: bottom-right, very wide horizontal strip (4:1)
The bottom row (panel a + small gap + panel b) has the same width as panel c. 
All three panels in the bottom and top rows have equal HEIGHT.

PANEL C (top, full-width 5:1 horizontal strip, "the audit scene"):
A sci-fi conceptual illustration with horizontal narrative flow, divided into 
four left-to-right zones.

[Zone 1, ~12% width, far left] A stylized line-art human head in profile 
view, brain visible inside with simplified gyri texture, outlined in steel 
blue (#2c728f) 1.5pt strokes; 5–7 small magenta (#984ca3) dots on the scalp 
representing EEG electrodes. Below the head, three to four flowing 
multi-channel EEG waveform traces in steel blue (#2c728f) with a soft 
light-blue (#95bad6) glow underneath. Tiny italic gray (#9b9b9b) label 
"EEG signal" below the waveforms.

From the EEG source, two semi-transparent sage-teal (#6aa0a3) arrows split: 
one curves up-right, one curves down-right.

[Zone 2, ~32% width, center-upper] A rounded rectangle with magenta 
(#984ca3) 1pt outline and pale-yellow (#f6f097) tinted background at 25% 
opacity. Inside, a single horizontal row of 6 small abstract icons:
  T = three small waveform segments with peak markers (steel blue),
  F = five vertical frequency bars descending δ-θ-α-β-γ (gradient blue→magenta),
  TF = a tiny 6×4 wavelet heatmap (yellow-teal-purple gradient),
  C = 3-4 connected dots forming a permutation pattern (sage teal),
  X = a radial PAC comodulogram pattern,
  R = a small 5×5 connectivity matrix.
Each icon labeled below in 7pt: T, F, TF, C, X, R. 
Bold magenta panel title above: "Human canon", small gray subtitle below: 
"6 families · 63 features".

[Zone 3, ~32% width, center-lower] A rounded rectangle with steel-blue 
(#2c728f) 1pt outline, cool gradient background fading from light-blue 
(#95bad6) on left to deep purple (#433075) on right. Inside, four 
transparent transformer-style blocks arranged horizontally side-by-side, 
each with slight perspective offset (subsequent blocks offset down-right 
by 3pt for 3D depth). Each block filled with 15-25 sparse scattered 
light-blue (#95bad6) dots representing a high-dimensional vector cloud. 
Two of the four blocks (block 2 and block 4) contain a large 24pt 
semi-transparent magenta (#984ca3) "?" character at 40% opacity floating 
in their center. Thin dashed sage-teal (#6aa0a3) lines connect adjacent 
blocks. Bold steel-blue title below: "Foundation model", italic gray 
subtitle: "anonymous · distributed · high-dimensional".

[Zone 4, ~24% width, right, audit arrow occupies the central vertical] 
A bold prominent lime-green (#91d73f) 4pt curved arrow with teal-green 
(#2cb47d) 1pt outline, originating from the right edge of the Human canon 
panel, arching downward and leftward, piercing into the Foundation model 
block about 50% deep. Soft mint-green (#b4e4b6) glow underneath at 30% 
opacity (6pt blur). Along the arc midpoint: bold 8pt steel-blue label 
"probe · erase · closure", with smaller italic 7pt gray sub-label 
"causal audit (this paper)".

Above panel c, small light-gray (#9b9b9b) header text in italic 9pt, 
left-aligned: "How do we know what a foundation model has captured from 
a brain signal?"

Bold lowercase panel label "c" in steel blue, top-left corner.

PANEL A (bottom-left, 1:1 square, "encoded vs causally used"):
A radar/spider chart with 6 axes arranged as a regular hexagon. Axis labels 
clockwise from top: F (12 o'clock), R (2 o'clock), T (4 o'clock), C (6 
o'clock), X (8 o'clock), TF (10 o'clock). Three concentric hexagonal grid 
lines at 0.33 / 0.66 / 1.0 in light gray (#9b9b9b) at 25% opacity.

Two filled polygon regions overlap:
  - OUTER region (encoded territory) — near-regular hexagon close to outer 
    ring; lime green (#91d73f) at 25% opacity, 2pt outline. Vertices: 
    F=1.00, R=0.86, T=0.90, C=0.86, TF=0.91, X=0.80.
  - INNER region (causally used) — small irregular shape with F vertex 
    visibly protruding upward; magenta (#984ca3) at 50% opacity, 2pt 
    outline. Vertices: F=0.34, R=0.21, T=0.20, C=0.14, TF=0.08, X=0.07.

The F-axis line has a subtle pale-yellow (#f6f097) glow (8pt blur). Bold 
magenta annotation near the F-axis spike: "causal rate = 0.344". Curved 
indicator with italic magenta text: "Frequency-family dominance".

At each axis vertex, a small mini-icon matching the corresponding family 
icon from panel c, 12pt size, plus the family letter label.

Legend below the radar:
"■ encoded territory (88% of 378 units learned)" — green swatch
"■ causally used (22% of 378 units used)" — magenta swatch
"gap = 3:1 encoded ≠ used" — bold magenta

Bold lowercase panel label "a" in steel blue, top-left corner.

PANEL B (bottom-right, 4:1 horizontal strip, "FM advantage decomposed"):
Fifteen narrow vertical bars arranged in 5 task groups × 3 model bars per 
group, left-to-right. Group separators (wider gaps) between adjacent task 
groups; tighter spacing within each group of 3 bars. All bars normalized 
to 100% total height.

Group 1 (Task: MDD): 3 bars
  - Bar 1 (M1 CSBrain): SATURATED — gray (#9b9b9b) at 30% opacity with 
    diagonal hatching, 1.5pt dashed gray outline, no internal segments. 
    Tiny italic gray "saturated" above the bar.
  - Bar 2 (M2 CSBraMod): SATURATED — same style as Bar 1.
  - Bar 3 (M3 TBD): PENDING — extremely faint 0.5pt dotted gray outline 
    at 30% opacity, no fill, tiny gray "pending" above.

Group 2 (Task: Sleep): 3 bars
  - Bar 1 (M1 CSBrain): INTERPRETABLE — bottom 25% lime green (#91d73f) 
    at 65% opacity with mint horizontal stripes labeled "25" in bold 
    steel-blue 7pt; top 75% deep purple (#433075) at 75% opacity with 
    45° magenta (#984ca3) hatching labeled "75" in bold pale-yellow 7pt. 
    Headroom annotation below: "h=0.118" in italic gray 6pt.
  - Bar 2 (M2 CSBraMod): INTERPRETABLE — 32% green / 68% purple, same 
    style. "h=0.072" below.
  - Bar 3 (M3 TBD): PENDING — same as Group 1 Bar 3.

Group 3 (Task: Stress): 3 bars
  - Bar 1 (M1 CSBrain): UNDEFINED — 1.5pt dashed gray outline only, no 
    fill, large em dash "—" in center, italic gray "RC=0" above.
  - Bar 2 (M2 CSBraMod): INTERPRETABLE — 15% green / 85% purple, same 
    style. "h=0.057" below.
  - Bar 3 (M3 TBD): PENDING.

Groups 4 and 5 (Task 4 and Task 5, both TBD): all 6 bars are PENDING 
(faint dotted outlines only).

Below each bar: bold steel-blue 7pt model label "M1" / "M2" / "M3".
Below each task group center: bold steel-blue 8pt task label "MDD" / 
"Sleep" / "Stress" / "Task 4" / "Task 5".

Reference lines: thin 0.5pt gray lines at y=1.0 (FM ceiling) and y=0 
(B₀ baseline), labeled "FM" and "B₀" at far left in italic gray 7pt.

Above panel b: bold steel-blue 9pt title "FM advantage decomposed →". 
Below it, italic gray 7pt subtitle: "3 models × 5 tasks · stacked = 100% 
normalized headroom".

Bottom note in italic gray 7pt: "Confirmed canonical features explain 
only the green region. The purple region is what the model uses but 
the canon hasn't named."

Bold lowercase panel label "b" in steel blue, top-left corner.

OVERALL STYLE:
- Strict color palette: pale yellow #f6f097, lime green #91d73f, teal 
  green #2cb47d, steel blue #2c728f, deep purple #433075, magenta #984ca3, 
  neutral gray #9b9b9b, mint green #b4e4b6, sage teal #6aa0a3, 
  light blue #95bad6.
- Three-color visual narrative across panels: lime green = audit/action 
  (panel c arrow + panel a outer ring + panel b named segments); magenta 
  = FM actually uses (panel c electrodes/?, panel a inner ring + F-spike, 
  panel b hatching); deep purple = unnamed unknown (panel c FM gradient + 
  panel b unnamed segments).
- Sans-serif typography throughout, 6–11pt.
- Generous whitespace, refined Nature-journal aesthetic, NOT cartoonish, 
  NOT cluttered, NOT photorealistic.
- Final aspect ratio approximately 5:2 (e.g., 2400×1000 or 2500×1050 
  pixels), wide horizontal banner format.