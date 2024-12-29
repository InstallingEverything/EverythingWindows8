# Charms Bar

Instructions to disable the Charms Bar.

Very easily done via a regkey change.

We will also make this avaliable via our download.

    HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\ImmersiveShell\EdgeUI

    ValueName: DisableCharmsHint; ValueType: dword; ValueData: 1
    
    ValueName: DisableTRcorner; ValueType: dword; ValueData: 1
    
    ValueName: DisableTLcorner; ValueType: dword; ValueData: 1

No need to reboot.