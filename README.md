# TSN4ALL
A TSN (time sensitive networking) configuration tool to manage different ethernet devices in a local network.

Test the actual editor on https://www.bichler.tech/download/tsn4all/

  ## Editor elements:
  The editor should constist of a menu bar, left or right to the main editor. The menu should contain all installes eth-devices.
  The main editor has one region for graphical/logical network diagram.
  
  How to add an menu device?
  Each device must provide the following infos to install it to menu bar:
  * name
  * description
  * version
  * revision
  * builddate
  * image (png, jpg)
  * portcount in first step, should be replaced by yang model
  * speed of each port in first step, should replaced by yang model
  * (yang interfaces definition) second step
