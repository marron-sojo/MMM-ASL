# MMM-ASL

A module to easily learn American Sign Language (ASL) by imitating short video tutorials in the mirror. Users can see how they are 'actually' doing through their reflection and the correct gestures from the video at the same time. This overcomes the current limitation of learning which is simply watching video tutorials through their phone or laptop and not being able to compare the gestures directly.

## Dependencies
  * An installation of [MagicMirror<sup>2</sup>](https://github.com/MichMich/MagicMirror)

## Installation
 1. Clone this repo into `~/MagicMirror/modules` directory.
 2. Configure your `~/MagicMirror/config/config.js`:
 
     ```
     {
         module: 'MMM-connection-status',
         header: "Internet Connection",
         position: 'top_left', // Or any valid MagicMirror position.
         config: {
             // See 'Configuration options' for more information.
         }
     }
     ```

## Configuration Options

| **Option**         | **Default** | **Description**                     |
| ------------------ | ----------- | ----------------------------------- |
| `updateInterval`   | `60000`     | Time in ms to wait between updating |
| `initialLoadDelay` | `0`         | Time in ms to wait until start      |
| `animationSpeed`   | `250`       | Fade animation time                 |
