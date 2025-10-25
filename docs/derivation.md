# Lawful Derivation: Circle → G₆ → Medians → G₁₂

This note fixes the geometric procedure by which the continuum’s first visible structure is produced. The construction is **compass-lawful**: every step derives from the radius and lawful symmetry.

## 1. Circle and Six Steps (G₆)
- Draw a circle of radius **R**.
- Step the compass around the circumference six times; the points close, defining a regular hexagon.
- Connect adjacent step points to obtain six equilateral triangles; this is the **G₆** lattice (primal family at angles 0°, ±60°).

## 2. Medians (Lawful Correctors)
- For each equilateral cell, draw the three **medians** (from vertices to opposite midpoints). Medians intersect at the centroid.
- The family of medians across the tessellation forms straight, equally spaced lines rotated relative to the primal set.
- Scale relation: the median spacing equals **(√3⁄3)·R** relative to unit constructions, producing a consistent secondary spacing.

## 3. Dual Family (30° Rotation)
- The medians reveal a rotated family at **±30°** relative to the primal (0°, ±60°).
- Extending these lines across the plane yields the dual lattice compatible with the primal spacing.

## 4. Superposition to G₁₂
- Superpose the primal (0°, ±60°) and dual (±30°, 90°, etc.) families.
- The result is **G₁₂**: twelve evenly spaced directional families at 30° increments — a complete directional grammar of the plane.

## 5. Notes on Lawfulness
- No free parameters beyond **R** are introduced; all lengths and angles follow from the invariant act (setting the compass and stepping the circle).
- The derivation is reproducible with ruler and compass or with the provided HTML demonstrations (`src/`).
