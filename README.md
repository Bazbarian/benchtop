# Benchtop

A browser electronics lab: build circuits on a breadboard, wire up an Arduino Uno, and watch them run live.

**Live site:** https://YOUR-USERNAME.github.io/benchtop/

## What it does

- Breadboard, Arduino Uno, batteries, supply rails, resistors, LEDs, buttons, switches, potentiometers, 7-segment display
- Logic gates (AND, OR, NOT, NAND, NOR, XOR), D flip-flop, clock, logic inputs and probes
- A nodal circuit solver runs live — LEDs are modeled as diodes and burn out without a resistor
- Arduino sketches in C++ (setup/loop, digital/analog I/O, PWM, delay, millis, Serial monitor)
- PCB view renders the same circuit as copper traces

## Controls

Drag parts from the left. Drag from any pin or hole to draw a wire. `R` rotates, `Del` deletes, `Ctrl+Z` undoes, scroll zooms, drag empty space to pan. Your bench autosaves in the browser.

## Running locally

It's a single static file — open `index.html` in a browser, or serve the folder:

```sh
python3 -m http.server 8000
```
