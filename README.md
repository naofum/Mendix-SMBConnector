# Mendix-SMBConnector

The **SMB connector** can be used to read and write SMB (Windows shared) files.


## Dependencies
* none


## Installation
* Import the module **SMB connector** in your project (from the Mendix AppStore or by downloading and exporting the module from this project)

* You can use Java action (readFile/saveFile) to read and write SMB files with on-premise environment.


## Configuration options
- enable SMB 1.0 feature in Turn Windows features on or off settings.
- specify smbpath like smb://hostname/folder/filename.ext


## License
- This module Licensed under the GPL v3+ (see. https://www.gnu.org/licenses/gpl-3.0.en.html)
- This module contains jCIFS library which is Licensed under the LGPL v2.1 (see. https://www.gnu.org/licenses/lgpl-2.1.en.html)


## Version history
- 2.0.0 Converted to Mx 8.0.0
- 1.0.1 fixed example
- 1.0.0 first release beta for public
- 0.1.0 first functions for SMB Connector implemented
