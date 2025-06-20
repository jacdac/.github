## Welcome to Jacdac!

Jacdac is an open-source software and hardware platform that brings a plug-and-play experience to the world of micro-controllers, starting with [the BBC micro:bit](https://microbit.org).

## Getting started

Get started at the [Jacdac home page](https://jacdac.github.io/jacdac-docs). Click on the hamburger
menu (upper left) to get an overview.

## Issues and Discussions

Please refer to the following for Jacdac issues and discussions 
- https://github.com/jacdac/jacdac/issues
- https://github.com/jacdac/jacdac/discussions

## For developers

### Jacdac device and service catalogs

The Jacdac [device](https://jacdac.github.io/jacdac-docs/devices/) and [service]((https://jacdac.github.io/jacdac-docs/services/) )
catalogs are the foundation of the Jacdac stack: 
- [jacdac/jacdac](https://github.com/jacdac/jacdac): this repo contains the source of the catalogs, from which a variety
of other artifacts are generated, including the above pages 

### Jacdac web stack

Jacdac bridges the world of the web browser and hardware via
the Jacdac bus, which you can experience via the [Jacdac dashboard](https://jacdac.github.io/jacdac-docs/dashboard). 
Device twins show the state of the connected
hardware; device simulators allow virtual devices to be added
to the bus.  

The following repos define the web stack
- [jacdac/jacdac-docs](https://github.com/jacdac/jacdac-docs): Jacdac home page and web-based tools, built on
- [jacdac/jacdac-ts](https://github.com/jacdac/jacdac-ts): dependency-free Jacdac Object Model ([JDOM docs](https://jacdac.github.io/jacdac-ts/))
- [jacdac/react-jacdac](https://github.com/jacdac/react-jacdac): React hooks for Jacdac ([docs](https://jacdac.github.io/react-jacdac/))
- [jacdac/gatsby-remark-makecode](https://github.com/jacdac/gatsby-remark-makecode): renders MakeCode code snippets into images.

### Jacdac CLI

- [jacdac/jacdac-cli](https://github.com/jacdac/jacdac-cli): command-line interface (NPM)

### Jacdac firmware

Jacdac firmware is organized into several repos:
- [jacdac/jacdac-c](https://github.com/jacdac/jacdac-c): MCU-independent implementation of Jacdac protocol and device drivers
- [jacdac/jacdac-stm32x0](https://github.com/jacdac/jacdac-stm32x0): Jacdac host for STM32 MCUs
- [jacdac/jacdac-module-template](https://github.com/jacdac/jacdac-module-template): building firmware for a Jacdac module

### MakeCode Client

- [jacdac/pxt-jacdac](https://github.com/jacdac/pxt-jacdac): MakeCode extension for Jacdac, including simulator support for device twins and simulators (via web stack)

## For hardware designers

- [jacdac/jacdac-ddk](https://github.com/jacdac/jacdac-ddk): 