# 306CA3
Computer Assignment: DTMF Decoder
Build a DTMF decoder. Your code should accept a tonal sequence and output a string of key presses.

Rules:
* Use a sampling rate of 8000 samples per second.
* Use a set of bandpass filters, not a FFT.
* For full credit, use FIR filters of length 31 or less or second order (two pole) IIR filters. You get partial credit for working implementations that use larger filters.
* You may assume the silence and tonal periods are both multiples of 400 samples. (This is a simplifying assumption.)
* You may not assume the tones or the silence periods are the same length.
