# Simple_Emon_Library
My need and purpose for this Library,
I need a simple code for computing AC Volts and Current with my Arduino Leonardo
I have about 30 outdoor condenser units and heat pumps.
I want to monitor the ac Current for the Compressor, Fan Motor, and Defrost heater.
I will also monitor the inside temperature of the Freezers.
As I monitor the tempuratures, volts, and currents, I can tell I a fan has gone bad,
or a defrost has stopped working, and hopefully tell if they are going to fail soon
as their current will rise before they die.

I am in North Carolina USA, so I have 3-phase power, but I only want to monitor
the two legs that are at 120 volts.  The only things that use the high 208 Volt
leg are the compressor motors and it is rare when they fail.

I am hoping to use multiple Arduino Leonardos to monitor the condensing unit.
Then I can query them and read the values into some sort of code to monitor.
