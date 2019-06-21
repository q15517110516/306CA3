# CA3
Build a DTMF encoder.  The Wikipedia page for DTMF gives a table of the tonal frequencies.  For each keypress of a telephone keypad, the system combines a row tone and a column tone and sends both.  

Your code should take a string of arbitrary length, e.g., "(302)-831-8008" (my office number) and encode the values that correspond to valid keys and ignore the rest.  E.g., "12  34aB-cd$%^&76" should output the tones for "1234abcd76" (allow both 'b' and 'B', etc.).   Make each keypress a half second long and put a tenth of a second of silence between the keypresses.  Do not add a a silence period at the end.  Ideally, both the silence length and the keypress length should be easily settable (and resettable) parameters.  

Use Fs=8000, the standard sampling rate for telephone quality audio.

As always, include documentation describing your code and how your solution works.
