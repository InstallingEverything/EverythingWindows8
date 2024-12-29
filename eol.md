# End of Life Notification

Windows 8 went End of Life on January 12, 2016.
Windows 8.1 went End of Life on January 10, 2023.

Microsoft as they have down with previous versions of Windows installed a popup warning of the EOL date.

Below is the regkey on how to remove the popup.

    Windows Registry Editor Version 5.00

    [HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\EOSNotify]
    "DiscontinueEOS"=dword:00000001

    [HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\EOSNotify]
    "DiscontinueEOS"=dword:00000001
    "RemindMeAfterEndOfSupport"=dword:00000001
