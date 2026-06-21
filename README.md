## Interview-Focused Notes for Combinational Logic Designs

### 🔹 Logic Gates

Basic building blocks of all digital circuits. Interviewers often ask truth tables and gate implementation using only NAND/NOR gates.

### 🔹 Half Adder

Adds two 1-bit inputs and generates Sum and Carry outputs. Frequently asked to test understanding of XOR and AND gate usage.

### 🔹 Full Adder

Adds three 1-bit inputs (A, B, Cin) and produces Sum and Carry. Core building block for ALUs, processors, and arithmetic circuits.

### 🔹 Half Subtractor

Performs subtraction of two 1-bit inputs and generates Difference and Borrow. Common question for understanding binary arithmetic.

### 🔹 Full Subtractor

Subtracts three inputs (A, B, Bin) and generates Difference and Borrow outputs. Used in arithmetic units and digital processors.

### 🔹 2:1 Multiplexer (MUX)

Selects one of two inputs based on a select signal. One of the most commonly asked Verilog coding questions in interviews.

### 🔹 4:1 Multiplexer (MUX)

Routes one of four inputs to a single output using select lines. Important for understanding data selection and combinational design.

### 🔹 8:1 Multiplexer (MUX)

Selects one input from eight inputs. Frequently asked as a scalable design problem in RTL interviews.

### 🔹 1:2 Demultiplexer (DEMUX)

Routes one input to one of two outputs based on select signals. Used in communication and data distribution systems.

### 🔹 1:4 Demultiplexer (DEMUX)

Distributes one input among four outputs. Interviewers may ask its relation to decoders.

### 🔹 1:8 Demultiplexer (DEMUX)

Expands a single data line to eight output paths. Useful for understanding signal routing concepts.

### 🔹 2:4 Decoder

Converts a 2-bit input into one of four active outputs. Widely used in memory address decoding and chip selection.

### 🔹 3:8 Decoder

Converts a 3-bit input into one of eight outputs. Commonly used in memory systems and digital control logic.

### 🔹 4:2 Encoder

Converts one active input among four lines into a 2-bit binary code. Frequently asked alongside decoder concepts.

### 🔹 8:3 Encoder

Encodes one active input among eight lines into a 3-bit binary output. Important for interrupt handling and communication systems.

### 🔹 4:2 Priority Encoder

Assigns priority when multiple inputs are active simultaneously. A very common interview question for RTL and FPGA roles.

### 🔹 Binary to Gray Converter

Converts Binary code into Gray code where only one bit changes between consecutive values. Used in asynchronous counters and CDC applications.

### 🔹 Gray to Binary Converter

Converts Gray code back to Binary format. Frequently asked together with Binary-to-Gray conversion logic.

### 🔹 Even Parity Generator

Generates a parity bit to ensure an even number of 1's in data. Widely used in error detection systems.

### 🔹 Even Parity Checker

Verifies received data using the parity bit. Important for understanding data integrity and communication protocols.
