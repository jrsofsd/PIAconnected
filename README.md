PIAconnected
============

Detect when a Private Internet Access VPN is connected.

Files:
------

+PIAconnected.exe

    PIAconnected.exe is a "compiled" Autoit script that detects whether
    the Private Internet Access (PIA) VPN is connected.

    PIAconnected.exe returns 1 if the VPN is connected, 0 otherwise.

+PIAconnected.cmd

    An example batch file "PIAconnected.cmd" is included. 
    It runs PIAconnected.exe and the exit code is available in the DOS
    environment variable %ERRORLEVEL%. The batch file displays either

        "The Private Internet Access VPN is connected..."

    or

        "The Private Internet Access VPN is NOT connected..."

+PIAconnected.au3

    Autoit sourrce code for +PIAconnected.exe.
    
+README.txt

    README text file.
