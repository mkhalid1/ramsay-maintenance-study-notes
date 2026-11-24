<!-- nav:top -->[Contents](../../README.md#contents) · Previous: [Electronics, PLCs and test instruments](electronics-plc-instruments.md) · Next: [How scoring works](../scoring.md)<!-- /nav:top -->

# AC/DC theory, power distribution and electrical maintenance

**In one line:** you apply Ohm's law and the power formula to series and parallel circuits, read voltages around a simple circuit to find a fault, and know the basics of transformers, breakers and grounding.

This is a MultiCraft category. Both MultiCrafTest and MultiCraft Trainee list "Basic AC/DC Theory, Power Distribution, and Electrical Maintenance". Ramsay's MultiCraft Trainee sample question asks what electrical resistance is measured in, which shows the level: core theory, applied to plant equipment.

## What it measures

- **Circuit theory.** Ohm's law, series and parallel resistance, power.
- **Fault finding with a meter.** Where you should and should not read voltage in a working or faulty circuit.
- **Distribution.** Transformers, three-phase voltages, breakers and fuses.
- **Electrical maintenance and safety.** Grounding, overcurrent, and what a trip tells you.

## How the questions look

Four-option multiple choice. Many items give a small circuit with round numbers and ask for a current, voltage, resistance or power. Others describe a fault and ask for the cause.

## A method that works

1. **Write the three formulas before you start:** V = I x R, P = V x I, and for parallel resistors 1 / Rt = 1 / R1 + 1 / R2 + ...
2. **For series circuits, add the resistances,** find the one current, then find each voltage drop.
3. **For parallel circuits, every branch has the full supply voltage.** Find each branch current, then add them.
4. **For voltage fault finding, remember:** an open switch or open fuse has the full supply voltage across it, and a closed switch or good wire has about zero.
5. **For transformers, voltage follows the turns ratio.** A 4:1 step-down transformer divides the voltage by 4.

## Traps that cost points

- **Adding parallel resistors like series ones.** Parallel resistance is always lower than the smallest branch.
- **Expecting zero volts across an open switch.** With a good load beyond it, the full supply appears across the open contacts.
- **Confusing an overload with a short circuit.** A breaker that trips the instant you reset it points to a short or ground fault, not a heavy load.
- **Mixing up the grounding conductor and the neutral.** The neutral carries normal current. The equipment ground carries fault current only, so the breaker trips.
- **Forgetting the square root of 3** between line and phase voltages in a wye system: 208 / 1.732 is about 120.

## Timing

Calculation items: 45 seconds to a minute. Knowledge items: 20 to 30 seconds.

## Practice items

These items are original, written for these notes. They are not taken from any Ramsay test.

![Series circuit with a 24 volt source and resistors of 2 and 6 ohms](../../assets/ac-series.svg)

**Item 1.** In the series circuit above, what current flows?

- A. 2 A
- B. 3 A
- C. 4 A
- D. 12 A

**Item 2.** What is the voltage across R2?

- A. 6 V
- B. 12 V
- C. 18 V
- D. 24 V

![Parallel circuit with 40, 40 and 20 ohm resistors across 120 volts](../../assets/ac-parallel.svg)

**Item 3.** What is the total resistance of the three resistors in parallel?

- A. 10 Ω
- B. 20 Ω
- C. 33 Ω
- D. 100 Ω

**Item 4.** What total current does the supply deliver?

- A. 1.2 A
- B. 6 A
- C. 12 A
- D. 24 A

**Item 5.** How much current flows through R3?

- A. 3 A
- B. 6 A
- C. 12 A
- D. 20 A

<details>
<summary>Answers and explanations, items 1 to 5</summary>

**Item 1: B, 3 A.** Series resistance adds: 2 + 6 = 8 Ω. I = V / R = 24 / 8 = 3 A. *Why not D:* 12 A uses only the 2 Ω resistor.

**Item 2: C, 18 V.** V = I x R = 3 x 6 = 18 V. The other 6 V drops across R1, and the two add up to the 24 V supply. *Why not A:* 6 V is the drop across R1.

**Item 3: A, 10 Ω.** 1 / Rt = 1/40 + 1/40 + 1/20 = 0.025 + 0.025 + 0.05 = 0.1, so Rt = 10 Ω. *Why not D:* 100 Ω adds the resistors as if they were in series.

**Item 4: C, 12 A.** I = V / R = 120 / 10 = 12 A. You can check by adding branch currents: 3 + 3 + 6 = 12 A. *Why not B:* 6 A is the current in R3 alone.

**Item 5: B, 6 A.** Each branch has the full 120 V across it: 120 / 20 = 6 A. *Why not A:* 3 A is the current in each 40 Ω branch.

</details>

![Lamp circuit with fuse and open switch and test points 1 to 4](../../assets/ac-meter.svg)

**Item 6.** In the circuit above the switch is open. What does a voltmeter read between points 2 and 3, across the open switch?

- A. 0 V
- B. 60 V
- C. 120 V
- D. 240 V

**Item 7.** With the switch still open, what does a voltmeter read between points 3 and 4, across the lamp?

- A. 0 V
- B. 60 V
- C. 120 V
- D. 240 V

**Item 8.** A space heater draws 10 A from a 120 V supply. How much power does it use?

- A. 12 W
- B. 130 W
- C. 1,200 W
- D. 12,000 W

**Item 9.** A transformer with a 4:1 step-down ratio has 480 V on its primary. What is the secondary voltage?

- A. 120 V
- B. 240 V
- C. 1,920 V
- D. 480 V

**Item 10.** A breaker trips the instant it is reset, with the load switched on. What is the most likely cause?

- A. A short circuit or ground fault downstream
- B. The circuit is lightly loaded
- C. The room is cold
- D. The wire run is long

**Item 11.** What is the main purpose of the equipment grounding conductor?

- A. To carry the normal return current
- B. To give fault current a low-resistance path so the breaker or fuse opens
- C. To raise the supply voltage
- D. To reduce the power bill

<details>
<summary>Answers and explanations, items 6 to 11</summary>

**Item 6: C, 120 V.** Point 2 connects to L1 through the good fuse. Point 3 connects to N through the good lamp, because no current flows so the lamp drops no voltage. The open switch has the full 120 V across it. *Why not A:* zero would be the reading across a closed switch.

**Item 7: A, 0 V.** With the switch open, no current flows, so there is no voltage drop across the lamp. Both points 3 and 4 sit at neutral potential. *Why not C:* the lamp gets 120 V only when the switch is closed.

**Item 8: C, 1,200 W.** P = V x I = 120 x 10 = 1,200 W. *Why not A:* 12 W divides instead of multiplying.

**Item 9: A, 120 V.** A 4:1 step-down divides the voltage by 4: 480 / 4 = 120 V. *Why not C:* 1,920 V would be a 1:4 step-up.

**Item 10: A.** An instant trip on reset means a very high current, which is what a short circuit or ground fault produces. *Why not B:* a light load draws less current, not more.

**Item 11: B.** If a live wire touches a metal enclosure, the equipment ground carries the fault current back so the overcurrent device opens quickly, and the enclosure does not stay live. *Why not A:* normal return current is the neutral's job.

</details>

## Score yourself

| Item | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 |
|---|---|---|---|---|---|---|---|---|---|---|---|
| Answer | B | C | A | C | B | C | A | C | A | A | B |

- **10 to 11:** strong. Move on.
- **7 to 9:** redo the parallel circuit and the voltage fault-finding items, which is where most marks go.
- **6 or fewer:** drill V = I x R and P = V x I on simple numbers until you can do them without writing.

## Next step

Practise circuit sums against the clock in the [free Ramsay Maintenance practice test on PrepClubs](https://prepclubs.com/free-practice-tests/ramsay-maintenance?utm_source=github&utm_medium=referral&utm_campaign=study-notes&utm_content=ramsay-maintenance).

---

<!-- nav:bottom -->← Previous: [Electronics, PLCs and test instruments](electronics-plc-instruments.md) | Next: [How scoring works](../scoring.md) → | [Back to contents](../../README.md#contents)<!-- /nav:bottom -->
