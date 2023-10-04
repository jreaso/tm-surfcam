# Time Machine Surf Cam

This builds on the dataset created with [surf-forecast-videos](https://github.com/jreaso/surf-forecast-videos). This project is not complete and is currently using a nearest neighbour approach with the assumption that key features of a surf report are (_equally_) important. Forecasts are clustered by their similarities on these key features so that forecast footage can be shown.

Note that this is built on top of the 04/10/23 version of the dataset which contains approximately a month worth of observations and is by no means large enough to provide desirable result.

Improvements could be to label the videos either by attaching tags (_e.g. flat, messy, clean, shoulder high, ..._) or by ranking how similar a subset of pairs are. These would both result in a better idea about which features are more influential on the surf.
