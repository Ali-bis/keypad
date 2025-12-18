The Void Macro Pad\

This custom 3x3 mechanical keypad was designed to give me a speed boost in Blender and coding. It's built around CircuitPython so I can easily remap the keys without worrying about messing with the code.

Why I wanted to build this\

I got tired of having to remember a million key combos for simple tasks like Saving, Undoing, and Rendering. It was really slowing me down. Plus I had a hankering to learn how to design a PCB from scratch using the Seeed XIAO board. (Also, I thought it would be a blast!)

How does it work\

The brain of this operation is a Seeed XIAO RP2040. It's connected up to 9 mechanical switches (I'm a fan of Cherry MX) laid out in a matrix. The details are below...

Firmware: I'm running KMK (CircuitPython keyboard library) to make it all work.\

Features: When hooked up to a computer it's a pretty standard USB HID keyboard. I also snuck in a rotary encoder which lets me control volume and zoom with a nifty little wheel.

The Parts\

Controller: Seeed XIAO RP2040\

Switches: 9 x Cherry MX Blue switches\

Diodes: 9 x 1N4148 (just in case I didn't want to deal with ghosting on my keyboard)\

Encoder: EC11 Rotary Encoder

Status\

The PCB design is done and now I'm just waiting on the boards to arrive. Once they do, I'll be able to pop in some switches and 3D print the case. 
