# 07. Sequential Circuits: Flip-Flops and Latches

---

## What Are Sequential Circuits?

Sequential circuits are digital circuits whose outputs depend on both current inputs and previous states (history). They use memory elements to store state information.

---

## Types of Sequential Circuits

- **Synchronous:** State changes at clock edges (preferred in most designs).
- **Asynchronous:** State changes at any time inputs change (prone to glitches).

---

## Latches

### 1. SR (Set-Reset) Latch

- **Inputs:** S (Set), R (Reset)
- **Outputs:** Q, Q'
- **Operation:** Q = 1 (set), Q = 0 (reset), Q holds (no change), Indeterminate if S=R=1 (in NOR latch).

### 2. D (Data) Latch

- **Input:** D (Data), Enable
- **Stores** value of D when Enable is active.

---

## Flip-Flops

Flip-flops are clocked memory elements, edge-triggered.

### 1. SR Flip-Flop

- Clocked version of SR latch.
- **Avoid S=R=1** (undefined).

### 2. D Flip-Flop

- Data or Delay flip-flop.
- **Q(next) = D** at clock edge.

### 3. JK Flip-Flop

- Like SR but no invalid state.
- J=K=1 toggles output.

### 4. T (Toggle) Flip-Flop

- Toggles output on each clock edge if T=1.

---

## Characteristic Tables

| FF Type | Inputs      | Q(next)          |
|---------|-------------|------------------|
| SR      | S R         | S+R'Q            |
| D       | D           | D                |
| JK      | J K         | JQ'+K'Q          |
| T       | T           | T'Q + TQ'        |

---

## Excitation Tables

Used for designing sequential circuits; shows required input for state transitions.

---

## Flip-Flop Conversion

- D to JK, JK to T, etc., using logic equations.

---

## Timing Parameters

- **Setup Time:** Minimum time input must be stable before clock.
- **Hold Time:** Minimum time input must remain stable after clock.
- **Propagation Delay:** Time from clock to output change.

---

## Master-Slave Flip-Flops

- Use two flip-flops in series to prevent race conditions.
- Master active on clock high, slave on clock low.

---

## Applications

- Registers, counters, memory, state machines.

---

## Interview Patterns

- Draw truth tables and state diagrams for flip-flops.
- Convert between flip-flop types.
- Design a synchronous circuit using flip-flops.
- Explain setup and hold times and their importance.

---

## Exercises

1. Draw excitation and characteristic tables for JK flip-flop.
2. Convert a D flip-flop to a T flip-flop.
3. Design a 1-bit memory cell using latches.
4. Analyze a circuit to find its type (SR, D, JK, T).
5. Explain what happens if setup/hold times are violated.

---

## Key Interview Questions

- What is the difference between a latch and a flip-flop?
- How does a JK flip-flop avoid the invalid state of SR?
- What are setup and hold times?

---

## References

- [Morris Mano, Digital Logic and Computer Design, Ch. 7](https://www.amazon.com/Digital-Logic-Computer-Design-Mano/dp/0132145103)
- [GeeksforGeeks - Flip-Flops](https://www.geeksforgeeks.org/flip-flops-in-digital-electronics/)
- [Brilliant - Flip-Flops](https://brilliant.org/wiki/flip-flop/)
- [Wikipedia: Flip-Flop (Electronics)](https://en.wikipedia.org/wiki/Flip-flop_(electronics))

---
