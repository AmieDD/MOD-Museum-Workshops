# Open Source Cosplay Project with AmieDD and Hybrid World Adelaide and MOD Museum 
Details for AmieDD workshops at Hybrid World and MOD Museum. at the [University of Southern Australia](https://mod.org.au/) is a futuristic museum of discovery, a place to be and be inspired.

## Ingredients List
* Download [Arduino IDE](https://www.arduino.cc/en/Main/Software) - The open-source Arduino Software (IDE) makes it easy to write code and upload it to the board. It runs on Windows, Mac OS X, and Linux. The environment is written in Java and based on Processing and other open-source software. Amie's In-game Hint: Download the version from the Arduino webpage, the version from the Windows app store has issues with the drivers sometimes.

## Contributors:
* [Amie Dansby](https://www.amiedd.com)
* [Flexo](https://www.flexo.nz/) 
* [Andrew Sowa](http://www.andrewsowa.com/) - Custom Rocket PCB Learn to Solder Badge for Workshop 1
* [OSH Park](https://oshpark.com/shared_projects/u10ZmdAJ)
* [Midnight Giant](https://www.thingiverse.com/search?q=Midnight_giant&dwh=605b305acb373bf)
* [Srgnt Ballistic](https://twitter.com/SrgntBallistic) 
* [JD](https://twitter.com/warmasterdook)
* [MOD.](https://mod.org.au/)

#### [Workshop 1 - Learn To Solder Things!](https://github.com/AmieDD/MOD-Museum-Workshops/tree/master/Workshop%201)
  *

#### [Workshop 3 Making Space Junk Props](https://github.com/AmieDD/MOD-Museum-Workshops/tree/master/Workshop%203)
 *

#### [Workshop 4 "Let's Make Things Spin!" Robot Space Sidekick](https://github.com/AmieDD/MOD-Museum-Workshops/tree/master/Workshop%204)
  *

#### [Workshop 5 Resin Casting Props and LEDs](https://github.com/AmieDD/MOD-Museum-Workshops/tree/master/Workshop%205)
  *

#### [Workshop 6 Props, Swords, and Magic!](https://github.com/AmieDD/MOD-Museum-Workshops/tree/master/Workshop%206)
  *


###Troubleshooting

Arduino sketches:

Pins #2 and #7 are not available (they are exclusively for USB)
The onboard 5V regulator can provide 150mA output, not 800mA out
You cannot plug shields directly into the Pro Trinket
There is no Serial-to-USB chip onboard. This is to keep the Pro Trinket small and inexpensive, you can use any FTDI cable to connect to the FTDI port for a Serial connection. The USB connection is for uploading new code only.
The bootloader on the Pro Trinket use 4KB of FLASH so the maximum sketch size is 28,672 bytes. The bootloader does not affect RAM usage.
