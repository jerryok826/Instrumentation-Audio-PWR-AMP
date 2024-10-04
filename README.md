# Instrumentation-Audio-PWR-AMP

![Robot_Front](https://github.com/jerryok826/Instrumentation-Audio-PWR-AMP/blob/main/Pictures/audio_pwr_amp_r3.jpeg)

## Project Description
I needed a audio amp I could use to test speakers and haptics. Most audio amps today seem to be class D using some form PWM output drive. These cannot be easily be tested with a scope. So I started looking for a linear class AB audio amp. The old LM1875 meet these requirements. The other specs I was looking for were running from only 12 volts. Also DC direct dirve of the speakers so the amps low frequency performance was the very best.  Also I wanted a calibrated gain. With the audio attenuation pot set to 100% the input to out gain is 10. The design uses a on board 12 volt to -12v converted to generated the required negative supply voltage for the LM1875. The DC offset at the speaker drive is about 1 millvolt. I call this board a "Instrumentation Audio PWR AMP" because it has known characteristicss for testing speakers and haptics.

The unit should put out about 10 watts into a 4 ohm speaker. The spec sheet for the LM1875 is in the Docs directory. 

### Project Status
The project is basically complete.

## Design Files
This project was designed with Kicad 7.X
