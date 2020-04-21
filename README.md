# MicroRNG Software Kit

[MicroRNG](https://tectrolabs.com/microrng/) is a hardware (true) random number generator device that can be used in embedded systems as a reliable entropy source. It can interface with microcontrollers or microprocessors (mainboards) with integrated circuits and modules through a mikroBUS™ socket using SPI or 2-wire UART interface and can generate random numbers at a rate up to 1 Mbps in SPI mode and up to 1.5 Mbps in UART mode.

This repository contains the MicroRNG Software Kit and utilities for using the MicroRNG device with Raspberry PI 3+ or other Linux-based single-board computers via the SPI interface.

* [More about MicroRNG](https://tectrolabs.com/microrng/)

## Contents

* `MicroRngSPI.cpp` - API source code in C++ for communicating with the MicroRNG device over SPI interface.
* `mcdiag.cpp` - general purpose diagnostics utility that interacts with the MicroRNG device for determining the maximum clock speed and for validating the communication over SPI interface.
* `mcrng.cpp` - utility for downloading random bytes generated by MicroRNG device over SPI interface.
* `sample.cpp` - sample C++ program that demonstrates how to use the API for communicating with the MicroRNG device over SPI interface.

## Authors

Andrian Belinski  
