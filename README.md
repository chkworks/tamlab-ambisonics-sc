# tamlab-ambisonics-sc

Some examples how to connect with the ambisonic speaker system (OTTOsonics) at the Tangible Music Lab in Linz.

## 1. Driver installation

The system is using the AVB protocol via two Motu interfaces.<br />
Install the driver here: https://motu.com/de/download/ (select interfaces, then the "24Ao" entry and chose your operating system.

## 2. Check Motu AVB settings (Mac OS)

Connect with the Interface via USB and open the Motu Discovery app. An interface called "Interface" should appear.
TODO: Describe necessary settings in the configuration interface

## 3. Run the code from Supercollider
First you need to install the Ambisonic Toolkit for Supercollider. Installing the ATK requires Git to be installed on your computer. 

https://github.com/ambisonictoolkit/atk-sc3/blob/master/README.md#installing

Then open the Supercollider code in the reposity and play!

### Other useful ressources
- https://youtu.be/VvI56TnY8tA (Eli Fieldsteel lecture on the topic)
- https://www.alterbauhof.at/ottosonics/ (OTTOsonics system website)
- https://en.wikipedia.org/wiki/Audio_Video_Bridging (AVB protocol)
- https://www.ambisonictoolkit.net/ (ATK website)
- https://github.com/ambisonictoolkit/atk-sc3 (ATK Supercollider Repository)
