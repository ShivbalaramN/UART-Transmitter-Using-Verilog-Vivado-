**📡 UART Transmitter (Verilog HDL)**

**📌 Overview**

This project implements a UART (Universal Asynchronous Receiver/Transmitter) Transmitter using Verilog HDL. It serially transmits 8-bit parallel data following standard UART protocol.

The design converts parallel data into a serial bit stream with start and stop bits, widely used in embedded and communication systems.

**🚀 Features**
 8-bit data transmission
 
 Asynchronous serial communication
 
 Start bit and stop bit implementation
 
 Busy flag for transmission status
 
 Designed and simulated using Vivado

**Inputs and Outputs**

**Inputs:**

 clk → System clock

 reset → Reset signal

 data_in [7:0] → Parallel data input

 tx_start → Start transmission

**Outputs:**

   tx → Serial output

   busy → Transmission status

**🧪 Simulation Details**

**Tool Used**: Xilinx Vivado


**Testbench**: tb_uart_tx.v

**✅ Behavior:**

 Idle state → tx = 1

 Start bit → 0
 
 Data bits → transmitted LSB first
 
 Stop bit → 1
 
**📊 Waveform Description**

The waveform shows correct UART transmission sequence:

 Start bit initiation
 
 Sequential bit shifting
 
 Stop bit completion
 
 Busy signal active during transmission

 <img width="1919" height="1018" alt="Waveform" src="https://github.com/user-attachments/assets/d2462a61-2a3e-43d7-87a1-79ed011aa6c1" />

**👨‍💻 Author**

 Shiv Balaram N

 B.E. Electronics and Communication Engineering (ECE)

 Anna University Chennai
