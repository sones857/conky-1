# conky-1
conky config 
basic conky config code to read disc space, uptime, network connection, quailty.

save as .conkyrc file 

If delay script is needed, save the following to a file, add to startup and enable run as programme in permissions.

#!/bin/bash
#Conky start-up delay script

bash -c "sleep 8; conky"

