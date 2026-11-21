# AXI4 DMA Controller

A parameterized AXI4 Direct Memory Access (DMA) Subsystem designed in SystemVerilog. The project implements an AXI4-based DMA engine capable of transferring data between memory regions with minimal CPU intervention. The design follows a modular RTL architecture and is verified using simulation.

## Features

- AXI4-Lite Register Interface
- AXI Read Master
- AXI Write Master
- Control FSM
- Address Generator
- Parameterized FIFO
- Interrupt Controller
- Modular and parameterized RTL design
- Synthesizable SystemVerilog implementation

## Tools Used

- SystemVerilog
- Verilator
- GTKWave
- Yosys
- Ubuntu Linux
- Git & GitHub

## Project Structure

```text
AXI4-DMA-Controller/
├── rtl/                 # RTL source files
├── tb/                  # Testbench files
├── docs/
│   ├── block_diagram.png
│   ├── waveform/        # Simulation waveform screenshots
│   └── terminal_output/ # Terminal output screenshots
├── README.md
└── .gitignore
```

## Block Diagram

![AXI4 DMA Block Diagram](docs/block_diagram.png)

## Simulation Results

### 1. FIFO

**Waveform**

![FIFO Waveform](docs/waveform/fifo.png)

### 2. Address Generator

**Waveform**

![Address Generator Waveform](docs/waveform/add_gen.png)

**Terminal Output**

![Address Generator Terminal](docs/terminal_output/add_gen_terminal.png)

### 3. Control FSM

**Waveform**

![Control FSM Waveform](docs/waveform/cfsm.png)

**Terminal Output**

![Control FSM Terminal](docs/terminal_output/cfsm_terminal.png)

### 4. Register Interface

**Waveform**

![Register Interface Waveform](docs/waveform/reg_interface.png)

**Terminal Output**

![Register Interface Terminal](docs/terminal_output/reg_interface_terminal.png)

### 5. Read Master

**Waveform**

![Read Master Waveform](docs/waveform/read_master.png)

**Terminal Output**

![Read Master Terminal](docs/terminal_output/read_master_terminal.png)

### 6. Write Master

**Waveform**

![Write Master Waveform](docs/waveform/write_master.png)

**Terminal Output**

![Write Master Terminal](docs/terminal_output/write_master_terminal.png)

### 7. Interrupt Controller

**Waveform**

![Interrupt Controller Waveform](docs/waveform/interrupt.png)

**Terminal Output**

![Interrupt Controller Terminal](docs/terminal_output/interrupt_terminal.png)

## Team Contributions

Developed as a collaborative academic project.

## My Contribution

- Address Generator
- Interrupt Controller
- Top-level integration
-
