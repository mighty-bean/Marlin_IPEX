# Customized Marlin for IPEX Printers

*This is a work in progress. Not fully tested.*

Details available on YouTube: https://youtu.be/aYOCjpKOlpE

Marlin contains support for IDEX printers (*Independant Dual Extruders*) where two independant carriages can move on the x-axis, each containing one extruder. This allows for two separate filaments to be used within the same print, or printing two models simultaneously in mirrored mode. 

A unique printer configuration is added in this customized version of Marlin, which we call **IPEX** for *Independant Paired Extruder*s. As with IDEX printers, there are two independent carriages on the x-axis, but we place a pair of extruders on each. This allows for a total of four independent filaments printed withing the same session, or two filaments on each side of mirrored mode. 

# BIGTREETECH Octopus V1.0

Our solution utilizes the BIGTREETECH Octopus V1.0 motor control board to drive the 8 stepper motors needed to run the IPEX printer.

Portions of this Marlin customization were taken from the BIGTREETECH Octopus v1.0 code base which enables the use of Marlin on the Octopus control board.

[Octopus V1.0 Github](https://github.com/bigtreetech/BIGTREETECH-OCTOPUS-V1.0/tree/master/Firmware/Marlin-bugfix-2.0.9.3.x)
[Octopus V1.0 Product Info](https://biqu.equipment/en-au/collections/control-board/products/bigtreetech-octopus-v1-1?gclid=CjwKCAiApvebBhAvEiwAe7mHSP9-mZzHdbQjxB_1DrQDPsfona7W1Jz2poWtOh5z_JgSiBTobKbg0BoCGgkQAvD_BwE)

# Marlin 3D Printer Firmware

See the Marlin Github page for details and background on Marlin

![GitHub](https://img.shields.io/github/license/marlinfirmware/marlin.svg)
![GitHub contributors](https://img.shields.io/github/contributors/marlinfirmware/marlin.svg)
![GitHub Release Date](https://img.shields.io/github/release-date/marlinfirmware/marlin.svg)
[![Build Status](https://github.com/MarlinFirmware/Marlin/workflows/CI/badge.svg?branch=bugfix-2.0.x)](https://github.com/MarlinFirmware/Marlin/actions)

<img align="right" width=175 src="buildroot/share/pixmaps/logo/marlin-250.png" />

Additional documentation can be found at the [Marlin Home Page](https://marlinfw.org/).

## License

Marlin is published under the [GPL license](/LICENSE) because we believe in open development. The GPL comes with both rights and obligations. Whether you use Marlin firmware as the driver for your open or closed-source product, you must keep Marlin open, and you must provide your compatible Marlin source code to end users upon request. The most straightforward way to comply with the Marlin license is to make a fork of Marlin on Github, perform your modifications, and direct users to your modified fork.

While we can't prevent the use of this code in products (3D printers, CNC, etc.) that are closed source or crippled by a patent, we would prefer that you choose another firmware or, better yet, make your own.
