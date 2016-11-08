# win_enum_local
## Local Windows Enumeration for Privilege Escalation

This is a python script that enumerates Windows computer for privilege escalation vulnerabilities. It is designed to be quick and robust to acomidate Windows versions from XP to 10. The use of WMIC was avoided for XP compatibility. 

**accesschk.exe from MS SysInternals is required to be in the same root folder as this script.**

You can get accesschk from this link: https://technet.microsoft.com/en-us/sysinternals/accesschk.aspx

This script has come in handy while working through the Offensive Security Penetration Testing with Kali Labs.

You can compile the script to an executable using PyInstaller for easy use on any machine.

You can get pyinstaller from here: http://www.pyinstaller.org/

This is an open project and I welcome input and pull requests from anyone who wishes to contribute.

## Based on examples from the following resources:

http://www.fuzzysecurity.com/tutorials/16.html

http://toshellandback.com/2015/11/24/ms-priv-esc/
