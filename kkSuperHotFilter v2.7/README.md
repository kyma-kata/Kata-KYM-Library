# About

This is a sample-rate controllable, stereo state variable filter with three-times oversampling! It simultaneously creates the four types of filter which can be mixed into the output:

* low pass
* high pass
* band pass
* band reject

You can select the output level of each filter type. If you want just a low pass filter, set the LowPassLevel to 1 and the other filter types to 0. 

The Wavetable parameter specifies a waveshaping function that can be used in the feedback path of the filter. The amount of waveshaping is set by the WaveshapeAmount parameter. 

The filter Frequency, Bandwidth and filter type levels can all be set at sample rates, as well as the amount of waveshaping in the feedback path. 

If a Sound is used to set the Frequency or Bandwidth then it is possible to set them differently for the left and right channels. If you want to control these parameters in stereo using !EventValues you could put left and right !EventValues in two Constant Sounds feeding in to the left and right sides of a ChannelJoin and paste that into the parameter. 