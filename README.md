# Pterodactyl-Egg-Wreckfest
Wreckfest Egg for Pterodactyl Panel version 1.11 or newer.


## Wreckfest Requires 3 Ports to be configured.
| Port    | Default       |
|---------|---------------|
| Game    | 33540         |
| Query   | 27015         |
| Steam   | 27025         |
 
 
## Known Issues:
* ``[WARNING]: IsSubsystemNative, not defined subsystem, fallback to wrapper 'User|NetworkingSockets|Utils|NetworkingUtils'``,
  * You can safely ignore this as it should still function.
* Server does not appear on the steam page. 
  * This is fine. It is an issue with Wreckfest in general that THQ needs to fix.
* ``_XSERVTransmkdir: ERROR: euid != 0,directory /tmp/.X11-unix will not be created.``
  * This will occur with wine. No way to fix this with Dedicated Servers that does not have a graphics driver installed. Should work as is.
* I can't use console to execute commands.
  * I am unsure how to make this work since it goes through wine, which basically allows running windows commands, so nothing I can do about it. If someone knows how to fix it, fork the repository.
