Yet-Another-Secure-CoPy (Copy over proxy)
=========================================
  Single command for copying files or folders over middle computer.

##Traditional Way: (Source:C Destination:A)##

* SSH to B
* Copy files from C to B
* Copy files from B to A

##Target:##
  Get files from C to A via B

    yascp [-r] -s C -d A -proxy B
