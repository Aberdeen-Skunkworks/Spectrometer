# Spectrometer
Construction notes and design files for a spectrometer.

The ultimate aim is to build a Raman spectrometer to measure the "fingerprint" of molecules which works by shining a specific frequency laser on a material and looking at the emitted (not reflected or transmitted) light.

This allows exact identification and measurement of the quantity of compounds in liquids and solids. It may be combined with the acoustic levitating platform to allow very clean spectra of liquids and solids to be measured without a container getting in the way and interfering the signal.

# Resources

https://publiclab.org/notes/emontoya57/12-16-2015/a-homemade-cost-effective-raman-spectrometer-with-high-performance
https://hackaday.io/project/19579-the-otter-diy-raman-spectrometer
https://erossel.wordpress.com/ This guy's notes on the linear CCD


# Parts Needed
- 532nm laser. This is a cheap green laser, good as it avoids flouresence for lower wavelengths (e.g. violet).
- a 532nm band pass filter to clean up the laser. Maybe there's dirt or something in the laser which causes it to emit at other frequencies.  https://www.newport.com/f/laser-line-filters £100?
- TCD1304 linear CCD. This should be easier to control than a standard camera plus we can cool it for longer exposure times. https://tcd1304.wordpress.com/tcd1304-pcb/ has a driver board we can buy at dirty PCBs from Erossel. £25 total?
- Peltier cooling element for the CCD. Erossel https://www.amazon.co.uk/TEC1-03510-Heatsink-Thermoelectric-Cooling-Module/dp/B01EZQKA5Y
- An optical grating.
- Mirrors.
- Safety glasses at the laser frequency
- Access to a laser lab with safety lockouts to prevent errant beams.
