Blockinger 3
============

Free classic Tetris® clone for Android.

This is a fork of [Blockinger2 by Tasio Leiva](https://github.com/yanshoutong/Blockinger2), which is a fork of [Blockinger by Simon Willeke](https://github.com/vocollapse/Blockinger).

## Networking
New in this fork: Networking!

Blockinger3 players on the same WiFi network will automatically send their highscore list to you and vice versa, so you can compete against friends, like on a real arcade machine! This happens every two minutes.

## Scoring

Basic points per cleared line are:

- 100 points for 1 line
- 300 points for 2 lines
- 500 points for 3 lines
- 800 points for 4 lines (called "Tetris")

Scoring consecutive Tetrises provides 400 bonus points per Tetris.

Additionally the player receives a bonus score for using Soft and Hard Drops. Soft Drops award 1 point per dropped line, while Hard Drops award 2 points per dropped line.

## Levels

Levels are a measurement of difficulty.

The speed at which pieces automatically drop down increases by 10% per level.

The current level increases after clearing 10 additional lines.

## Vibration

There are some problems with the vibration functionality that can occur on a few devices.

Also most tablet devices don't support Vibration at all.

If your device does support vibration but you don't notice the button vibrations, you can increase the vibration duration.

This setting is called "Vibration Delay Compensation" and can be found under advanced settings.

The duration of button vibrations should be adjusted to be just barely noticeable.

## APM

APM means "Actions Per Minute".

This is a measurement of the player's finger speed.

## FPS

FPS means "Frames Per Second".

This measures the frequency of display updates. Low FPS can be notices by slow reactions from the game and choppy displaying.

High FPS on the other hand consume more power. A good trade-off between display smoothness and power consumption can be achieved between 25 and 35 FPS.

FPS can be limited in advanced settings.

## Randomizer

### 7-Bag-Randomization:

Generates randomly permutated sequences of all 7 pieces. This means, that the player can never encounter 3 identical pieces in a row.

### Plain Random:

The next piece will be independently generated at random.

## Resumability

An interrupted game is resumable as long as the "Exit" menu entry from the main menu was not pressed.

## Building
To build this app, you need Android Studio and cap'n proto and its Java plugin. In the Arch Linux package repository, they are packaged as `capnproto` and `capnproto-java`.

## Licenses

### Blockinger

- GNU GENERAL PUBLIC LICENSE Version 3
- Copyright 2013 - 2018 Simon Willeke <hamstercount@hotmail.com>
- Copyright 2018 Tasio Leiva <contact@tasioleiva.com>

### Music
- Author: [Pornophonique](http://www.pornophonique.de/).
- License: Creative Commons BY-NC-SA 3.0 DE

### Artwork and Sound Effects
- License: GNU GENERAL PUBLIC LICENSE Version 3
