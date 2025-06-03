# 02. Number Systems and Codes

---

## Importance in Digital Logic

Understanding number systems and codes is fundamental for analyzing, designing, and troubleshooting digital circuits and data transmission.

---

## Number Systems in Digital Logic

- **Binary (Base 2):** Digits 0, 1
- **Octal (Base 8):** Digits 0–7
- **Decimal (Base 10):** Digits 0–9
- **Hexadecimal (Base 16):** Digits 0–9, A–F

---

## Conversion Techniques

- **Decimal ↔ Binary:** Repeated division/remainder and place value.
- **Binary ↔ Octal/Hex:** Group bits (3 for octal, 4 for hex).
- **Binary Arithmetic:** Addition, subtraction, multiplication, division.

---

## Signed Number Representation

- **Sign-Magnitude:** MSB is sign (0=+, 1=−).
- **1's Complement:** Invert all bits for negative.
- **2's Complement:** Invert all bits, add 1 for negative. Most widely used.

---

## Binary Codes

### 1. BCD (Binary Coded Decimal)

- Each decimal digit is represented by a 4-bit binary value.

### 2. Excess-3 Code

- BCD + 3 (useful for error detection).

### 3. Gray Code

- Only one bit changes between adjacent values (minimizes errors in mechanical/electrical transitions).

### 4. ASCII

- 7/8-bit code for representing characters.

---

## Error Detection Codes

- **Parity Bit:** Simple error detection (even/odd).
- **Hamming Code:** Detects and corrects single-bit errors.
- **Checksums:** Used in data communications.

---

## Applications

- Memory addressing
- Digital displays (7-segment)
- Data transmission and storage integrity

---

## Interview Patterns

- Convert numbers between binary, octal, decimal, and hex.
- Represent negative numbers in 2's complement.
- Explain why Gray code is used in shaft encoders.

---

## Exercises

1. Convert 45 (decimal) to binary, octal, and hexadecimal.
2. Represent −34 in 8-bit 2’s complement and 1’s complement.
3. Write the Gray code for decimal 0–15.
4. Encode "LOGIC" in ASCII and binary.
5. Add two BCD numbers: 38 + 25.

---

## Key Interview Questions

- Why is 2’s complement preferred over 1’s complement?
- How does parity detect errors in data transmission?
- What is the advantage of Gray code?

---

## References

- [Morris Mano, Digital Logic and Computer Design, Ch. 2](https://www.amazon.com/Digital-Logic-Computer-Design-Mano/dp/0132145103)
- [GeeksforGeeks - Number Systems](https://www.geeksforgeeks.org/number-system-in-digital-electronics/)
- [Wikipedia: Binary Number](https://en.wikipedia.org/wiki/Binary_number)
- [Brilliant - Binary and Hexadecimal](https://brilliant.org/wiki/binary-and-hexadecimal-numbers/)

---
