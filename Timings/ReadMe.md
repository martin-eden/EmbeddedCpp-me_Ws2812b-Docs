# Timings

Bits transfer times.

Any bit is transferred as HIGH and LOW pulses. Bit "1" has longer HIGH
pulse. Total transfer time for any bit should be the same.

When bits are in different bytes, transfer time is longer as we need
to fetch next byte.

| What | Value (ns) | Image |
:-----:|:----------:|:------:
Zero bit frame | 1240 | ![Zero bit frame](0.%20Frame.png)
Zero bit pulse | 320 | ![Zero bit pulse](0.%20Pulse.png)
One bit frame | 1240 | ![One bit frame](1.%20Frame.png)
One bit pulse | 884 | ![One bit pulse](1.%20Pulse.png)
Interbyte frame | 1616 | ![Interbyte frame](Interbyte%20frame.png)
