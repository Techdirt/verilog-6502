A Verilog HDL version of the old MOS 6502 CPU.

Note: the 6502 core assumes a synchronous memory. This means that valid
data (DI) is expected on the cycle *after* valid address. This allows
direct connection to (Xilinx) block RAMs. When using asynchronous memory,
I suggest registering the address/control lines for glitchless output signals.

[Also check out my new 65C02 project](https://github.com/Arlet/verilog-65c02-fsm)
which is a complete rewrite, and aims to improve readability as well as performance.

Have fun. 
