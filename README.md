# Intelligent-Hearing-Aid-Device
Made with Arduino, built BJT amplifier and filter circuits

The goal is to build a low power, cost-effective hearing aid that has several key intelligent features. First, it has tuning functionality that allows the wearer to tune the amplification to his or her needs. It has a conversational mode which recognizes voice input and amplifies it while reducing background noise. It saves all data to memory so that the device can be quickly powered up and ready to use. 

A signal picked up by the microphone first goes through a pre-amp stage which culls frequencies above 3kHz (outside hearing spectrum) and then amplifies the remaining signal for future stages. The signal then progresses to the filter stage where it goes through four parallel filters that divide the signal into four frequency ranges. This filtered signal is read by the level estimator and provided to the Arduino. The filtered signal is also passed to the gain-controlled stage where the signals are amplified based on tuning settings provided by the Arduino. The signal finally enters the output stage where it passes through a summer and the modified signal can be heard with a pair of earphones.

![frau2gkhoufwv06 large](https://user-images.githubusercontent.com/24973005/36634507-71e067ca-195a-11e8-9e32-5591055db41f.jpg)
