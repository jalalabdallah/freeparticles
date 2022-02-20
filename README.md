 Jalal Abdallah (Physicist)
 Hello Quantum World !
I am Physicist, Particles and Quantum Cosmology
[Jalal 1](https://user-images.githubusercontent.com/96692907/154752156-30a23210-f52e-4379-96d7-e9a3454debad.JPG)
.And i want to be Web developer!
![Jalal 13](https://user-images.githubusercontent.com/96692907/154764522-28e7dd3d-4216-4dff-a16f-2c7dc2904aa0.JPG)

import React from 'react';
import YouTube from 'react-youtube';

class Example extends React.Component {
  render() {
    const opts = {
      height: '390',
      width: '640',
      playerVars: {
        // https://developers.google.com/youtube/player_parameters
        autoplay: 1,
      },
    };

    return <YouTube videoId="2g811Eo7K8U" opts={opts} onReady={this._onReady} />;
  }

  _onReady(event) {
    // access to player in all event handlers via event.target
    event.target.pauseVideo();
  }
}
