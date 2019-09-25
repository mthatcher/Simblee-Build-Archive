# Simblee-Build-Archive
This archive allows you to add Simblee boards to the Arduino IDE.

This archive gives you access to the files necessary to compile and upload sketches to your Simblee boards. 
Since RF Digital abandoned its users, setting up a new Arduino environment capable of programming the boards has become quite a challenge.
Thankfully the good people at OpenBCI did all the hard work and created a path forward. I've simply taken what they did, 
and put it on Github. 

To use this find the Additional Boards Manager URLS listed in the Arduino IDE preferences (File > Preferences) and, if it's listed, delete

https://www.simblee.com/package_simblee166_index.json

Then add

https://github.com/mthatcher/Simblee-Build-Archive/raw/master/package_simblee166_index.json
