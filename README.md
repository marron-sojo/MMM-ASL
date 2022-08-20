# MMM-ASL
Display internet connection status for MagicMirror<sup>2</sup>

We built a module, which users can learn American Sign Language with gifs on the magic mirror and practice words while looking in the mirror.
While coming up with an idea for a module that can well utilize a mirroring functionality, we thought it would be nice to do exercise, meditation, or learn sign language while looking at oneself in the mirror  and watching a video at the same time.
Randomly show sign language gifs

based on MMM-EyeCandy

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
