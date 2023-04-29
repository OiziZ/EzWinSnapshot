# EzWinSnapshot

This script written in Powershell makes it possible to have a very simple and effective Snapshot system.

By using the RoboCopy command, if the original folder was not changed, no snapshot will be created.
It's makes it possible to avoid polluting the bandwidth of the disk(s) for nothing.

This script has been tested on the following Windows versions:
- Windows 10 Pro x64
- Windows 11 Pro x64
- Windows Server 2022
- Windows Server 2019

**Currently the script is not able to handle the case of a lack of disk space in the destination folder, beware of your storage space!**

**Don't forget to put a star if this script helped you!**

# Features
You can modify:
- Snapshot interval (Time to be specified in minutes!)
- The maximum number of snapshots
- The source folder
- The snapshot destination folder

# What I would like to add
- Sends an email to each Snapshot created (Admin can choose if the feature is enabled or not)
- Give the possibility to make as many snapshots as possible by not exceeding a certain percentage of use of the destination disk
- A log system (Which can be emailed)
- A prettier runtime window ^^'
