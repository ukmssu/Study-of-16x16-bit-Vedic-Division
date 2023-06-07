# Study-of-16x16-bit-Vedic-Division
The primary goal of this project is to utilize the straightforwardness of the Vedic sutras to create division modules that can enhance the speed of a Digital Signal Processor.

## Abstract
The need for VLSI architecture to handle complex systems has led to the development of high-speed divider architectures. There are several methods present in Vedic mathematics but here Parvartya sutra is used. This formula can be applied to all cases of division, making it an efficient method for dividing large numbers with respect to delay and power consumption. In this report, a 16-bit divider architecture was implemented using the Parvartya sutra, synthesized, and simulated using the Xilinx ISE simulator. The design was then implemented on a verilog HDL in Xilinix Vivado 2020.2. The output parameters, including propagation delay and device utilization, were calculated from the synthesis results. This report found that this architecture offers faster speeds than other architectures presented. This architecture has the potential to be used in various applications, including digital signal processing, cryptography, and processor arithmetic unit design, among others.

KEYWORDS: Vedic Mathematics; Vedic Divider; Paravartya Sutra; VLSI design; Digital Signal Processing; Algorithms; Sutras; Verilog HDL

## Objective of the work
The main objectives of this project are:

• Implementing Paravartya sutra in decimal number system and then in binary number system.

• Performing the delay and area analysis of the different division modules.

• Developing different techniques to reduce the latency of divider.

• Comparing the performance of the proposed divider with the existing dividers.

## Conclusion
The proposed Paravartya division module has implemented various techniques to reduce its delay, including developing dedicated adder and multiplier modules, transforming multiplication operation into addition of two terms, using Vedic UT multipliers, compressor adders, rearranging terms for maximum parallelism, and more. When compared with existing dividers, the proposed 16-bit by 16-bit Paravartya divider was found to be faster by 4.5ns than the serial implementation of the Paravartya sutra. Additionally, even after producing a quotient with a fraction part that is accurate up to one decimal place, the proposed Paravartya divider has at least a 62% reduction in delay compared to the SRT, Netwon-Raphson, and Nikhilam dividers, which produce quotient and remainder separately. Moreover, the proposed divider has a 33.79% reduction in delay when compared to the non-restoring division algorithm and a 38.46% reduction in delay with respect to the combinational array divider.
