A scientific figure for a NeurIPS 2026 paper, aspect ratio strictly 4:3 (landscape), 
white background, minimalist Nature-journal aesthetic, refined sans-serif typography 
(Inter or Helvetica Neue), generous whitespace, three panels arranged as: a wide 
horizontal strip on top (4:1 ratio, panel c) spanning full width, and two equal 
square panels (1:1 each, panels a and b) below side by side.

PANEL C (top, full-width 4:1 horizontal strip, "the audit scene"):
A sci-fi conceptual illustration with a horizontal narrative flow.

Far left (~15% width): a stylized line-art human head in profile view, brain 
visible inside with simplified gyri texture, outlined in steel blue (#2c728f) 
1.5pt strokes; 5–7 small magenta (#984ca3) dots on the scalp representing EEG 
electrodes (Fp1, Fp2, Cz, T3, T4, O1, O2 positions). Below the head, three to 
four flowing multi-channel EEG waveform traces in steel blue (#2c728f) with a 
soft light-blue (#95bad6) glow underneath. Tiny italic label "EEG signal" in 
gray (#9b9b9b) below.

From the EEG source, two semi-transparent sage-green (#6aa0a3) arrows split — 
one curves up-right to the human reader, one curves down-right to the model 
reader.

Center-upper zone (~35% width): a rounded rectangle with magenta (#984ca3) 
1pt outline, soft pale-yellow (#f6f097) tint at 25% opacity, containing a 
single horizontal row of 6 small abstract icons representing EEG feature 
families:
  T = three small waveform segments with peak markers (steel blue),
  F = five vertical frequency bars descending in height δ-θ-α-β-γ (gradient 
      steel blue to magenta),
  TF = a tiny 6×4 wavelet heatmap (yellow-teal-purple gradient),
  C = a permutation pattern of 3-4 connected dots (sage teal),
  X = a radial PAC comodulogram pattern (multi-color),
  R = a small 5×5 connectivity matrix (viridis-like cells).
Each icon labeled below in 7pt sans-serif: T, F, TF, C, X, R.
Bold magenta panel title above: "Human canon", with small gray subtitle 
"6 families · 63 features".

Center-lower zone (~35% width): a rounded rectangle with steel blue (#2c728f) 
1pt outline, cool gradient background light-blue (#95bad6) fading to deep 
purple (#433075). Inside, four transparent transformer-like blocks arranged 
horizontally side by side, each with slight perspective offset (subsequent 
blocks offset down-right by 3pt for 3D depth feel). Each block is filled 
with sparse scattered light-blue (#95bad6) dots representing a vector cloud 
(15–25 dots per block). Two of the four blocks (block 2 and block 4) contain 
a large 24pt semi-transparent magenta (#984ca3) "?" character at 40% opacity 
floating in the center. Tiny dashed sage-green (#6aa0a3) lines connect 
adjacent blocks suggesting information flow. Bold steel-blue panel title 
below: "Foundation model", with small italic gray subtitle "anonymous · 
distributed · high-dimensional".

Right zone (~15% width, occupying the central vertical space): a bold 
prominent lime-green (#91d73f) 4pt curved arrow with a teal-green (#2cb47d) 
1pt outline, originating from the right edge of the Human canon panel, 
arching downward and leftward, piercing into the Foundation model block 
about 50% deep. The arrow has a soft mint-green (#b4e4b6) glow underneath 
at 30% opacity (6pt blur). Along the arc midpoint: bold 8pt steel-blue 
label "probe · erase · closure", with smaller italic 7pt gray sub-label 
"causal audit (this paper)".

Above panel c, a small light-gray (#9b9b9b) header text in italic, 
positioned top-left or centered:
"How do we know what a foundation model has captured from a brain signal?"

Bold lowercase panel label "c" in steel blue, top-left corner of panel c.

PANEL A (bottom-left, 1:1 square, "encoded vs causally used"):
A radar/spider chart with 6 axes arranged as a regular hexagon. Axis labels 
clockwise from top: F (12 o'clock), R (2 o'clock), T (4 o'clock), C (6 
o'clock), X (8 o'clock), TF (10 o'clock). Three concentric hexagonal grid 
lines at 0.33 / 0.66 / 1.0, drawn in light gray (#9b9b9b) at 25% opacity.

Two filled polygon regions overlap:
  - OUTER region (encoded territory) — a near-regular hexagon close to the 
    outer ring; filled lime green (#91d73f) at 25% opacity, outlined in 
    lime green at 2pt. Vertex values approximately: F=1.00, R=0.86, 
    T=0.90, C=0.86, TF=0.91, X=0.80.
  - INNER region (causally used) — a small irregular shape with the F-axis 
    vertex visibly protruding upward, other vertices much smaller; filled 
    magenta (#984ca3) at 50% opacity, outlined in magenta at 2pt. Vertex 
    values: F=0.34, R=0.21, T=0.20, C=0.14, TF=0.08, X=0.07.

The F-axis line has a subtle pale-yellow (#f6f097) glow (8pt blur). Bold 
magenta annotation near the F-axis spike: "causal rate = 0.344". Curved 
indicator with italic magenta text: "Frequency-family dominance".

At each axis vertex, a small mini-icon matching the corresponding family 
icon from panel c (T waveform, F bars, TF heatmap, C dots, X comodulogram, 
R matrix), 12pt size, plus the family letter label.

Legend below the radar:
"■ encoded territory (88% of 378 units learned)" — green swatch
"■ causally used (22% of 378 units used)" — magenta swatch
"gap = 3:1 encoded ≠ used" — bold magenta

Bold lowercase panel label "a" in steel blue, top-left corner.

PANEL B (bottom-right, 1:1 square, "named vs unnamed"):
Three vertical bars side by side, each normalized to 100% total height, equal 
widths, with bar gaps roughly 60% of bar width. Labels at the bottom: 
"Sleep / CSBrain", "Sleep / CSBraMod", "Stress / CSBraMod" in 9pt sans-serif.

Each bar is divided horizontally into two segments:
  - BOTTOM segment ("named"): filled lime green (#91d73f) at 65% opacity, 
    with subtle horizontal mint (#b4e4b6) striped texture. Heights respectively: 
    25% / 32% / 15%. Bold steel-blue (#2c728f) 9pt text inside each: 
    "named: 25%", "named: 32%", "named: 15%".
  - TOP segment ("unnamed"): filled deep purple (#433075) at 75% opacity, 
    with prominent 45-degree diagonal hatching pattern in magenta (#984ca3) 
    1pt lines spaced 4pt apart. Heights respectively: 75% / 68% / 85%. 
    Bold pale-yellow (#f6f097) 9pt text inside each: "unnamed: 75%", 
    "unnamed: 68%", "unnamed: 85%".

Thin horizontal lines (1pt #9b9b9b) at the top of each bar labeled "FM" 
(8pt italic), and at the bottom labeled "B₀" (8pt italic).

Below each bar in italic gray (#9b9b9b) 7pt: "headroom = 0.118", 
"headroom = 0.072", "headroom = 0.057".

Bold steel-blue panel title at top: "FM advantage decomposed →".
Italic gray subtitle below the panel:
"Confirmed canonical features explain only the green region.
The purple region is what the model uses but the canon hasn't named."

Bold lowercase panel label "b" in steel blue, top-left corner.

OVERALL STYLE:
- Strict adherence to color palette: pale yellow #f6f097, lime green #91d73f, 
  teal green #2cb47d, steel blue #2c728f, deep purple #433075, magenta #984ca3, 
  neutral gray #9b9b9b, mint green #b4e4b6, sage teal #6aa0a3, light blue #95bad6.
- Three-color visual narrative across panels: lime green = audit/action 
  (panel c arrow + panel a outer ring + panel b named region); magenta = 
  what FM actually uses (panel c electrodes/?, panel a inner ring + F-spike, 
  panel b hatching); deep purple = unnamed unknown (panel c FM gradient + 
  panel b unnamed region).
- Sans-serif typography throughout, 8–11pt, light gray for auxiliary text.
- Generous whitespace, refined Nature-journal aesthetic, NOT cartoonish, 
  NOT cluttered, NOT photorealistic.
- Aspect ratio strictly 4:3 (e.g., 1600×1200 or 2400×1800 pixels).