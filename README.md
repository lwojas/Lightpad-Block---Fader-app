# Lightpad Block - Fader app
This littlefoot script turns the Roli Lightpad Block into a bank of 16 faders to control midi CC values.

## Libraries

Littlefoot - This is essentially like C but with a few restrictions and some built-in functions exlcusive to the lightpad hardware, see [here](https://weareroli.github.io/BLOCKS-SDK/the_littlefoot_language.html#littlefoot_description) for more info. 

## Setup

See [here](https://weareroli.github.io/BLOCKS-SDK/getting_started_with_blocks_code.html) to download the Blocks code IDE. Alternatively you can sideload the littlefoot script using the Roli dashboard app.

## Features
- Fader mode: 16 touch faders assigned to Midi channels 1 - 16 (perfect for mixing things like Korg gadget)
- Midi CC display mode: shows what CC is being manipulated and the value in real time

## Issues
The latest firmware for the Lightpad block seems to disable reading of the Midi clock byte, if midi clock does not seem to work when you run the app this could be the cause. It is possible to downgrade the firmware and restore this functionality, however it is not the scope of this app readme to detail this.

## To do
- Fix metadata variables to be easier to configure from the dashboard

## Contact
lechwojas@gmail.com
