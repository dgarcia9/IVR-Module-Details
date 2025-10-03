# IVR-Module-Details
Creating report on modules within Five9 IVRs

This script will download all IVRs from a domain and then scan them for the modules specified with the settings of each module.
Lines 15 and 16 will require you to update your Five9 Username and Password.
Line 41 you can set a comma separated list of which modules you want to scan for and generate a file for.

Required Libararies are:
json
xmltodict
requests
zeep
pandas
