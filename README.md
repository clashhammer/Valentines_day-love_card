# Valentine's Day Love Card ❤️

A small Valentine's Day card built with **14 red LEDs** and an **astable oscillator** that makes the LEDs blink.

The repository includes the PCB files, so you can order the board and assemble one yourself without having to design the circuit from scratch.

## Main Parts

| Quantity | Part |
|---:|---|
| 14x | Red LEDs |
| 2x | 220 µF Capacitors |
| 7x | 470 Ω Resistors |
| 2x | 5 kΩ Resistors |
| 2x | 1 kΩ Resistors |
| 1x | 10 kΩ Resistor |
| 1x | Switch |
| 1x | AO3400 MOSFET |
| 2x | 2N2222 Transistors |
| 1x | 9V Battery Clip |
| 1x | 9V Battery |

## Assembly

### Resistors

| Reference | Value |
|---|---:|
| R1 | 10 kΩ |
| R2, R4 | 1 kΩ |
| R3, R5 | 5 kΩ |
| R6–R12 | 470 Ω |

### LEDs

Insert the LEDs according to the PCB markings:

- **Anode (+)** → circular hole
- **Cathode (−)** → square hole

### Capacitors

The electrolytic capacitors are polarized:

- **Positive (+)** → square hole
- **Negative (−)** → circular hole

Make sure the polarity is correct before soldering them.

### Transistors

Install the 2N2222 transistors so that the curved side of the transistor matches the outline printed on the PCB.

The emitter pins should go into the corresponding square holes.

### Battery

Connect the 9V battery with the correct polarity:

- **Positive (+)** → square hole
- **Negative (−)** → circular hole

## Removing the Logo

If you want to order the PCB without the logo, remove the front silkscreen file:

`Love_Card-F_Silkscreen.gto`

before sending the Gerber files to the PCB manufacturer.

## Video

I also made a video showing the finished card and how it works:

[Watch the video on YouTube](https://www.youtube.com/watch?v=TKKQ9AhvqFg)

---

Thanks for checking out the project! ❤️

<img width="1200" height="1600" alt="image" src="https://github.com/user-attachments/assets/4d4faa7e-afa9-41c9-9ec4-0d4918536eab" />
