# me_Ws2812b -- Send data to WS2812B LED stripe

Documentation for me_Ws2812b library.

# What

Arduino. AVR. ATmega329/P. 16 MHz. LED stripe. RGB. WS2812B. Function.
C. Assembler. Standalone. GPL3.

Datasheet: Datasheets/RGB LED stripe - WS2812B.pdf

# API

Core


## Timings

* _Ideally_ we want 1250 ns between any bits.
* _Specification_ allows 1100 .. 1400 ns between bits.
* _Implementation_ has 1620 ns between bits in separate bytes.
* _Practically_ it works.
* _Probably_ controller can tolerate LOW times up to 50 us timeout.

* Interbit timings
  * 0 -- Images/0.png
    #. HIGH part -- Images/0.High.png
    #. LOW part -- Images/0.Low.png
  * 1 -- Images/1.png
    #. HIGH part -- Images/1.High.png
    #. LOW part -- Images/1.Low.png
* Interbyte timings -- Images/Interbyte.png

