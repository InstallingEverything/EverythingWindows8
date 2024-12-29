# Charms Bar

Instructions to disable the Charms Bar.

Very easily done via a regkey change.

We will also make this avaliable via our download.

    Windows Registry Editor Version 5.00

    [HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\ImmersiveShell\EdgeUI]

    "DisableCharmsHint"=dword:1
    
    "DisableTRcorner"=dword:1
    
    "DisableTLcorner"=dword:1

No need to reboot.