Open On-Chip Debugger 0.12.0
Licensed under GNU GPL v2
For bug reports, read
	http://openocd.org/doc/doxygen/bugs.html
DEPRECATED! use 'adapter srst delay' not 'adapter_nsrst_delay'
DEPRECATED! use 'adapter srst pulse_width' not 'adapter_nsrst_assert_width'
Info : BCM2835 GPIO JTAG/SWD bitbang driver
Info : clock speed 2030 kHz
Info : SWD DPIDR 0x0bc11477
Info : [stm32f4x.cpu] Cortex-M0+ r0p1 processor detected
Info : [stm32f4x.cpu] target has 4 breakpoints, 2 watchpoints
Info : starting gdb server for stm32f4x.cpu on 3333
Info : Listening on port 3333 for gdb connections
[stm32f4x.cpu] halted due to debug-request, current mode: Thread 
xPSR: 0xf1000000 pc: 0x000002f0 msp: 0x20009000
Info : Listening on port 6666 for tcl connections
Info : Listening on port 4444 for telnet connections

OUTPUT OF OPENOCD WHILE COMMUNICATING OVER SWD
which implies it has a M0+ core
what?!
