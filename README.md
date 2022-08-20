# MMM-ASL

A module to easily learn American Sign Language (ASL) by imitating short video tutorials in the mirror. Users can see how they are 'actually' doing through their reflection and the correct gestures from the video at the same time. This overcomes the current limitation of learning which is simply watching video tutorials through their phone or laptop and not being able to compare the gestures directly.

![](https://i.im.ge/2022/08/20/OIP2lx.mmm-asl-example.gif)

## Dependencies
  * An installation of [MagicMirror<sup>2</sup>](https://github.com/MichMich/MagicMirror)

## Installation
 1. Clone this repo into `~/MagicMirror/modules` directory.
 2. Configure your `~/MagicMirror/config/config.js`:

## Examples
#### Full screen
     {
         module: 'MMM-ASL',
         position: 'mididle_center',
         config: {
             // See 'Configuration options' for more information.
             type: "default",
             maxWidth: "100%",
         }
     }
#### Mini
     {
         module: 'MMM-ASL',
         position: 'top_right', // Or any valid MagicMirror position.
         config: {
             // See 'Configuration options' for more information.
             type: "mini",
             maxWidth: "20%",
         }
     }

## Configuration Options

| **Option**         | **Default**    | **Description**                                      |
| ------------------ | -------------- | ---------------------------------------------------- |
| `type`             | `default `     | Full screen version: `default`, Mini version: `mini` |
| `maxWidth`         | `100%`         | Width of the sign language gifs                      |
