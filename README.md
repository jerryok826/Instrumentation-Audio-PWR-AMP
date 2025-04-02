# Instrumentation-Audio-PWR-AMP

![Robot_Front](https://github.com/jerryok826/Instrumentation-Audio-PWR-AMP/blob/main/Pictures/audio_pwr_amp_r4.jpeg)

## Project Description
I needed a audio amp I could use to test speakers and haptics. Most audio amps today seem to be class D using some form of PWM output drive. These cannot be easily be tested with a scope. So I started looking for a linear class AB audio amp. The old LM1875 meets these requirements. The other specs I was looking for were running from 12 volts. Also DC direct speaker dirve so the amp's low frequency performance was the very best.  Also I wanted a calibrated gain. With the audio attenuation pot set to 100% the input to out gain is 20. The design uses a on board 12 volt to -12v converter to generated the required negative supply voltage for the LM1875. The DC offset at the speaker terminals is typically about 1 millvolt. I call this board a "Instrumentation Audio PWR AMP" because it has known characteristicss for testing speakers and haptics. ALso the polarity of the output can be changed via a jump. Also there is a small VU meter to monitor the speaker driver level. This is mostly for debugging the a haptics test setup.

The unit should put out about 10 watts into a 4 ohm speaker. The spec sheet for the LM1875 is in the Docs directory. 

### Project Status
The project is basically complete.

## Design Files
This project was designed with Kicad 7.X
