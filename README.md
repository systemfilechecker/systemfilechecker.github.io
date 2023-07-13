# System File Checker

The SFC (System File Checker) command is a great one to use if your Windows PC is giving you problems. SFC can tell you a lot about the root cause of problems, including Blue Screen of Death (BSOD) and system faults, and it will immediately solve them.




## System File Checker (SFC) - sfc/scannow

An administrator has the ability to check the versions of all protected files using System File Checker. When System File Checker notices that a protected file has been rewritten, it searches the cache folder or the source files of the Windows installation for the right version of the file and replaces the corrupted one. The cache folder is examined and updated by System File Checker. To use System File Checker, you must be logged on as an administrator or a member of the Administrators group. The sfc /scannow, sfc /scannce, or sfc /scanboot commands can be used to restore the contents of the Caches folder if it becomes corrupted or useless.


## How to Use  System File Checker in Windows?

**System File Checker is a utility in Windows that checks for problems with files on your computer. To run it, follow these steps:**

* Make sure you've installed the latest updates for Windows, and then restart your machine. To find out more, read Update Windows.

* In the search box on the taskbar, type command prompt, and right-click or press and hold from the list of results. Select Run as administrator, and then selectYes.

* Type DISM.exe /Online /Cleanup-image /Restorehealth, and then press Enter.

* After you see a message that says **"The operation completed successfully,"** type sfc /scannow and press Enter.

* After you see a message that says, **"Verification 100% complete,"** type exit and press Enter.
