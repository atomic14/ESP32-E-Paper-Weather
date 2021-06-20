# Intro

I've been playing around with one of these ePaper displays. I've got the LILYGO 2.7" E-Paper Plus Module. The classic thing that people seem to do is get a weather display up and running - so I thought I would do the same.

[![Demo Video](https://img.youtube.com/vi/VnhYpI8I-oE/0.jpg)](https://www.youtube.com/watch?v=VnhYpI8I-oE)

There's a really nice library by G6EJD that everyone seems to be using. This already has support for a whole bunch of ePaper displays including the Waveshare 2.7 inch display which is the one that is used on the LILYGO board I have.

https://github.com/G6EJD/ESP32-e-Paper-Weather-Display

Most of the instructions are around using the Arduino IDE but I much prefer PlatformIO so this repo gets it all working there.

You can order the module I'm using here: https://s.click.aliexpress.com/e/\_AZRYxj

# Getting started

You'll need to modify the settings in `own_credentials.h`. Add your WiFi details, get an API key from https://openweathermap.org/. And update your home city and timezone.
