# 06. Arithmetic Circuits

---

## Importance in Digital Systems

Arithmetic circuits perform basic mathematical operations—addition, subtraction, multiplication, and division—essential for processors, ALUs, calculators, and digital signal processing.

---

## Adders

### 1. Half Adder

- Adds two single bits.
- Outputs: **Sum** (A XOR B), **Carry** (A AND B).

### 2. Full Adder

- Adds three bits (A, B, Carry-in).
- Outputs: **Sum** (A XOR B XOR Cin), **Carry-out** (AB + BCin + ACin).
- Used for multi-bit addition by cascading (ripple-carry adder).

### 3. Parallel Adder

- Multiple full adders connected in series to add multi-bit numbers.

### 4. Carry Look-Ahead Adder

- Reduces propagation delay by calculating carries in advance.

---

## Subtractors

### 1. Half Subtractor

- Subtracts two bits.
- Outputs: **Difference** (A XOR B), **Borrow** (A'B).

### 2. Full Subtractor

- Subtracts three bits (A, B, Borrow-in).
- Outputs: **Difference** (A XOR B XOR Bin), **Borrow-out** (A'B + B'Bin + A'Bin).

---

## Binary Multipliers

- **Array Multiplier:** Uses adders and AND gates in matrix form.
- **Booth’s Algorithm:** Efficient for signed multiplication.

---

## Binary Dividers

- **Restoring Division:** Classic division approach.
- **Non-Restoring Division:** Faster, fewer steps.

---

## BCD (Decimal) Arithmetic Circuits

- **BCD Adder:** Adds decimal digits using binary adders plus correction logic.

---

## Overflow Detection

- Occurs when result exceeds the representable range.
- For addition: If carry into MSB ≠ carry out of MSB.

---

## Applications

- ALUs in CPUs and microcontrollers
- Digital calculators
- DSPs and FPGAs

---

## Interview Patterns

- Design a 4-bit adder using full adders.
- Draw circuit for a half subtractor.
- Implement a 2-bit multiplier.
- Explain overflow detection in binary addition.

---

## Exercises

1. Design a 2-bit binary multiplier.
2. Implement a 4-bit ripple-carry adder.
3. Show how to detect overflow in signed addition.
4. Design a BCD adder circuit.
5. Write truth tables for half adder and full subtractor.

---

## Key Interview Questions

- How does a carry look-ahead adder improve speed?
- What is the difference between half adder and full adder?
- How do you detect overflow in binary arithmetic?

---

## References

- [Morris Mano, Digital Logic and Computer Design, Ch. 6](https://www.amazon.com/Digital-Logic-Computer-Design-Mano/dp/0132145103)
- [GeeksforGeeks - Arithmetic Circuits](https://www.geeksforgeeks.org/arithmetic-circuits-in-digital-electronics/)
- [Brilliant - Adders and Subtractors](https://brilliant.org/wiki/adders-and-subtractors/)
- [Wikipedia: Arithmetic Logic Unit](https://en.wikipedia.org/wiki/Arithmetic_logic_unit)

---
