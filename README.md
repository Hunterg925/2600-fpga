# 2600-fpga
An FPGA implementation of the Atari 2600 TV game console from 1977.

NOTE: this implementation an experiment designed and simulated in Vivado.
At this time, it is designed to work for Breakout (Breakaway IV).

You must convert your breakout ROM image from a .a26 file to a .mem file to be loaded into Vivado as memory.

On hardware, the only two outputs at this time are VGA video and single-pin PWM audio.
