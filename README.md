This is a an extension for Drive Badger. It provides `exclude.list` file, containing a list of exclusions compatible with popular `rsync` program.

The purpose of these exclusions is to decrease the amount of data to be exfiltrated by Drive Badger, and thus to speed up the attack,
by eliminating files and directories, that are not valuable in any way to the attacker:

- Windows system files
- Office
- common Microsoft software: Skype, Teams, OneDrive, Edge
- hardware drivers, including for peripheral devices (Creative soundcards, HP printers etc.)
- preinstalled OEM software (Acer, Dell, Fujitsu etc.)
- common software: Java, VLC, Mozilla Firefox/Thunderbird, LibreOffice
- PDF readers/writers: Adobe Reader, Foxit Reader, Foxit PhantomPDF, novaPDF, PDFCreator

### Installing

Clone this repository as `/opt/drivebadger/config/exclude-windows` directory on your Drive Badger persistent partition.

### More information

- [Drive Badger main repository](https://github.com/drivebadger/drivebadger)
- [Drive Badger wiki](https://github.com/drivebadger/drivebadger/wiki)
- [description, how configuration repositories work](https://github.com/drivebadger/drivebadger/wiki/Configuration-repositories)
