This is an extension for Drive Badger. It provides `exclude.list` file, containing a list of exclusions compatible with popular `rsync` program.

The purpose of these exclusions is to decrease the amount of data to be exfiltrated by Drive Badger, and thus to speed up the attack,
by eliminating files and directories, that are not valuable in any way to the attacker:

- Windows system files
- common Microsoft software: Office, OneDrive, Edge, Windows Live - except for:
   - OEM preinstalled trial versions of Microsoft Office (see https://github.com/drivebadger/exclude-oem repository)
   - instant messaging and video conferencing software (see https://github.com/drivebadger/exclude-messaging repository)

### Installing

Clone this repository as `/opt/drivebadger/config/exclude-windows` directory on your Drive Badger persistent partition.

### More information

- [Drive Badger main repository](https://github.com/drivebadger/drivebadger)
- [Drive Badger wiki](https://github.com/drivebadger/drivebadger/wiki)
- [description, how configuration repositories work](https://github.com/drivebadger/drivebadger/wiki/Configuration-repositories)
