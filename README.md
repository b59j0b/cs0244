java c University of Edinburgh Electrical Engineering
Data Converter Design in Simulink
Simulink Design Assignment
Design an audio band ADC with the following specifications over 20 Hz - 20 kHz:
[1] Maximum stable input amplitude (MSA) at least +/-0.85 for a full-scale input range of +/-1.0.
[2] Signal to quantisation noise ratio at MSA at least 105 dB.
[3] Total (audio band only) harmonic distortion at input level 1 dB below MSA less than -95 dB.
[4] NO audio band limit cycles or tones exceeding the quantisation noise power (i.e., no visible spurious
peaks rising above the noise floor)
You may choose ANY appropriate modulator architecture (order, quantisation levels, OSR). Remember to clearly state and justify any design decisions or calculations you make.
A standard 24.576 MHz master clock is available (512×the common 48 kHz hi-fi audio Nyquist rate). You may use any modulator sample rate derived by dividing the master clock by a power of 2, e.g. 24.576 MHz, 12.288 MHz, 6.144 MHz, 3.072 MHz, 1.536 MHz etc.
You should design your modulator using Simulink system level (choose from any of the modulator schematics in labs 1-5 or define your own).
Your report should contain the following (in the order suggested):
1. Justify the choice of modulator structure, which may be drawn from those within the libraries made available during the lab sessions OR yo代 写program、 Python/C++
代做程序编程语言ur own custom structure. You may use the sigma-delta design toolbox to synthesize the coefficients for higher order structures. Print and include the Simulink schematic of your modulator. (20%)
2. Justify the modulator order, oversampling ratio, use (or not) of multi-bit feedback and dynamic element matching scheme (including any element matching assumptions), use (or not) of dither. Include a conclusions and summary table of all specs, modulator options considered and performances. (20%)
3. Include all appropriate design calculations and simulations to confirm that the chosen modulator meets the specification under the assumption of ideal components. (10%)
4. Perform a full set of Simulink simulations demonstrating your modulator’s tolerance of finite dc integrator gain, coefficient mismatch, practical DAC element mismatch and integrator saturation ISAT=1. (25%)
5. Demonstrate your modulator’s stability and absence of limit cycle tones under different input conditions (frequency, amplitude, dc, step etc.) for ideal and non-ideal components. (15%)
6. Demonstrate the dynamic range scaling of the integrator outputs. (10%)
Your report should be maximum 20 pages in length (not including any Appendices). Assignment issued Wednesday 15th January 2025.
Assignment hand-in date Monday 24th March 2025 before 2pm via Turnitin.

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
