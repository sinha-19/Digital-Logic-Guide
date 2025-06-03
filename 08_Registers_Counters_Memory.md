# 08. Registers, Counters, and Memory

---

## Registers

Registers are groups of flip-flops used to store multiple bits of data.  
- **n-bit register:** Stores n bits.
- Used for temporary storage, data transfer, instruction holding.

### Types of Registers

- **Shift Register:** Moves bits left/right (serial-in, serial-out, parallel-in, parallel-out).
- **Universal Shift Register:** Supports all shift/load operations.
- **Buffer Register:** Temporarily holds data for I/O.

---

## Register Transfer

- **Register Transfer Language (RTL):** Describes data flow between registers.
- Example: `R1 ← R2 + R3`

---

## Counters

Counters are sequential circuits that count clock pulses.

### Types of Counters

- **Asynchronous (Ripple) Counter:** Each flip-flop triggered by previous; simple but slow.
- **Synchronous Counter:** All flip-flops share the same clock; fast and widely used.
- **Up Counter / Down Counter / Up-Down Counter**
- **Ring Counter:** Shift register with feedback.
- **Johnson Counter:** Shift register with inverted feedback.

### Modulo-n Counters

- Counts from 0 to n-1, then resets.

---

## Counter Design

- Use flip-flop excitation tables to derive logic equations.
- For n-bit counter, need n flip-flops.

---

## Memory Elements

### RAM (Random Access Memory)

- **Static RAM (SRAM):** Fast, uses flip-flops, expensive, used for cache.
- **Dynamic RAM (DRAM):** Dense, needs refresh, used for main memory.

### ROM (Read Only Memory)

- Non-volatile, used for firmware.

### Memory Organization

- **Word:** Basic unit of storage (e.g., 8, 16, 32 bits).
- **Address lines:** Number of unique addresses = 2^(number of lines).

---

## Memory Decoding

- **Decoder circuits** used to select memory locations.
- **Chip Select:** Enables specific memory chips in large systems.

---

## Applications

- CPU registers (accumulator, program counter)
- Digital clocks (counters)
- Serial-to-parallel/parallel-to-serial data conversion

---

## Interview Patterns

- Design a 4-bit synchronous counter.
- Draw a right-shift register circuit.
- Calculate the number of address lines for a given memory size.
- Explain difference between SRAM and DRAM.

---

## Exercises

1. Design a 3-bit ring counter.
2. Implement a 4-bit parallel-in, serial-out shift register.
3. How many address lines are required for 2 KB of RAM?
4. Draw block diagram of memory organization for a microprocessor.
5. Compare ripple and synchronous counters.

---

## Key Interview Questions

- What is the advantage of synchronous counters over asynchronous?
- How does a shift register work?
- Explain the structure and operation of SRAM and DRAM.

---

## References

- [Morris Mano, Digital Logic and Computer Design, Ch. 8](https://www.amazon.com/Digital-Logic-Computer-Design-Mano/dp/0132145103)
- [GeeksforGeeks - Registers and Counters](https://www.geeksforgeeks.org/registers-and-counters-in-digital-electronics/)
- [Brilliant - Counters](https://brilliant.org/wiki/counters/)
- [Wikipedia: Counter (Digital)](https://en.wikipedia.org/wiki/Counter_(digital))

---
