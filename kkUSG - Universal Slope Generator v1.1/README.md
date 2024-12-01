# About

A slope generator inspired by the Serge Universal Slope Generator.

When a trigger signal is given to the Trigger input this Sound acts like a sample rate envelope generator. 

Also an audio signal can be fed to the Input parameter then the Sound acts like a slew rate limiter. 

The attack and decay times can be varied at sample rate. 

The Sound also has internal feedback for the attack and decay rates which can create non-linear slopes. 

Multiple outputs can be enabled. This Sound can output up to 5 channels containing the following signals:

  channel 1 & 2: slope (always enabled)
  channel 3: End of attack trigger (optional)
  channel 4: End of decay trigger (optional)
  channel 5: Pulse wave (optional)