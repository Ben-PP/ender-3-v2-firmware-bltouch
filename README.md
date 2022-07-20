# Marlin firmware for Ender 3 v2 with some modifications

This is Marlin firmware customized for my Creality Ender 3 v2 with bltouch and microswiss direct extruder

## Changes from example Ender 3 v2 firmware

Following changes have been made to make this suitable for my machine:
- Bed size changed to 225,210,210 (X,Y,Z)
- XY min positions changed to -8,-14 (X,Y)
- Enabled Bltouch abl-probe
- Probing with 2 probes 70*60 movement 10*60 fast pass and slow pass is half the fast pass
- Nozzle to probe offsets: -45,-6,-3.8 (X,Y,Z)
- Some other misc settings

## Marlin github
https://github.com/MarlinFirmware/Marlin

## License

Marlin is published under the [GPL license](/LICENSE) because we believe in open development. The GPL comes with both rights and obligations. Whether you use Marlin firmware as the driver for your open or closed-source product, you must keep Marlin open, and you must provide your compatible Marlin source code to end users upon request. The most straightforward way to comply with the Marlin license is to make a fork of Marlin on Github, perform your modifications, and direct users to your modified fork.

While we can't prevent the use of this code in products (3D printers, CNC, etc.) that are closed source or crippled by a patent, we would prefer that you choose another firmware or, better yet, make your own.
