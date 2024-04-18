# NES Controller Breakout Board

<!-- Harry Boyd - hboyd255@gmail.com - 16/04/2024 -->

This is a simple breakout board for the NES controller.

That I have made a
[KiCad library](https://github.com/HBoyd255/nes-controller-port) for the NES
port, and the port is available on
[zedlabz.com](https://www.zedlabz.com/products/controller-connector-port-for-nintendo-nes-console-7-pin-90-degree-replacement-2-pack-black-zedlabz?_pos=8&_sid=b3d25e834&_ss=r).

The reason I made this board is for debugging and testing. The NES controller is
beautifully simple, in that it contains a single 4021 shift register. This makes
it compatible with pretty much any microcontroller that has at least 3 spare
GPIO pins.

## Logic Lab

This board is part of a lab that I am creating for the York Engineering Society.
The lab is designed to give insight into how 4000 series logic chips work, and
despite their age, how they are still useful today.

![A render of the PCB](images\PcbRender.png)

## Fabrication

To fabricate this board, zip the contents of the `gerber` folder and upload them to your chosen PCB manufacturer. I would recommend using JLCPCB.
