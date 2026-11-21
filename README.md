# AXI4 DMA Subsystem

A parameterized AXI4 Direct Memory Access (DMA) Subsystem designed in SystemVerilog.
The project implements an AXI4-based DMA engine capable of transferring data between
memory regions with minimal CPU intervention.The design follows a modular RTL
architecture and is verified using simulation.

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
AXI4-DMA-Subsystem/
├── rtl/                 # RTL source files
├── tb/                  # Testbench files
├── netlist/             # Synthesis outputs
├── README.md            # Project documentation
└── .gitignore           # Git ignore rules 
```

## Block Diagram
![AXI4 DMA Subsystem](docs/block_diagram.png)


## Simulation Results

### FIFO

**Waveform**

![FIFO Waveform](docs/waveforms/fifo.png)

---

### Address Generator

**Waveform**

![Address Generator Waveform](docs/waveforms/add_gen.png)

**Terminal Output**

![Address Generator Terminal](docs/terminal_output/add_gen_terminal.png)

---

### Control FSM

**Waveform**

![Control FSM Waveform](docs/waveforms/cfsm.png)

**Terminal Output**

![Control FSM Terminal](docs/terminal_output/cfsm_terminal.png)

---

### Register Interface

**Waveform**

![Register Interface Waveform](docs/waveforms/reg_interface.png)

**Terminal Output**

![Register Interface Terminal](docs/terminal_output/reg_interface_terminal.png)

---

### Read Master

**Waveform**

![Read Master Waveform](docs/waveforms/read_master.png)

**Terminal Output**

![Read Master Terminal](docs/terminal_output/read_master_terminal.png)

---

### Write Master

**Waveform**

![Write Master Waveform](docs/waveforms/write_master.png)

**Terminal Output**

![Write Master Terminal](docs/terminal_output/write_master_terminal.png)

---

### Interrupt Controller

**Waveform**

![Interrupt Controller Waveform](docs/waveforms/interrupt.png)

**Terminal Output**

![Interrupt Controller Terminal](docs/terminal_output/interrupt_terminal.png)
