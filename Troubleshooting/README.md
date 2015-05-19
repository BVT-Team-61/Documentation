# Troubleshooting

## Errors when configuring environment
* Use any windows OS 7 or later (XP is not compatible).
* Use anything, but chrome to access RoboRio (Chrome has removed the required Silverlight plugin).
* Check for firmware updates before ever competition.
* Be familiar with the WPI, FIRST, and NI website for updates and help.

## Errors when writing program
* Refer to Chief Delphi or Javadoc.
* Have backups for your backups (GitHub is nice, but label known working code).
* Have a second person sanity check your code.
* Write code incrementally, starting with the basics, then add new features.

## Errors when uploading program
* Read the error messages. If you don't know what they mean, copy and paste the message into Google.
* Double check router settings.

| Device         | IP Address     | Subnet Mask     |
| :------------- | :------------- | :-------------- |
| Router         | 10.0.61.1      | 255.255.255.0   |
| RoboRio        | roborio.local (10.0.61.2)        |
| Other Devices  | 10.0.61.10-255 (DHCP)            |
* When in doubt reboot RoboRio.

## Errors when running program
* Try previously tested, working code.
* Double check all code (even the 'known working' parts).
* Was there a recent hardware change?
* When in doubt reboot RoboRio.
* Run untested code at slower than normal speed to prevent 'toaster' (erratic, damaging behaviour).
