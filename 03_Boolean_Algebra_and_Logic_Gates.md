# 03. Boolean Algebra and Logic Gates

---

## What is Boolean Algebra?

**Boolean algebra** is a mathematical structure that deals with binary variables (0 and 1) and logical operations. It forms the theoretical basis for digital logic circuits and switching systems.

---

## Basic Boolean Operations

- **AND (·):** Output is 1 only if all inputs are 1.
- **OR (+):** Output is 1 if at least one input is 1.
- **NOT (‾):** Output is the complement (inverse) of the input.

---

## Basic Logic Gates

- **AND Gate:** Output is high only if all inputs are high.
- **OR Gate:** Output is high if any input is high.
- **NOT Gate (Inverter):** Output is complement of input.

---

## Derived Logic Gates

- **NAND:** NOT of AND; universal gate.
- **NOR:** NOT of OR; universal gate.
- **XOR (Exclusive OR):** Output is high if inputs differ.
- **XNOR (Exclusive NOR):** Output is high if inputs are the same.

---

## Truth Tables

Example for two inputs A and B:

| A | B | AND | OR | NAND | NOR | XOR | XNOR |
|---|---|-----|----|------|-----|-----|------|
| 0 | 0 |  0  | 0  |  1   |  1  |  0  |  1   |
| 0 | 1 |  0  | 1  |  1   |  0  |  1  |  0   |
| 1 | 0 |  0  | 1  |  1   |  0  |  1  |  0   |
| 1 | 1 |  1  | 1  |  0   |  0  |  0  |  1   |

---

## Boolean Laws and Theorems

1. **Commutative:** A+B = B+A ; AB = BA
2. **Associative:** (A+B)+C = A+(B+C) ; (AB)C = A(BC)
3. **Distributive:** A(B+C) = AB + AC
4. **Identity:** A+0 = A ; A·1 = A
5. **Null Law:** A+1 = 1 ; A·0 = 0
6. **Idempotent:** A+A = A ; A·A = A
7. **Inverse:** A+A' = 1 ; A·A' = 0
8. **Absorption:** A+AB = A ; A(A+B) = A
9. **DeMorgan’s Theorems:**  
   - (A·B)' = A' + B'  
   - (A+B)' = A'·B'

---

## Canonical Forms

- **Sum of Products (SOP):** OR of AND terms (e.g., AB + A'B).
- **Product of Sums (POS):** AND of OR terms (e.g., (A+B')(A'+B)).

---

## Standard Forms

- **Minterm:** AND term with all variables (either in true or complemented form).
- **Maxterm:** OR term with all variables.

---

## Logic Gate Implementation

- **Universal Gates:** NAND and NOR can implement any Boolean function.
- **Gate-level Minimization:** Reduce the number of gates/inputs for efficient implementation.

---

## Practical Considerations

- **Propagation Delay:** Time for input change to affect output.
- **Fan-in and Fan-out:** Number of inputs a gate can handle/drive.

---

## Interview Patterns

- Write truth tables for logical expressions.
- Implement Boolean functions using only NAND/NOR gates.
- Prove identities with Boolean laws.
- Minimize logic expressions with Boolean algebra.

---

## Exercises

1. Simplify: F = AB + A'B + AB'
2. Express F = (A + B)(A' + C) in SOP form.
3. Prove DeMorgan’s theorems using truth tables.
4. Implement F = (A + B)' using only NAND gates.
5. Find the dual of the expression: F = AB + C

---

## Key Interview Questions

- What are universal gates?
- State and prove DeMorgan’s theorems.
- How do you implement XOR using only NAND gates?
- Why is minimization of logic expressions important?

---

## References

- [Morris Mano, Digital Logic and Computer Design, Ch. 3](https://www.amazon.com/Digital-Logic-Computer-Design-Mano/dp/0132145103)
- [GeeksforGeeks - Boolean Algebra](https://www.geeksforgeeks.org/boolean-algebra/)
- [Brilliant - Logic Gates](https://brilliant.org/wiki/logic-gates/)
- [Wikipedia: Logic Gate](https://en.wikipedia.org/wiki/Logic_gate)

---
