# Hardware description

This folder describes how the FunctionalSkin prototype was built: a 120 × 60 cm wooden façade panel made of 32 folded plywood tiles, coated with a radiative cooling paint. A second, smaller prototype made of heat-pressed mycelium tiles is described at the end. The design files are linked below, and the full reasoning behind the design is in the final report (`Documents`, Part A).

**Key dimensions of the panel:** tile size 15 × 15 cm, 5.5 mm plywood, 135° fold, protrusion angle 75°, maximum cavity depth 8 cm, backboard 120 × 60 cm.

## Parts List

| Description | Ref. number | Amount | Supplier |
|-------------|-------------|--------|----------|
| Plywood sheets, 5.5 mm thick, 65 × 34 cm (6 tiles per sheet, indoor grade) | Lightply | 6 (to verify, 32 tiles needed) | Hornbach |
| Spruce battens, rough, 22 × 48 × 2100 mm | KONSTA Vuren panlat ruw | about 6 (estimate: 5 × 120 cm + 9 × 60 cm) | Hornbach |
| Polyurethane construction adhesive (EN 204 class D4) | Bison Konstruktielijm | 1 | [fill in] |
| Waterproof wood glue (EN 204 class D3) | Pattex | 1 | [fill in] |
| Nails, 35 mm (backboard) | [fill in] | 1 box | [fill in] |
| Nails, 15 mm (tiles, slats) | [fill in] | 1 box | [fill in] |
| White acrylic sealant (for seams) | Kelfort acrylkit anti-crack | 1 | [fill in] |
| Radiative cooling paint | CryoPaint® | [fill in] | Cryo X |
| PLA filament (assembly jig) | [fill in] | [fill in] | [fill in] |
| Aluminium for the mould and 3D inserts (mycelium prototype) | [fill in] | [fill in] | [fill in] |

## Fabrication methods and tools

- **CNC mill:** CNC-Step High-Z S720T (open-source CNC router), with three bits: 90° V-groove, flat-top and 45° V-groove
- **CAD/CAM:** Autodesk Fusion 360 (version 2704.1.15) for the tile design and toolpaths; the toolpath is posted to G-code for the CNC
- **3D printer** for the assembly jig (PLA); PLA prints were also used to test the corner joints before milling
- **Handheld clothing steamer:** Tefal Pure POP DT2022
- **Nail gun:** Bostitch Tacker SB-2IN1-E
- **Saw** for the 45° strips and slats, **clamps**, **paintbrush**
- **Heat press** (Carver) for the mycelium tiles

### Design files

| File | Use | Link |
|------|-----|------|
| Wooden tile | Model for CNC | https://a360.co/4hJ9jBd |
| Assembly jig | Model for 3D printing | https://a360.co/4hM8A3H |
| Aluminium mould | Model for CNC (mycelium pressing) | https://a360.co/4yFomTX |

## Build instructions

The panel is made in four stages. The whole process for one 120 × 60 cm panel took more than a full day of labour.

### 1. Mill the tiles

1. Clamp a 65 × 34 cm sheet of 5.5 mm plywood on the CNC. Six tiles are milled per sheet. Make two inverse tile versions, 16 of each (32 tiles in total).
2. Run the three milling operations:
   - **90° V-groove bit:** cuts the angle used to mount the tile to the backboard.
   - **Flat-top bit:** cuts the contour of the tile.
   - **45° V-groove bit:** cuts the fold line. Cut to a depth that leaves about **1 mm** of material, so the outer veneer stays intact. This gives a seamless outer layer after folding.
3. Spindle speed: 26,000 rpm for both V-groove bits and 32,000 rpm for the flat-top bit.
4. Saw a 5 mm strip off each tile at the 45° angle, so the tiles connect without gaps on the backboard.

### 2. Fold and glue the tiles

1. Moisten the fold groove with a wet cloth.
2. Heat the groove with the clothing steamer for about **2 minutes**, until the wood fibres become flexible.
3. While still applying heat, fold the tile to **135°**.
4. Hold the tile in this position in the 3D-printed jig, bond with polyurethane construction adhesive (Bison, D4) and clamp for **4 hours**, following the manufacturer's manual.

### 3. Build the backboard and assemble

1. Build the backboard (120 × 60 cm) from 48 × 22 mm spruce battens: 5 battens run lengthwise and 9 across. Join with waterproof wood glue (Pattex, D3) and 35 mm nails.
2. Attach the tiles to the backboard with wood glue and 15 mm nails.
3. Add slats sawn at 45° between each pair of inverse tiles for extra stability (wood glue and 15 mm nails).
4. Where the tiles leave large openings at the sides, add triangular plywood pieces and glue them with construction adhesive (Bison, D4).
5. Fill the remaining seams with white acrylic sealant (Kelfort) once the tiles are mounted.

### 4. Coat the panel

1. Paint the outside facets and the sides with **three layers** of CryoPaint, applied with a brush for full coverage.
2. Let each layer dry for at least **24 hours** before applying the next.
3. Leave the inner cavity side uncoated.

### Tips from our build

- The first laser-cut prototype from scrap plywood left gaps between the tiles. Milling a groove while keeping the outer veneer intact solved this.
- Print the tile in PLA first to check the corner joints. At first the top corners did not align. Re-orienting their angles gave a clean fold at 135°.
- The folding step is manual, which can affect the accuracy of the folded geometry.
- Indoor plywood is not suitable for outdoor use. Use it for prototypes only. A thicker solid timber such as Douglas fir would require larger tiles (e.g. 30 × 30 cm).

## Second prototype: heat-pressed mycelium tiles

A small panel (about 30 × 30 cm, 3 × 3 tiles) was assembled from mycelium composite tiles, using waste blocks from another student's research. It is uncoated and for indoor display only.

1. **Make the aluminium mould:**
   1. Open the mould model in Fusion 360 (link in the design files table). It consists of a flat square mould plus 3D inserts (a positive and a negative part, each 100 × 100 mm) with a wavy shape. The wide wave angle lets a standard cubic block be pressed without growing it in a shaped mould.
   2. Generate the toolpaths in Fusion 360 and post them to G-code for your CNC. Machine: CNC-Step High-Z S720T (open-source CNC router), Bits: Flat-top milling bit with three cutting edges. Spindle speed and feed rate: [fill in]. Cutting depth per pass: [fill in].
   3. Mill the positive and negative inserts from aluminium (grade and thickness: [fill in]).
   4. Check that the two inserts fit together, and that they fit in the flat mould and the heat press.
2. **Grow:** *Fomes inzengae* on hemp shives in 10 × 10 × 3 cm acrylic moulds, 13 days at 30 °C. Remove from the mould and grow a skin for 7 days, then air dry for about 2.5 weeks.
3. **Press:** heat press (Carver) at 115 kN with the aluminium mould and inserts, 150 or 190 °C for 5 or 20 minutes. The panel prototype was pressed for 10 minutes at 190 °C.
4. **Assemble:** nail and glue the tiles to a timber frame.

Full details and test results are in the final report, Part B.3.
