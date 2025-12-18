# PilbertTransform

The PilbertTransform, AKA "Pete's Poor Man's Hilbert", is a less expensive Hilbert approximation using custom allpass filters.  This implementation has the benefit of zero latency.  The two outputs are 90 degrees out of phase with each other but neither have a recognizable phase relationship to the input.  Care must but used when used with bypass path or dry signal mix.

Suitable for input signals in the audio range.  It should not be used with sub-audio signals.  

Hilbert Transforms have many uses including, but limited to:
	- Single Side Band Modulation / Frequency Shifter.
	- Magnitude and envelope following.  
	- Location mapping of sound sources. 
	- Phase estimation from magnitude alone.
	- Latency detection and velocity measurment.
	- Measurement of seimic and gravitional waves.
	- Calculating entrophy in the brain for seizure detection.


Example sound developed by the Kata community leveraging the Pilbert / Hilbert:
	- Frequency Shifter with cancellation of reversed/reflected/negative frequencies. 
	- Imagination Machine, a frequency shifter with feedback 
	- Phase Displacement Unit, a amplitude independent distortion
	- PhaseSpinner, a quirky subharmonic generator 

