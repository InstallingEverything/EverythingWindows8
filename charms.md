Disable the Charms (this can be done with a Reg-Hack, though to a lesser extent can be achieved by right clicking on the taskbar, selecting Properties and then go to Navigation and Disable ("When I Point to the upper-right corner, show the charms". The more complete Registry hack is available here in a zip file or you can enter it manually:

HKCU\SOFTWARE\Microsoft\Windows\CurrentVersion\ImmersiveShell\EdgeUI
; 
    ValueName: DisableCharmsHint; ValueType: dword; ValueData: 1
    ValueName: DisableTRcorner; ValueType: dword; ValueData: 1
    ValueName: DisableTLcorner; ValueType: dword; ValueData: 1
BTW if 
