# About

This Sound applies a live time stretch/compress and pitch shift to its input. 

When time stretching this Sound can only time stretch for a limited duration depending on the size of the buffer and the rate of stretching. Once the amount of buffer has been exhausted the output will revert to the unstretched input with a latency delay equal to the buffer size.

When stretching is released the Sound can then time compress (if enabled) until the latency has returned to zero and the play position is at the begining of the buffer again. 

This Sound is optionally in Stereo which uses more memory and DSP resource.