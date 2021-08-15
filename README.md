# Overdrive-pedal

## About
A simple overdrive circuit implemented with a OpAmp with soft clipping and a tone control. The OpAmp is configured as a non-inverting amplifier supplied with +9V and GND, with a 4.5V DC bias. The circuit is separated in 5 stages (see schematic image below the 3D model):
  1. Input: one Mono jack for audio;
  2. Equalization: capacitors to filter out some low noise and DC;
  3. Gain stage with soft clipping (made by the 2 opposed diodes on the OpAmp feedback) and low pass filter (capacitor on the OpAmp feedback, and grounded capacitor and resistor on the OpAmp negative input);
  4. Tone Control (Inpired by the Big Muff tone control circuit): basicaly a low pass filter in parallel with a high pass filter, united by a potentiometer to control the filtering.
  5. BJT buffer
  6. Output with volume control: a grounded potentiometer, where the output can be controlled from GND to the total distorced signal.

## Overdrive Schematic
*This is only the soft clipping and tone control circuit, without the inputs, outputs and supply circuits. Please open the Altium project for the full circuit.*

![Overdrive schematic](https://github.com/felipeb-oliveira/Overdrive-pedal/blob/master/images/schematic.PNG)

## Board
![Board top](https://github.com/felipeb-oliveira/Overdrive-pedal/blob/master/images/boardTop.PNG)
![Board bottom](https://github.com/felipeb-oliveira/Overdrive-pedal/blob/master/images/boardBottom.PNG)

