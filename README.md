EggBotDuino
==========

This is my personal project containing all I need to run my home amde EggBot.
The firmware is based on https://github.com/russhughes/EggDuino
The Inkscape driver is base on https://github.com/evil-mad/EggBot by Evil Mad Scientist Laboratories.

The software was almost working for me, I needed to make some changes and keep trac of them.

My changes on firmware:
- I'm using a 28BYJ-48 stepper motor and I needed to change some few settinngs about it
- I changed the pin configuration

My changes to inkscape driver:
- I remove search of the serial port. Instead is part of the configuration. In this way any serial device or any OS (I'm using linux) can be used.
