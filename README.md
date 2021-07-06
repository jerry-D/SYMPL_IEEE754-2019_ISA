# 32, 64, 128 and 256-bit SYMPL IEEE 754-2019 Instruction Set Architecture Compute Engine.

(July 6, 2021) Update:  Below is a .gif showing the target 128-bit process executing a very simple routine to display vintage Textronix 401X plots on the Tera Term TEK display.  It shows the ULX3S coming up, the go command being entered from the debugger, and the target demo program being run.  The debugger has exlusive use of the Alternate display buffer while the target processor uses the Normal display buffer and can write to the TEK graphic plot display, as shown in the .gif animation.  It employs the auto-detection feature of Tera Term, so that the renderings go to the TEK display automatically.  When done, the user depresses buttons 1 & 2 on the ULX3S and the terminal automatically switches back to Alternate display buffer of the debugger. 

[![TEKgif](https://github.com/jerry-D/SYMPL_IEEE754-2019_ISA/blob/main/SYMPdemo2.gif)](https://github.com/jerry-D/SYMPL_IEEE754-2019_ISA/blob/main/SYMPdemo2.gif)

(June 28, 2021) Update:  the debugger now has source-level disassembly.  The animated .gif below shows an actual debug session starting from power-up message, then proceeding to Help menu, uploading a binary executable, uploading object listing file, setting harware breakpoint, running, hitting breakpoint, single-stepping, displaying data dump, editing a data memory location, single-stepping, then free-run with auto snap-shot occuring every 2 seconds.  While running in real-time, you can examine and edit any memory location on-the-fly, without having to force a breakpoint first, all without the need for any s/w routines on the target side, as it's all done in hardware.

[![RTMDXgif](https://github.com/jerry-D/SYMPL_IEEE754-2019_ISA/blob/main/SYMPL_RTMDX.gif)](https://github.com/jerry-D/SYMPL_IEEE754-2019_ISA/blob/main/SYMPL_RTMDX.gif)

(June 18, 2021) Update:  the debugger is up and running in the ULX3S FPGA.  Still need a couple weeks to do documentation and add the disassembler. Sorry for the delay.

(April 22, 2021)  A RADIONA ULX3S FPGA project board has been purchased and efforts are underway to create 32, 64, 128 and 256-bit versions of the SYMPL IEEE 754-2019 ISA Compute Engine that implements in hardware all computational and non-computational binary32 floating-point operations mandated by the IEEE 754-2019 standard.  

For a preview of what's to come, click on the thumb of a 17" x 24" poster-size preliminary information sheet below and then the "download" button once it appears.  This repository will be continually updated with FPGA flash file that you can use to flash your ULX3S FPGA with for evaluation purposes.  To obtain your RADIONA ULX3S board, visit CrowdSupply or MOUSER Electronics.  Be sure to order the model with the -85F FPGA.  

Be advised that it will probably be another 3-4 weeks before alpha is made available here.

[![poster](https://github.com/jerry-D/SYMPL_IEEE754-2019_ISA/blob/main/SYMPL_IEEE_754_poster_v1_3_thumb.png)](https://github.com/jerry-D/SYMPL_IEEE754-2019_ISA/blob/main/SYMPL_IEEE_754_poster_v1_3.png)


