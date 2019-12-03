This Script checks the Network Connection if the Interface is up and a specified IP can be pinged
A lockfile prevents the script from running multiple times.  
Output Messages will be written to /var/log/connection_monitoring.log. 
The Logfile will be automatically overwritten on the next run

Project:        connection_monitoring

Author:         Florian Weiner (sun35friend@gmail.com)

Copyright:      Copyright (c) 2019 Florian Weiner
Git Repo:       https://github.com/sun30friend/connection_monitoring

Installation:

- sudo mkdir -p /scripts
- cd /scripts
- sudo git clone https://github.com/sun30friend/connection_monitoring.git
- sudo sh ./scripts/connection_monitoring/install.sh
