# Transversal Lab

Transversal Lab is a practice app for the angle relationships formed when two lines are cut by a transversal. Students drag a transversal and tilt one line while all eight angle measures update live, so the parallel condition can be switched on and off in front of them: with the parallel lock on, the equal and supplementary pairs hold; with the lock off, students watch corresponding pairs drift apart by exactly the tilt, which is the indicator 5.2 evidence that the properties belong to parallel lines only. Around the exploration sit three item modes: naming a highlighted pair, computing a measure with the earning relationship attached, and judging parallel or not from two given measures, including flawed student claims to diagnose.

Math 2201 Unit 8: Properties of Angles and Triangles (indicators 5.1, 5.2, 5.9; the compute mode also serves Section 3's justified measures, 5.8)

## How students use it

- Explore: the transversal slant and the tilt of line b are draggable (sliders mirror the same controls for keyboard users). A live table shows all eight measures, and a pair comparator names any two positions and states whether they are equal, supplementary, or neither right now. Students record cases, state their generalizations in their own words, then turn the lock off and record break it findings.
- Name the Pair: two highlighted angles; the student names the relationship (corresponding, alternate interior, alternate exterior, same-side interior, vertically opposite). Feedback explains the positions.
- Compute with a Reason: one measure given, one marked angle to find, and the relationship must be chosen as part of the answer. Feedback separates the two halves: a right measure with a wrong reason, and a right reason with a wrong measure, each get their own correction.
- Parallel or Not?: two measures, one at each intersection, with the diagram drawn honestly from those measures (the drawn tilt of line b is derived from the givens). In verdict items the student rules on whether the lines must be parallel and names the deciding relationship. In claim items a written student claim is presented and the student finds its flaw: a misnamed relationship, measures that fail the relationship, or no flaw at all.

The Exploration Record at the bottom collects recorded cases, the student's generalizations and break it findings in their own words, and completed practice. The Section 1 portfolio artifact is built from it: cases measured with the lock on, generalizations as first stated, and the break it findings.

## Technical notes

Single HTML file, no dependencies, works offline. All logic is inline in index.html, generation is seeded and reproducible, and a Node harness (harness.js) verifies the geometry against independent vector mathematics: quadrant measures from dot products across a parameter sweep, pair classification re-derived from the definitions for all 256 position pairs, compute keys checked against both the relationship rule and the geometry, and verdict items checked so the drawn tilt reproduces both given measures exactly. Nothing is recorded and nothing leaves the page.

GitHub topics when published: math-2201, angles-triangles, draft (draft removed after QA).
