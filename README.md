# The Virtual Windows Kernel Extension project

This project is designed for Windows 7 only at the moment and is in a very early beta stage. We are working hard toward making a program to allow SOME Windows 10 applications to work on Windows 7. The project, Virtual Windows Kernel Extension or VWinKernelExt will soon be a super easy to use program allowing you to safely and easily run Windows 10 applications on Windows 7 by taking advantage of Windows' DLL order. Windows first starts by checking for the required DLLs in the launch folder of the application, we can take advantage of that by injecting certain apps with Windows 10 DLLs to try and make some apps run.

## The Windows DLL Order -- First three steps

1. Check KnownDLLs (Hardcoded in Windows Registry: HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Session Manager\KnownDLLs)
2. Check for less important DLL files (the injection point for VWinKernelExt)
3. Check System32 for DLLs



This project is attempting to make Windows 7 better to use and safer in 2025 by trying to run Windows 10 applications on it. If you would like to contribute to the project, feel free! We are accepting any form of contribution.
