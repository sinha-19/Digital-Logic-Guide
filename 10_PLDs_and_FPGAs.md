# 10. Programmable Logic Devices (PLDs) and FPGAs

---

## What are PLDs?

**Programmable Logic Devices (PLDs)** are digital devices whose logic function can be programmed after manufacturing, allowing custom digital designs.

---

## Types of PLDs

### 1. PROM (Programmable Read-Only Memory)

- Used for fixed logic functions.
- Programmed once.

### 2. PAL (Programmable Array Logic)

- Programmable AND array, fixed OR array.
- Simple, used for small logic circuits.

### 3. PLA (Programmable Logic Array)

- Both AND and OR arrays programmable.
- Flexible, can implement any SOP/POS function.

### 4. CPLD (Complex PLD)

- Multiple PLD blocks in a single chip.
- Moderate complexity designs.

---

## FPGAs (Field Programmable Gate Arrays)

- Large, highly flexible PLDs.
- Consist of thousands of configurable logic blocks (CLBs), programmable interconnects, and I/O blocks.
- Re-programmable many times.

---

## FPGA Architecture

- **Configurable Logic Blocks (CLBs):** Implement logic functions.
- **Interconnects:** Programmable routing between CLBs.
- **I/O Blocks:** Interface with external pins.
- **Embedded RAM/ROM, DSP blocks, PLLs** in advanced FPGAs.

---

## FPGA Programming

- Hardware description languages (HDLs): **VHDL, Verilog.**
- Synthesis tools generate configuration bitstream.
- Configuration loaded into SRAM cells (volatile) or flash (non-volatile).

---

## Applications

- Rapid prototyping of digital circuits.
- Custom hardware accelerators.
- Signal processing, image processing.
- Embedded systems, robotics.

---

## Advantages

- Reconfigurability.
- Fast time-to-market.
- Integration of large/complex systems.

---

## Disadvantages

- Higher power than custom ASICs.
- Slower than ASICs for some applications.
- More expensive per unit (for large volume).

---

## Interview Patterns

- Compare PAL, PLA, CPLD, and FPGA.
- Draw block diagram of a FPGA.
- Discuss advantages and applications of FPGAs.
- Explain how a Boolean function is implemented in a PLA.

---

## Exercises

1. Implement F(A,B,C) = Σm(1,3,5,7) using a PLA.
2. Draw the architecture of a simple FPGA.
3. Compare PROM, PAL, PLA, and FPGA in a table.
4. Write a simple Verilog code for a 4:1 multiplexer.
5. Discuss steps for programming a FPGA.

---

## Key Interview Questions

- What are the differences between PAL and PLA?
- What are the main components of a FPGA?
- Why are FPGAs used for prototyping and embedded systems?

---

## References

- [Morris Mano, Digital Logic and Computer Design, Ch. 10](https://www.amazon.com/Digital-Logic-Computer-Design-Mano/dp/0132145103)
- [GeeksforGeeks - Programmable Logic Devices](https://www.geeksforgeeks.org/programmable-logic-devices-plds/)
- [Brilliant - Programmable Logic Devices](https://brilliant.org/wiki/programmable-logic-devices/)
- [Wikipedia: FPGA](https://en.wikipedia.org/wiki/Field-programmable_gate_array)

---
