# lard84

A custom 75% ansi low-profile keyboard.

1. [PCB](#PCB)
2. [Plate](#Plate)
3. [Case](#Case)

![Case, PCB and plate assembled](screenshots/case-v6-with-pcb-and-plate.png)

## PCB

The PCB (lard84.kicad_pro) is an 84-key design based on the [RP2350 Stamp](https://lectronz.com/products/rp2350-stamp), made using KiCad 8.0.
It is entirely hand-solderable (smallest footprint is 0603).

The design features a micro-usb port, full n-key rollover using a diode for each switch, a status LED, and apparent debug pins for development.

Key placement follows an ![ANSI 75% layout](https://docs.keebd.com/information/keyboard-layouts#75-ansi).

The design supports ![Gateron KS-33 low-profile switches](https://www.gateron.co/products/gateron-low-profile-mechanical-switch-set), and features holes
for the associated ![low-profile stabilizers](https://www.gateron.com/products/gateron-low-profile-plate-mounted-stabilizer).

![A screenshot of the PCB in KiCad](screenshots/lard84-v1.0.png)

## Plate

The top plate supports the switches, adds rigidity and gives a nice finish. It was made in Fusion360.
It is a relatively simple design with holes for each key, two holes for the Backspace, Space, Enter and LShift stabilizers, and 10 mounting holes for screws.

One key challenge was to figure out the placement and shape for the stabilizer holes, because of poor documentation and imprecise datasheets.

![Plate in Fusion360](screenshots/plate-and-pcb-face.png)

## Case

The case (case.FCStd) is a 3D-printable plastic enclosing and two feet for a more comfortable typing angle.

The enclosing features mounting holes for the PCB and plate, and anti-warping structural elements.

![The case in FreeCad](screenshots/case-v6-bare.png)
