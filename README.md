# Synrad-Laser-Data
This repository contains a description of the internal laser data variables which can be pulled from the Synrad i401 Firestar laser.
These values can be accessed by sending an HTTP Post request to 192.168.50.50/cmd/getalldata and */cmd/getservicedata
There are a few bits of missing info, such as constants used to convert voltage levels to real-world values. These will be filled in as needed and should be easily found by reading through */js/main_noimage/js and */js/service.js
