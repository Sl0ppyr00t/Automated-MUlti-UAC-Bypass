# Automated Multi UAC bypass 

* Automated os selector to run UAC based on OS.

# Affected OS Versions

* win 10 
* win 11 
* win server 2019
* win server 2022

# Setup 
* Make user non admin. 
* Set-ExecutionPolicy -ExecutionPolicy {Unrestricted or Bypass} -Scope CurrentUser 
* disable real time protection  

# Usage
* Download these files from either this repo directly if machine has inet capabilities. (Or downlaod these files and serve them with python :D)
* Get the files on the system with the low user access.
* cd to dir
* ./{File}.ps1 (or use the .exe)


# Change log 
v1.3.2-beta rolled out

* Make mock folder of system32 
* Copy DLL to mock folder
* Added a .exe (this is made from the UAC.ps1)
* More to come maybe, just maybe...
 
# Legal Disclaimer: 
* I am not responsible for U using it on non authorized systems, make sure u use it on systems u own or are authorized on. 

* x0xr00t 


