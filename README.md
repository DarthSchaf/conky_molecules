# conky_molecules
Conky molecules themes based on the great LSD conky config by charley166  
http://charley166.deviantart.com/art/LSD-conky-config-v2-0-392188352  
  
# Installation
Install dependencies:  
sudo apt-get install lm-sensors hddtemp conky-all  
  
Change permissions:  
sudo chmod u+s /usr/sbin/hddtemp  
  
Download zip  
Unzip:  
unzip <package>  
  
Create fonts dir:  
mkdir ~/.fonts  
  
Copy fonts:  
cp /conky_molecules/zekton/* ~/.fonts  
  
Create conky dir  
mkdir ~/.conky  
  
Move dir:  
mv conky_molecules ~/.conky/conky_molecules  
  
Start up:  
change into directory  
conky -c conkyrc &  
