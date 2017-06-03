# win_enum_local
## Local Windows Enumeration for Privilege Escalation

This is a python script that enumerates Windows computer for privilege escalation vulnerabilities. It is designed to be quick and robust to accommodate Windows versions from XP to 10. The use of WMIC was avoided for XP compatibility. 

**accesschk.exe from MS SysInternals is required to be in the same root folder as this script.**

You can get accesschk from this link: https://technet.microsoft.com/en-us/sysinternals/accesschk.aspx

This script has come in handy while working through the Offensive Security Penetration Testing with Kali Labs.

You can compile the script to an executable using PyInstaller for easy use on any Windows machine.

Download pyinstaller from here: http://www.pyinstaller.org/

This is an open project and I welcome input and pull requests from anyone who wishes to contribute.

## Notes
When the script is running some of the PE checks may throw errors if the registry keys the script is looking for are not present or if the system does not support the specific check being used.

An example is when the script is looking for the "AlwaysInstallElevated" registry key and it is not present you will see the following error:

`ERROR: The system was unable to find the specified registry key or value.`

This is nothing wrong with the script.

## Based on examples from the following resources:

http://www.fuzzysecurity.com/tutorials/16.html

http://toshellandback.com/2015/11/24/ms-priv-esc/
