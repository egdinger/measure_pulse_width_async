measure_pulse_width_async
=========================

Sample code to measure the pulse width of a signal asynchronously using interupts and timers.

This code is from another project I worked on (https://github.com/PSU-AVT). It 
is meant for an lpc1343 chip compiled using codered and the microbuilder.eu 
code.

It was originally designed to measure a pulse width from a Maxbotixs MB1040
ultrasonic rangefinder and convert that pulse width into a distance.

If you don't have those don't worry it should be fairly easy to modify to any 
microcontroller. Setting up the timers, the pin configuation for interupt, and 
the name of the interupt will be specific to the micro controller you're using.
The main logic in measure_maxbotix_in and the interupt handler will not change.