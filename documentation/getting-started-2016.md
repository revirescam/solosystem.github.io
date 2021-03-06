---
layout: page
title: Getting Started (old version from 2016)
permalink: documentation/getting-started-2016.html
---

## Getting Started - old version from 2016

This version of the Getting Started guide is from 2016, and focusses on the Cirrus Logic Audio Card, which discontinued production in 2017.  A more up-to-date version is available [here](/basic_build.html)


### Purchase components

These are the components needed to build a Solo using the CLAC (from 2016):

* [Raspberry Pi model A+](https://www.raspberrypi.org/products/model-a-plus/) (&#8776;£15.00)
* [Cirrus Logic Audio Card](https://uk.farnell.com/wolfson-microelectronics/cirrus-logic-audio-card/cirrus-logic-audio-card-for-raspberry/dp/2448312) (&#8776;£25.44)
* [PiFace Clock Module](http://www.piface.org.uk/products/piface_clock/) buy: [Farnell](http://uk.farnell.com/piface/shim-rtc/real-time-clock-shim-for-raspberry/dp/2434226) (&#8776;£8.95)
* [Watch battery (CR1220)](https://www.google.co.uk/search?q=CR1220) Generic part, widely available. buy: [Farnell](http://uk.farnell.com/multicomp/cr1220/coin-cell-lithium-3v-38mah-cr1220/dp/2065165) (&#8776;£0.70)
* [Memory card](https://www.google.co.uk/search?q=SD+micro) - any microSD format card.  [More guidance](/documentation/memory_cards/) (&#8776;£20.00 for 64GB)
* [Primo microphone](http://www.primomic.com/products/pdf/EM172.pdf) buy: [Micbooster](http://micbooster.com/primo-microphone-capsules/65-clippy-em172-microphone.html#/matched_capsules-mono) (&#8776;£24.00)
* [USB battery bank](https://www.amazon.co.uk/s/?keywords=ec+technology+powerbank) (&#8776;£19.00) (runs for 5 days)
* [Waterproof enclosure](http://dri-box.com) I suggest version [200](http://dri-box.com/size-option/size-200) (&#8776;£8.99)
* [Little box](https://www.westonboxes.com/collections/business-card-boxes-1/products/deep-business-card-box) (&#8776;£0.89)

You'll also need a USB-ethernet adapter to set the clock (only needed
rarely, so borrow one if you can) and access to a PC/laptop with a
card reader.

### Assemble

See the accompanying [video](https://youtu.be/2Fq05JlEKjw?t=122).

1. gather all the components
1. place the tiny battery into the clock module (positive side up)
1. mount the clock module on the Raspberry Pi [(product video)](https://www.youtube.com/watch?v=mBUGtiDrHKc)
1. mount the Cirrus Logic Audio Card on the Raspberry Pi and attach the fixing screws
1. attach the microphone to the pink socket on the Cirrus Logic Audio Card
1. attach the power cord to the Raspberry Pi (do NOT attach a power supply yet)
1. protect in the little box
1. lay the little box into the DriBox waterproof enclosure


### Prepare (flash) a memory card

Insert the memory card into the card reader of your PC, and follow the
[instructions](/documentation/flashing.html) to flash the SOSI (Solo Operating System Image) onto
the card.  Once flashed, insert the memory card into the Solo's
Raspberry Pi micro SD card socket.

### Set the clock

Follow the [instructions to set the
clock](/documentation/clock.html). It should be connected to a network
and left to run for 5 minutes. This step can be skipped, but your
audio files will be wrongly time-stamped until the clock is properly
set.

### Do a test recording

To turn it on: attach the power cable to the (charged) USB battery
bank, and watch the Solo boot.  Notice the green light stabilise
(after about 50 seconds) to a "heartbeat" double-flash pattern.

Then allow it to record audio.  Sing, shout, hammer.  Leave it for at
least ten minutes to fill up one complete audio recording file.

Then turn it off: pull the power cord from the battery (at the battery
end - don't disturb the more delicate connector on the Raspberry Pi).

### Recover data from memory card

With the power disconnected, remove the memory card, and insert into
the memory card reader of your PC/laptop.  Follow the
[instructions](/documentation/harvesting.html) for copying data
onto your PC/laptop.

### Listen and analyse

Play the audio files by double clicking on them.  Analyse them with a
sound editor - try [Audacity](http://www.audacityteam.org).

### Done

If it didn't work - look at
[troubleshooting](/documentation/troubleshooting.html).
