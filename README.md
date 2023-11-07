# PicoCNC

[Available on Tindie.](https://www.tindie.com/products/philba/picocnc/)

A breakout board that, along with grblHAL and a Rapsberry Pi Pico microcontroller, creates a powerful CNC motion controller for devices like routers, mills, lasers and lathes.  Using grblHAL, it forms the basis of a motion control system with advanced features.

[System builder's Resources](https://www.grbl.org/resources)


![PicoCNC](https://github.com/phil-barrett/PicoCNC/blob/main/PicoCNC.jpg "PicoCNC")

Key features of the PicoCNC board.
* Supports up to 4 Axes via Screw Terminal and Pin Header.
* Spindle control.
  - PWM (5V).
  - Direction (5V).
  - 0-10V.
  - 12V PWM supported (via open collector output).
* Limit Switches for each axis.
  - Supports switches or powered proximity sensors.​
  - 12V for better EMI immunity.
  - Separate power input for full isolation
  - Opto-isolated
* Relay support
  - Directly drive up to 7 relay coils via open collector outputs.​
  - Relay Coil voltage selectable between +5V or +12V.
  - Drive up to 11 SSR or Logic Level relays.
* Isolated standard Grbl input controls: Cycle Start, Feed Hold, EStop and Safety Door.​ Opto-Isolated.
* Opto-Isolated Probe input.
* Supports both Pico and Pico W.
* USB and WiFi (with Pico W) connection support.
* Micro SD Card socket.  Allows storage of GCode programs.  GCode programs may be run from the SD Card.
* Dust Collection support.
  - Dust Collection relay and TTL output ganged to Spindle. 
  - Header for a switch to manually run Dust Collector.
* Flexible power input.  Two 12V sections, one for Stepper/Servo output, relays and spindle control, one for isolated limit, probe and control inputs. The two sections may be joined for the budget conscious builder. On board 5V generation.​
* LED indicators for 12V inputs, +5V​​ and spindle active.
* Open collector outputs allow adding pull-up resistors on the board.
* Expansion headers for I2C, SPI and UART.  UART 3.3V/5V translation supported.
* Powered by open source software - grblHAL.

