# HP Power-Manager Buffer Overflow (Python3)

Since the official support for python2 is coming to an end and i am trying to improve my python3 skills and my understanding of exploits, i ported the well known HP Power Manager 4.2 'formExportDataLogs' Buffer Overflow exploit from python2 to python3. Please review the original python2 code by Muhammad Haidari on his github page.  [https://github.com/Muhammd/HP-Power-Manager](https://github.com/Muhammd/HP-Power-Manager)

**Tested on HP Power Manager 4.2 (Build 7) on Windows 7 Ultimate (6.1.7600 N/A Build 7600)**

*Usage: python3 hpm_exploit_p3.py : ip address the HP Power Manager is running on : port the application is running on : local port your shellcode is connecting back to -> script starts nc listener to catch reverse shell*

**This project is made for educational and ethical testing purposes only.  It is the end user's responsibility to obey all applicable laws**
