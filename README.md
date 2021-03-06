# microSimulink Library #

## Goals ##

This library aims to provide a rich set of blocks useful for developing realtime code on a microcontroller using Simulink and the RTCoder/RTWorkshop packages. This library is built from code reused during experiments with autonomous vehicles and so is most useful for those applications. As this library expands I aim to extend it to become more relevant for any application of a microcontroller.

## Requirements ##

This blockset relies on nothing besides Simulink to be used. All blocks have been designed to be compileable for microcontroller architectures, but should work fine in standard Simulink projects.

## Installation ##

All that's required is that you keep this library in its own directory and add that directory to the matlab path. The install.m file has been included in the directory to do just that. Simply run it and you're off!