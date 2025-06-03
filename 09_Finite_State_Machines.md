# 09. Finite State Machines: Mealy and Moore Models

---

## What is a Finite State Machine (FSM)?

An FSM is a sequential circuit model with a finite number of states, transitions between states, and outputs that depend on inputs and/or states.

---

## Elements of FSM

- **States:** Memory of the system.
- **Inputs:** External signals that affect transitions.
- **Outputs:** Resulting signals, may depend on state and/or input.
- **Transitions:** Define movement from one state to another.

---

## Moore vs. Mealy Machines

| Feature      | Moore Machine           | Mealy Machine            |
|--------------|------------------------|-------------------------|
| Output       | Depends on state only  | Depends on state + input|
| Output Change| On state change        | On input change         |
| Simplicity   | Easier to design       | May use fewer states    |

---

## State Diagram

- Circles: States
- Arrows: Transitions w/ input (and output for Mealy)
- Example: Sequence detector, traffic light controller

---

## State Table

- Tabular representation: Current State, Input, Next State, Output

---

## State Assignment

- Assign binary codes to states for implementation.
- Minimize number of state bits.

---

## State Reduction

- Combine equivalent states to minimize hardware.

---

## Implementation Steps

1. **Specification:** Define behavior.
2. **State Diagram/Table:** Represent states and transitions.
3. **State Assignment:** Assign binary codes.
4. **Flip-Flop Equations:** Use excitation tables.
5. **Output Logic:** Define output functions.
6. **Draw circuit:** Connect flip-flops and combinational logic.

---

## Example Applications

- Sequence detector (detects bit patterns)
- Traffic light controller
- Vending machine controller
- Elevator logic

---

## Interview Patterns

- Draw state diagrams for a given sequence detector.
- Convert a Moore machine to a Mealy machine and vice versa.
- Reduce number of states in a FSM.
- Implement FSM using flip-flops and gates.

---

## Exercises

1. Design a sequence detector for "1011" using a Mealy machine.
2. Draw state table for a 2-bit Gray code generator.
3. Reduce states in a given FSM.
4. Implement a traffic light controller FSM.
5. Explain differences in output timing between Moore and Mealy.

---

## Key Interview Questions

- What are the advantages and disadvantages of Moore vs Mealy machines?
- How do you minimize the number of states in a FSM?
- How is a FSM implemented in hardware?

---

## References

- [Morris Mano, Digital Logic and Computer Design, Ch. 9](https://www.amazon.com/Digital-Logic-Computer-Design-Mano/dp/0132145103)
- [GeeksforGeeks - Finite State Machines](https://www.geeksforgeeks.org/finite-state-machine/)
- [Brilliant - State Machines](https://brilliant.org/wiki/state-machines/)
- [Wikipedia: Finite-state machine](https://en.wikipedia.org/wiki/Finite-state_machine)

---
