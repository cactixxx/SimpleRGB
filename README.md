# SimpleRGB

A C++ Arduino library for controlling standard 4-pin non-addressable RGB LEDs through individual digital pins for red, green, and blue channels.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Version](https://img.shields.io/badge/version-1.0.0-green.svg)

## Table of Contents
- [Description](#description)
- [Hardware Requirements](#hardware-requirements)
- [Installation](#installation)
- [Features](#features)
- [API Reference](#api-reference)
- [Example Usage](#example-usage)
- [License](#license)
- [Version History](#version-history)
- [Contributing](#contributing)
- [Contact](#contact)

## Description
SimpleRGB provides an easy-to-use interface for controlling multiple RGB LEDs with features like solid colors, blinking patterns, and individual LED control.

## Hardware Requirements
- 4-pin RGB LED (common anode/cathode)
- Three digital output pins per LED
- Not compatible with addressable RGB LEDs (like WS2812B/NeoPixels)

## Installation
1. Download the library from GitHub
2. Extract and place in your Arduino libraries folder (`Documents/Arduino/libraries/`)
3. Restart the Arduino IDE
4. Include in your sketch:
