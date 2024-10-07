# CODETECH-TASK-TWO

# Finite State Machine (FSM) Design in Verilog/VHDL

## Project Overview

This project involves the design and implementation of a Finite State Machine (FSM) using Verilog (or VHDL). FSMs are sequential logic circuits that transition between different states based on inputs and can produce outputs accordingly. They are widely used in digital design for controlling systems with a defined sequence of operations.

## Features
- **FSM Design**: Implements different FSM types such as Mealy and Moore machines.
- **Testbench**: Testbench files are provided to simulate and verify the behavior of the FSM in various states and transitions.
- **Simulation**: The FSM design is simulated in the VLSI environment, and its performance is verified using waveform analysis.
- **Multiple Use Cases**: FSMs can be adapted for various applications such as traffic light controllers, elevator systems, vending machines, etc.



## FSM Details

### FSM Type
- **FSM Type**: Moore Machine
- **Number of States**: 3 states
- **Inputs**: 3 input signals
- **Outputs**: 1 output signal

### State Transition Diagram
A state transition diagram is included in the `/docs/` folder, which outlines all the states and transitions in the FSM based on input conditions.

### Design Flow
1. **State Definition**: Define states using enumerated types or parameters.
2. **State Transitions**: Use conditional logic (if-else or case statements) to manage transitions based on inputs.
3. **Output Logic**: Define outputs based on current state (Moore machine) or state/input combination (Mealy machine).

## Testbench and Simulation

### Testbench
The testbench file simulates the behavior of the FSM by applying different input combinations and observing the output and state changes. It ensures that the FSM transitions through all expected states correctly.

### Simulation Instructions
1. Run the simulation in your VLSI software.
2. Load the testbench file `fsm_testbench.v` (or `fsm_testbench.vhd`).
3. Use the provided waveform script (`fsm_waveform.do`) to generate and observe waveforms of inputs, outputs, and state transitions.
4. Verify that the FSM behaves as expected for all test cases.

   ## OUTPUT

   <div style="text-align: center;">
    <img src = "WhatsApp Image 2024-10-07 at 9.39.01 PM.jpeg" height = 80% width = 80% title = "Process Flow" >
</div>
   
   


