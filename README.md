# Synchronous-FIFO
This project implements a Synchronous FIFO (First In First Out) using Verilog HDL for efficient data storage and transfer within a single clock domain.

In this design, both read and write operations are controlled by a single clock (clk), making it simpler and faster compared to asynchronous FIFO designs.

The FIFO uses binary counters for read and write pointers and generates full and empty signals based on pointer comparison.

**Features:**

- Single clock operation (common clock for read and write)  
- Simple pointer logic using binary counters  
- Full and Empty flag generation  
- Efficient and low-complexity design  
- High-speed operation due to single clock domain  

**Working:**

- Data is written into FIFO using clk  
- Data is read from FIFO using the same clk  
- Write pointer increments on write operation  
- Read pointer increments on read operation  
- Full condition occurs when FIFO is completely filled  
- Empty condition occurs when no data is available  

**Simulation and Verification**

- Verified using testbench  
- Functional validation through simulation waveforms  

**Tools Used:**

- Verilog HDL  
- Xilinx Vivado  
- Artix-7 FPGA (for synthesis & implementation)  
