# 05. Combinational Circuits

---

## What are Combinational Circuits?

Combinational circuits are digital circuits whose outputs depend only on the current combination of inputs, not on any previous history (no memory).

---

## Design Steps

1. **Specification:** State the function.
2. **Truth Table:** List all input/output possibilities.
3. **Minimization:** Use K-maps or Boolean algebra.
4. **Implementation:** Draw using logic gates.

---

## Common Combinational Circuits

### 1. Adders

- **Half Adder:** Adds two bits; outputs sum and carry.
- **Full Adder:** Adds three bits (including previous carry).

### 2. Subtractors

- **Half Subtractor:** Subtracts two bits; outputs difference and borrow.
- **Full Subtractor:** Subtracts three bits (including borrow-in).

### 3. Multiplexers (MUX)

- Selects one of many inputs to pass to output, based on select lines.
- **2:1 MUX:** 2 inputs, 1 select, 1 output.
- **4:1, 8:1, 16:1 MUX**.

### 4. Demultiplexers (DEMUX)

- Routes one input to one of many outputs.

### 5. Encoders

- Converts multiple inputs to a binary output code.

### 6. Decoders

- Converts binary input code to one of many outputs.

### 7. Comparators

- Compares binary numbers, outputs equality/greater/less signals.

### 8. Parity Generators/Checkers

- Generates or verifies parity bits for error detection.

---

## Combinational Circuit Implementation

- **Cascade:** Combine smaller circuits for larger functions (e.g., ripple-carry adder).
- **Hierarchical Design:** Build large systems from smaller modules.

---

## Realization Using Multiplexers

- Any Boolean function can be implemented using MUXes.

---

## Interview Patterns

- Design a 4:1 multiplexer with logic gates.
- Implement a 2-bit binary adder.
- Draw truth tables for encoders/decoders.
- Realize functions using only multiplexers or decoders.

---

## Exercises

1. Design a full adder using two half adders and an OR gate.
2. Implement a 3-to-8 decoder.
3. Design a 4-bit comparator.
4. Realize F(A,B,C) = Σm(1,3,5,7) using a MUX.
5. Draw the logic diagram for a 2-to-4 line decoder.

---

## Key Interview Questions

- What is the difference between a multiplexer and a decoder?
- How do you build a full adder from half adders?
- Explain the principle of hierarchical design in combinational circuits.

---

## References

- [Morris Mano, Digital Logic and Computer Design, Ch. 5](https://www.amazon.com/Digital-Logic-Computer-Design-Mano/dp/0132145103)
- [GeeksforGeeks - Combinational Circuits](https://www.geeksforgeeks.org/combinational-circuits/)
- [Brilliant - Combinational Logic](https://brilliant.org/wiki/combinational-logic/)
- [Wikipedia: Combinational Logic](https://en.wikipedia.org/wiki/Combinational_logic)

---
