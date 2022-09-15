Mixing Board: Jekyll One
========================

The mixing board is a hodge podge of components, with very
little thought put into layout, routing and labels and
includes myriad headers to organize their connection.

It is meant to make it easy to re-wire and experiment with
various routing options and includes a variety of components
for evaluation.

It is also an opportunity to try out a real-world PCB with
footprint layouts.


Components
----------

See [thirdparty-datasheets](https://github.com/firefly/thirdparty-datasheets/#displays) for more details.

- ZJY133T-IF05 display
- USB-C with a AMS1117-3.3 as a power sub-system
- ESP32-C3-MINI-1 MCU module
- 4x tactile buttons


Pins
----

- MCU
  - Full ESP32-C3-MINI-1 GPIO pins, 3V3 and enable
- USB Power Sub-system
  - 3.3v power rail
  - ground rail
  - exposed CC1, CC2 and shield
- Display
  - Full 24-pin connector for FPC with both normal and inverted connection
- 4x Buttons


Design
------

![Image](./sample-pcb.png?raw=true)

![Image](./sample-3d.png?raw=true)


Current Focus
-------------

- wiring arrangement and routing for the display
- wiring arrangement and routing for the buttons
- effectiveness of the AMS1117-3.3 via USB-C
- footprint for the USB-C connector
- footprint for the screen as a top-mounted


Notes
-----

- obviously this should not be used for any production purposes


License
-------

MIT License.
