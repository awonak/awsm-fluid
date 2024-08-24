# AWSM - Fluid

> [!NOTE]  
> This project is a work in progress and may contain errors.

3u 12hp Arduino based multi-purpose utility module. 

## Features

**Digital Inputs**

* 2 digital gate/trig inputs
* 2 buttons

**Analog Inputs**

* 4 slide potentiometers w/ addressable LEDs
* 4 CV inputs w/ attenuator pots, summed with each slide pot.

**Analog Outputs**

* 2 PWM 0-10v outputs w/ LED indicator
* Each output paired with additional output which can be an inverted copy (-10v - 0v) or bipolar output (-10v - 10v).

## Concept

This module is meant to be a platform for creating unique utility module scripts using the given inputs and outputs. Some firmware examples are:

* CV controlable ADSR with gate / retrig inputs, envelope curves selected via button, envelope output with EOR/EOF output trigger.
* Clocked burst generator with high gate output during burst sequence.
* Dual LFO w/ shape and rate.
* Random cv generator w/ envelopes.