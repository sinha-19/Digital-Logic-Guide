# 11. Hazards, Timing, and Digital Design Issues

---

## Hazards in Digital Circuits

Hazards are unwanted switching transients (glitches) that can cause incorrect output in combinational or sequential circuits.

### Types of Hazards

- **Static Hazard:** Output is supposed to remain constant but momentarily changes.
    - **Static-1 Hazard:** Output should stay at 1 but dips to 0.
    - **Static-0 Hazard:** Output should stay at 0 but rises to 1.
- **Dynamic Hazard:** Output is supposed to change once, but changes multiple times.

---

## Causes of Hazards

- Different propagation delays in circuit paths.
- Incomplete logic minimization.
- Race conditions in sequential circuits.

---

## Eliminating Hazards

- Proper logic minimization (include all prime implicants).
- Add redundant logic to cover hazards.
- Use synchronous design—avoid glitches by latching outputs on clock edges.

---

## Timing Issues

### 1. Propagation Delay

- Time for a signal to travel from input to output.
- **Critical path:** Longest delay path; determines circuit speed.

### 2. Setup and Hold Times

- Setup: Input must be stable before clock.
- Hold: Input must remain stable after clock.
- Violations cause metastability.

### 3. Clock Skew

- Difference in arrival time of clock signal at different parts of the circuit.
- May cause race conditions or setup/hold violations.

---

## Races and Metastability

- **Race Condition:** Two or more signals change simultaneously, causing unpredictable results.
- **Metastability:** Flip-flop output oscillates or settles unpredictably due to timing violations.

---

## Glitches

- Momentary output spikes caused by hazards.

---

## Synchronous vs. Asynchronous Design

- **Synchronous:** All state changes on clock edges; easier to design/test.
- **Asynchronous:** Changes occur anytime; faster but harder to control.

---

## Design for Testability

- **Scan chains:** Shift register paths for testing flip-flops.
- **Built-In Self-Test (BIST):** Circuits can test themselves.
- **Boundary Scan (JTAG):** Standard for testing PCB connections.

---

## Power and Noise Issues

- **Dynamic Power Consumption:** Switching activity.
- **Static Power Consumption:** Leakage currents.
- **Crosstalk:** Signal interference between adjacent wires.

---

## Interview Patterns

- Identify and eliminate hazards in a circuit.
- Explain setup/hold time violations.
- Discuss clock skew and its effects.
- Suggest testability features for digital systems.

---

## Exercises

1. Analyze a circuit for static hazards.
2. Propose modifications to remove hazards.
3. Calculate the maximum clock frequency for a given propagation delay.
4. Explain metastability and its prevention.
5. Design a scan chain for a 4-bit register.

---

## Key Interview Questions

- What are static and dynamic hazards?
- How do setup and hold times affect flip-flop operation?
- Why is synchronous design preferred in industry?

---

## References

- [Morris Mano, Digital Logic and Computer Design, Ch. 11](https://www.amazon.com/Digital-Logic-Computer-Design-Mano/dp/0132145103)
- [GeeksforGeeks - Hazards in Digital Circuits](https://www.geeksforgeeks.org/hazards-in-digital-circuits/)
- [Brilliant - Timing Hazards](https://brilliant.org/wiki/timing-hazards/)
- [Wikipedia: Hazard (Logic)](https://en.wikipedia.org/wiki/Hazard_(logic))

---
