3340 Voltage Controlled Oscillator

User Guide

This module is a performance focused take on the classic CEM3340 Curtis chip based oscillators heard in historic synthesizers like the Prophet 5 and Memorymoog.

The most useful features of the chip are made accessible and optimised for sending or receiving control. Panel controls are intended to allow quick and unobstructed access to musical ideas.


Controls

OCTAVE

Rotary switch spanning 4 octaves. Great for varying the pitch of melody lines but also like a clock divider/multiplier in low frequency (LF) mode.


FREQ

A linear frequency control. 

In audio frequency (AF) mode the knob spans exactly two octaves. The middle of the potentiometer (the center octave note) is detented, so you can feel where it is. This pitch can be set to a known note by the MASTER TUNE, making it easy to return to guaranteed tuning at any time. Because the knob spans two octaves, any desired pitch is available both an octave up and down. This can be used to extend the range of the OCTAVE switch.

In low frequency (LF) mode the knob spans the range of the oscillator, from very slow (around 4 seconds per cycle) right into audio rate - which is valuable for external modulation possibilities.

The oscillator’s pitch range can be pushed far beyond these panel controls by external CV, either negative or positive.



LF/AF

A slide switch that selects between the low frequency and audio frequency mode.


CV

±12V compatible. Two input jacks make it easy to add vibrato or other frequency modulation to your melody line or LFO without an external CV mixer. Scalable to 1V/Oct.


SQUARE WAVE

Outputs the oscillator’s square waveform. When there is no input to the pulse width modulation (PWM) jack the waveform has a 50% duty cycle. The waveform’s amplitude ranges from 0V to +5V peak.


PWM

Controls the pulse width (normally at lower frequencies called duty cycle) of the square wave output. This is the amount of time within a single cycle that the amplitude of the waveform is high vs low. A wide continuum of character is available, from full to nasal sounding. 

The input sees control voltages ranging from 0V to +5V. Voltages outside this range are allowed but will not have an effect. 

It is not possible to send a control voltage to the PWM input that will result in the square waveform making no sound. 

You can patch an unused output back into the PWM input to achieve a different square wave sound, and because all outputs also range from 0-5V two 3340 VCO modules patch nicely with each other.

Note the PWM input has no effect on the triangle and ramp waveforms.


TRIANGLE WAVE

Outputs the oscillator’s triangle waveform. The waveform’s amplitude ranges from 0V to +5V peak.


RAMP WAVE

Outputs the oscillator’s ramp waveform. Also called a sawtooth wave. The shape of the waveform is exactly as drawn on the panel, a slow positive rising edge to steep decay. The waveform’s amplitude ranges from 0V to +5V peak.




MASTER TUNE

This trimpot is hidden inside the leftmost CV input. It is adjusted with the small flat head screwdriver provided with your module. It sets the lowest frequency possible when there is no external CV input. With the FREQ knob set in the center position you can use this to match the tuning of multiple oscillator modules in your system or calibrate the overall pitch of the module for use with a MIDI-CV controller.



Additional Notes

For instruction on how to calibrate the 3340 VCO refer to the build document.

All inputs and outputs are protected against signals within the standard Eurorack range of ±12V.

The power cable is reverse polarity protected, but you should always take care to plug it in correctly. The triangular symbol on an IDC socket as well as the red lead on standard ribbon cables (and the provided rainbow cable) denotes -12V and goes toward the RED indicator written on the PCB.

The current draw of the module for +12V and -12V  is 12.6mA.

The module is 4hp wide with a depth (measured from the backside of the panel, including IDC header) of 51mm.

Schematics are available on Github.
