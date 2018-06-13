# `avr`: Alvise Vidolin's Reverberator

Alvise Vidolin's reverberator is a noise convolution model reverberator.

## Description

`avr` is designed as follows:

* source and first reflections are calculated in the _standard way_(tm)
* an algorithm is designed for reflections between the second and fourth (?) with random scattering of pulses decaying with the sqrt(1/d) law.
* above the fourth order a colored noise is used to generate the final tail

## Content

This repository (will) contain:

* code
* documentation
* tests

## License

GNU GPL Version 3.0
