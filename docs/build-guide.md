# PicoStepSeq Build Guide

To assemble the PicoStepSeq you will need a flush cutter, soldering iron, solder, and solder flux.

## Parts Needed

For basic USB MIDI functionality:

    1 - "picostepseq" PCB (OSHpark, also see "hardware" directory for gerbers)
    1 - Raspberry Pi Pico (Adafruit, Digikey)
    1 - 0.96" I2C OLED SSD1306 128x64 display (Amazon)
        w/ pins in order GND, VCC, SCL, SDA; some have GND & VCC swapped
    1 - EC11 style rotary encoder w/ switch (Digikey, Adafruit]
    8 - "step switch" w/ built-in LED (Adafruit]
    8 - resistor 1k (R1-R8, 500 ohm also works) (Digikey, Adafruit]
    1 - encoder knob ("Davies 1900" style works well, Adafruit)

For both USB + Serial MIDI, add:

    2 - 3.5mm TRS jack, SJ-3523-SMT-TR (J1,J2) (Digikey)
    1 - 6N138 optoisolator (U2) (Digikey)
    1 - 100n capacitor (C1) (Digikey, Adafruit)
    1 - resistor 10 ohm (R1)
    1 - resistor 30 ohm (R2) (47 ohm also works)
    1 - resistor 220 ohm (R3)
    1 - resistor 4.7k ohm (R4)

## Assembly

To assemble the PicoStepSeq:

1. Start by soldering the Pico headers to the PCB.  You may need a vise or shim to help raise the PCB to keep it stable while soldering.
2. Solder the header for the display to the PCB.
3. 