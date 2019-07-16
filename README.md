# octoprint-psucontrol-fhem-script
script to control a fhem smart plug by psucontrol plugin


Download this file and place it where you want.
Expample path: /home/pi

Install psucontrol plugin in octoprint.

Change to settings in octoprint. Select the plugin psucontrol
Switch "Switching Method" to "System Command"
Puth the following path in:
    On System Command: /home/pi/fhem-switch-status on
    Off System Command /home/pi/fhem-switch-status off
Switch "Sensing Method" to "System Command"
Puth the following path in:
   Sensing System Command: /home/pi/fhem-switch-status sense
   
   
Cheers Robert
