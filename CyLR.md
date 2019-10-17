# CyLR

CyLR is a live response collection tool that can be used on OS platforms windows, linux, and mac. 

[Official Website](https://github.com/orlikoski/CyLR)

# Sample Output 
CyLR.exe --help
CyLR Version 2.1.0.0

Usage: CyLR [Options]... [Files]...

The CyLR tool collects forensic artifacts from hosts with NTFS file systems quickly, securely and minimizes impact to the host.

The avalable options are:
-od
        Defines the directory that the zip archive will be created in. Defaults to current working directory.
Usage: -od <directory path>

-of
        Defines the name of the zip archive will be created. Defaults to host machine's name.
Usage: -of <archive name>

-c
        Optional argument to provide custom list of artifact files and directories (one entry per line).
NOTE: Must use full path including drive letter on each line.  MFT can be collected by "C:$MFT" or "D:$MFT" and so on.
Usage: -c <path to config file>

-u
        SFTP username

-p
        SFTP password

-s
        SFTP Server resolvable hostname or IP address and port. If no port is given then 22 is used by default.  Format is <server name>:<port>
 Usage: -s 8.8.8.8:22

--dry-run
        Collect artifacts to a virtual zip archive, but does not send or write to disk.

--force-native
        Uses the native file system instead of a raw NTFS read. Unix-like environments always use this option.

-zp
        Uses a password to encrypt the archive file

--no-usnjrnl
        Skips collecting $UsnJrnl
