# RB01

Easiest way to make it working? Place the web app and the python backend on the raspberry running on the Roomba.
- Add the user pi to the www-data grop
- Place the html folder under the root of a webserver (e.g. /var/www/html) and set the ownership to pi:www-data
- Set the stiky bit to the www folder, so that all new files will be created as group www-data
- Run the apache2 as the user pi, and set the listening port to 8000
- leave the python backend somewhere, and execute it as user pi. 

## License
This project is licensed under the MIT License - see the  [license file](LICENSE.md) for details

## Legal Notice
Roomba is a trademark of iRobot Corporation. All other trademarks are the property of their respective owners.

## Acknowledgments

-  Daniel Macias for the [Roomberry project](https://github.com/danimaciasperea/Roomberry)
-  Matthew Witherwax' Python iRobot [library](https://github.com/julianpistorius/irobot).
-  Picamera [package](https://github.com/waveform80/picamera).