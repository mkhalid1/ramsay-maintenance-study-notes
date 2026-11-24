<!-- nav:top -->[Contents](../../README.md#contents) · Previous: [Pumps, piping and combustion](pumps-piping.md) · Next: [Mechanical maintenance and shop tools](maintenance-shop-tools.md)<!-- /nav:top -->

# Print reading

**In one line:** you read mechanical drawings: line types, views, dimensions, tolerances and the common callouts on a shop print.

Print Reading is a category on MecTest and Mechanical Maintenance Trainee. On the MultiCraft forms it sits inside "Motors, Control Circuits, and Schematics & Print Reading", so MultiCraft candidates also need electrical schematics, covered on the [motors and controls](motors-controls.md) page. This page covers the mechanical side.

## What it measures

Whether you can make or fit a part from a drawing without asking someone to explain it. That means:

- **Line types.** Visible, hidden, centre and dimension lines each mean something different.
- **Views.** Front, top and side views, and how they line up in a multiview drawing.
- **Dimensions.** Adding and subtracting chained dimensions to find one that is not shown.
- **Tolerances and callouts.** Limits, diameters, thread callouts and section views.

## How the questions look

Four-option multiple choice, often with a small drawing. Common tasks: name a line type, pick the missing view, find a missing dimension, or decide whether a measured part is within tolerance.

## A method that works

1. **Read the notes and title block first.** Units, scale and projection method change the answer.
2. **For a missing dimension, write the chain.** Overall length minus the known pieces gives the missing one.
3. **For tolerances, work out both limits** before you look at the options. Treat the limits as inside the tolerance.
4. **For views, picture yourself standing where the view is taken from.** Edges you can see are solid. Edges behind material are dashed.
5. **Check the projection.** In third-angle projection (US practice) the top view is above the front view and the right side view is to the right.

## Traps that cost points

- **Measuring the drawing with a rule.** Prints are often not to scale. Use the dimensions given.
- **Reading a hidden line as a visible edge.** Short dashes mean the edge is there but behind material.
- **Dropping a decimal place in tolerances.** 2.500 ±0.005 runs from 2.495 to 2.505, not 2.45 to 2.55.
- **Mixing up radius and diameter.** R is radius. Ø is diameter, twice the radius.
- **Misreading thread callouts.** In 1/2-13 UNC, the 13 is threads per inch, not a length.

## Timing

Line-type and callout items: 20 to 30 seconds. Dimension chains: 30 to 45 seconds. View items: up to a minute, so do them last if you are short of time.

## Practice items

These items are original, written for these notes. They are not taken from any Ramsay test.

![Four drawing line types labelled A to D](../../assets/pr-lines.svg)

**Item 1.** Which line above is a hidden line?

- A. A
- B. B
- C. C
- D. D

**Item 2.** Which line above is a centre line?

- A. A
- B. B
- C. C
- D. D

![Plate 8.00 inches long with two holes dimensioned 1.50 and 2.25 from the left](../../assets/pr-plate.svg)

**Item 3.** What is dimension X?

- A. 3.75
- B. 4.25
- C. 5.75
- D. 6.50

**Item 4.** How far is the centre of the right-hand hole from the left edge of the plate?

- A. 2.25
- B. 3.75
- C. 4.25
- D. 5.75

**Item 5.** A print gives a shaft diameter as 2.500 ±0.005. Which measured shaft is out of tolerance?

- A. 2.496
- B. 2.500
- C. 2.505
- D. 2.494

<details>
<summary>Answers and explanations, items 1 to 5</summary>

**Item 1: B.** Evenly spaced short dashes mark a hidden line: an edge that exists but is behind material in this view. *Why not C:* C alternates long and short dashes, which marks a centre line.

**Item 2: C.** Long dash, short dash, repeating, is a centre line. It marks the centre of holes, shafts and symmetric features. *Why not D:* D has arrowheads and a number, which makes it a dimension line.

**Item 3: B, 4.25.** The right-hand hole is 1.50 + 2.25 = 3.75 from the left edge. 8.00 - 3.75 = 4.25. *Why not A:* 3.75 is the distance from the left edge, not to the right edge.

**Item 4: B, 3.75.** Add the chained dimensions: 1.50 + 2.25 = 3.75. *Why not A:* 2.25 is the spacing between the holes.

**Item 5: D, 2.494.** The limits are 2.495 and 2.505. Only 2.494 falls outside. *Why not C:* 2.505 is exactly on the upper limit, which is allowed.

</details>

![Front and top views of a stepped block in third-angle projection](../../assets/pr-views.svg)

![Four candidate right side views labelled A to D](../../assets/pr-side-options.svg)

**Item 6.** The first drawing shows the front and top views of a stepped block. Which option is the correct right side view?

- A. A
- B. B
- C. C
- D. D

**Item 7.** A drawing is marked "SCALE 1:2" (half size) and has no "do not scale" note. A feature with no dimension measures 3 inches on the paper. What is its actual size?

- A. 1.5 in
- B. 3 in
- C. 6 in
- D. 9 in

**Item 8.** A hole is called out as "1/2-13 UNC". What does the 13 mean?

- A. The hole is 13 mm deep
- B. 13 threads per inch
- C. Thread class 13
- D. A thread pitch of 13 mm

**Item 9.** What does the symbol Ø before a dimension mean?

- A. Radius
- B. Diameter
- C. Depth
- D. Countersink

**Item 10.** In a section view, how are the cut surfaces of solid material shown?

- A. With hidden lines
- B. With evenly spaced diagonal hatching
- C. With centre lines
- D. They are left blank

**Item 11.** In third-angle projection, where is the top view placed?

- A. Directly above the front view
- B. Directly below the front view
- C. To the left of the front view
- D. Anywhere on the sheet, with a label

<details>
<summary>Answers and explanations, items 6 to 11</summary>

**Item 6: A.** From the right you see the 3-deep by 2-high outline. The low step sits in front, so the edge where the step's top surface meets the tall part shows as a solid (visible) line at height 1. *Why not B:* that edge is not behind any material from this direction, so it is not hidden. *Why not D:* the step edge must appear somewhere; a plain rectangle leaves it out.

**Item 7: C, 6 in.** At half scale the drawing is half the real size, so the real feature is 3 x 2 = 6 inches. *Why not A:* 1.5 in halves the drawing again. In practice, check whether the print says "do not scale" before measuring at all.

**Item 8: B.** In Unified thread callouts, the first number is the nominal diameter (1/2 inch) and the second is threads per inch. *Why not D:* inch threads are given in threads per inch, not a pitch in millimetres.

**Item 9: B.** Ø is the diameter symbol. *Why not A:* radius uses the letter R.

**Item 10: B.** Section lining, a set of evenly spaced thin diagonal lines, shows where the cutting plane passes through solid material. *Why not A:* hidden lines are usually left out of section views because the cut already shows the inside.

**Item 11: A.** Third-angle projection, the US standard, places the top view above the front view and the right side view to the right. *Why not B:* the top view goes below the front view in first-angle projection, used widely in Europe.

</details>

## Score yourself

| Item | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 |
|---|---|---|---|---|---|---|---|---|---|---|---|
| Answer | B | C | B | B | D | A | C | B | B | B | A |

- **10 to 11:** strong. Keep views fresh by sketching a side view of anything on your desk.
- **7 to 9:** relearn the line types and redo the tolerance and dimension chain items.
- **6 or fewer:** work through a basic blueprint reading book chapter on views and lines, then redo all 11 items.

## Next step

Practise print items under time pressure in the [free Ramsay Maintenance practice test on PrepClubs](https://prepclubs.com/free-practice-tests/ramsay-maintenance?utm_source=github&utm_medium=referral&utm_campaign=study-notes&utm_content=ramsay-maintenance).

---

<!-- nav:bottom -->← Previous: [Pumps, piping and combustion](pumps-piping.md) | Next: [Mechanical maintenance and shop tools](maintenance-shop-tools.md) → | [Back to contents](../../README.md#contents)<!-- /nav:bottom -->
