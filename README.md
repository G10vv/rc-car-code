# rc-car-components 

BTS7960 for throttle

L298n for steering

ESP32 (with expansion board) as the brain

LM386 audio amp for beeping

2 LEDs for headlights

2 LEDs for fog lights

2 LEDs for brake lights

2 LEDS for reverse lights

1 100 ohm resistor on all LED inputs

# PINOUT

### LM386 IN pin in D32
### VCC in 3v and GND in GND pin

## LEDs

D5 brake lights

D16 reverse lights

D2 headlights

D15 fog lights

all leds are GND shared

## MOTORS

### BTS7960 (throttle)

D26 R_PWM

D27 L_PWM

D14 R_EN

D12 L_EN

VCC is in the 5v option in the expansion board

GND is shared in the GND pin

B+ positive wire battery

B- negative wire battery

M- throttle motor wire

M+ throttle motor wire

### L298n (steering)

ENA pin has a jumper wire so is always on

D25 IN1

D33 IN2

12v+ positive battery wire

GND negative battery wire

OUT1 motor wire

OUT2 motor wire






