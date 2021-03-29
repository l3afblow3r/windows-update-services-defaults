# Windows Update Services Defaults
Registry Backup of Update Services for Windows 10

# Q: Where did you find this?
This can be found within the Windows Installation Media ISO Image.  

Open it and navigate to __sources/install.esd__ (**or install.wim**)  
and then open it using 7-Zip and navigate to __1/Windows/System32/config__  
and copy the __SYSTEM__ file to your desktop.

Load the hive in Registry Editor and export the __ControlSet001/Services__ key  
to a file. (This will export all services)

You can isolate certain services or keep all of them.  

Done.
