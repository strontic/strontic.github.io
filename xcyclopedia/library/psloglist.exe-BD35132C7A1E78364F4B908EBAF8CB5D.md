---
title: psloglist.exe | local and remote event log viewer
excerpt: What is psloglist.exe?
---

# psloglist.exe 

* File Path: `C:\SysinternalsSuite\psloglist.exe`
* Description: local and remote event log viewer

## Hashes

Type | Hash
-- | --
MD5 | `BD35132C7A1E78364F4B908EBAF8CB5D`
SHA1 | `DEEF6DBBE2A19CC6CD31053B9016039AC8539AB7`
SHA256 | `57DC27269669402152518DC7683E0A9CC372A3C3125EFE1C7ECD8E8516F556F3`
SHA384 | `DD3759249B92CDA0098B867FDD3716A00B04C99818B18C3B133008CE405315FC58C7EE070D7E60C7D3CDAC84C7BA8F00`
SHA512 | `5D8DE0944FC359B5EB7078BB8DFA75E2AB4420A42686F2EB147F5929A3B753A38F4D9AD291D5ACF098EBA5D2D308414FA6E43D67DE154B2F0BCCE81F5405406B`
SSDEEP | `6144:lIo3F867FlCBaaEPz51pctlHpU4oLOiOUEnBGh0BhOJhSgfNS6DB:lIo3FvCIaEPzXpyZpU4+OjUsBGOOJ1DB`
IMP | `4FBD131B43ADA427B7988D9DAC05090E`
PESHA1 | `67CC4FEC516ED389B16CE12A56EB94DB753F50F0`
PE256 | `2F8FE93C1A50C45978663A3348C9CE5E606616B5CF03BEA5DDD0955293A1EAEB`

## Runtime Data

### Usage (stdout):
```cmhg

PsLoglist v2.81 - local and remote event log viewer
Copyright (C) 2000-2019 Mark Russinovich
Sysinternals - www.sysinternals.com

System log on \\37AACD8D-548A-4:
[513] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:36:52 AM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	49 \??\C:\Windows\AppCompat\Programs\Amcache.hve.tmp 0 0  

[512] Service Control Manager
   Type:     ERROR 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:36:47 AM   ID:       7000 
The PORTMON service failed to start due to the following error: 
%%1275

[511] Application Popup
   Type:     ERROR 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:36:47 AM   ID:       1060 
Message text not available.  Insertion strings:
	? \??\C:\SysinternalsSuite\PORTMSYS.SYS  

[510] Application Popup
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:36:47 AM   ID:       26 
Message text not available.  Insertion strings:
	? \??\C:\SysinternalsSuite\PORTMSYS.SYS failed to load  

[509] Service Control Manager
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:36:47 AM   ID:       7045 
   User:     37AACD8D-548A-4\user
A service was installed in the system.
  Service Name:  PORTMON
Service File Name:  C:\SysinternalsSuite\PORTMSYS.SYS
Service Type:  kernel mode driver
Service Start Type:  demand start
Service Account:  ?

[508] Service Control Manager
   Type:     ERROR 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:36:44 AM   ID:       7000 
The PORTMON service failed to start due to the following error: 
%%1275

[507] Application Popup
   Type:     ERROR 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:36:44 AM   ID:       1060 
Message text not available.  Insertion strings:
	? \??\C:\SysinternalsSuite\PORTMSYS.SYS  

[506] Application Popup
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:36:44 AM   ID:       26 
Message text not available.  Insertion strings:
	? \??\C:\SysinternalsSuite\PORTMSYS.SYS failed to load  

[505] Service Control Manager
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:36:44 AM   ID:       7045 
   User:     37AACD8D-548A-4\user
A service was installed in the system.
  Service Name:  PORTMON
Service File Name:  C:\SysinternalsSuite\PORTMSYS.SYS
Service Type:  kernel mode driver
Service Start Type:  demand start
Service Account:  ?

[504] Service Control Manager
   Type:     ERROR 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:36:42 AM   ID:       7000 
The PORTMON service failed to start due to the following error: 
%%1275

[503] Application Popup
   Type:     ERROR 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:36:42 AM   ID:       1060 
Message text not available.  Insertion strings:
	? \??\C:\SysinternalsSuite\PORTMSYS.SYS  

[502] Application Popup
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:36:42 AM   ID:       26 
Message text not available.  Insertion strings:
	? \??\C:\SysinternalsSuite\PORTMSYS.SYS failed to load  

[501] Service Control Manager
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:36:42 AM   ID:       7045 
   User:     37AACD8D-548A-4\user
A service was installed in the system.
  Service Name:  PORTMON
Service File Name:  C:\SysinternalsSuite\PORTMSYS.SYS
Service Type:  kernel mode driver
Service Start Type:  demand start
Service Account:  ?

[500] Application Popup
   Type:     ERROR 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:36:27 AM   ID:       1060 
Message text not available.  Insertion strings:
	? \??\C:\Windows\SysWow64\Drivers\PAGEDFRG.SYS  

[499] Application Popup
   Type:     ERROR 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:36:25 AM   ID:       1060 
Message text not available.  Insertion strings:
	? \??\C:\Windows\SysWow64\Drivers\PAGEDFRG.SYS  

[498] Application Popup
   Type:     ERROR 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:36:22 AM   ID:       1060 
Message text not available.  Insertion strings:
	? \??\C:\Windows\SysWow64\Drivers\PAGEDFRG.SYS  

[497] Application Popup
   Type:     ERROR 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:36:20 AM   ID:       1060 
Message text not available.  Insertion strings:
	? \??\C:\Windows\SysWow64\Drivers\PAGEDFRG.SYS  

[496] Application Popup
   Type:     ERROR 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:36:18 AM   ID:       1060 
Message text not available.  Insertion strings:
	? \??\C:\Windows\SysWow64\Drivers\PAGEDFRG.SYS  

[495] Service Control Manager
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:35:54 AM   ID:       7045 
   User:     37AACD8D-548A-4\user
A service was installed in the system.
  Service Name:  MYFAULT
Service File Name:  C:\Windows\system32\drivers\myfault.sys
Service Type:  kernel mode driver
Service Start Type:  demand start
Service Account:  ?

[494] Application Popup
   Type:     ERROR 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:35:50 AM   ID:       1060 
Message text not available.  Insertion strings:
	? \??\C:\Windows\SysWow64\drivers\myfault.sys  

[493] Service Control Manager
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:35:50 AM   ID:       7045 
   User:     37AACD8D-548A-4\user
A service was installed in the system.
  Service Name:  MYFAULT
Service File Name:  C:\Windows\system32\drivers\myfault.sys
Service Type:  kernel mode driver
Service Start Type:  demand start
Service Account:  ?

[492] Application Popup
   Type:     ERROR 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:35:50 AM   ID:       1060 
Message text not available.  Insertion strings:
	? \??\C:\Windows\SysWow64\drivers\myfault.sys  

[491] Service Control Manager
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:35:50 AM   ID:       7045 
   User:     37AACD8D-548A-4\user
A service was installed in the system.
  Service Name:  MYFAULT
Service File Name:  C:\Windows\system32\drivers\myfault.sys
Service Type:  kernel mode driver
Service Start Type:  demand start
Service Account:  ?

[490] Application Popup
   Type:     ERROR 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:35:50 AM   ID:       1060 
Message text not available.  Insertion strings:
	? \??\C:\Windows\SysWow64\drivers\myfault.sys  

[489] Service Control Manager
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:35:50 AM   ID:       7045 
   User:     37AACD8D-548A-4\user
A service was installed in the system.
  Service Name:  MYFAULT
Service File Name:  C:\Windows\system32\drivers\myfault.sys
Service Type:  kernel mode driver
Service Start Type:  demand start
Service Account:  ?

[488] Application Popup
   Type:     ERROR 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:35:45 AM   ID:       1060 
Message text not available.  Insertion strings:
	? \??\C:\Windows\SysWow64\drivers\myfault.sys  

[487] Service Control Manager
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:35:45 AM   ID:       7045 
   User:     37AACD8D-548A-4\user
A service was installed in the system.
  Service Name:  MYFAULT
Service File Name:  C:\Windows\system32\drivers\myfault.sys
Service Type:  kernel mode driver
Service Start Type:  demand start
Service Account:  ?

[486] Application Popup
   Type:     ERROR 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:35:45 AM   ID:       1060 
Message text not available.  Insertion strings:
	? \??\C:\Windows\SysWow64\drivers\myfault.sys  

[485] Service Control Manager
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:35:45 AM   ID:       7045 
   User:     37AACD8D-548A-4\user
A service was installed in the system.
  Service Name:  MYFAULT
Service File Name:  C:\Windows\system32\drivers\myfault.sys
Service Type:  kernel mode driver
Service Start Type:  demand start
Service Account:  ?

[484] Application Popup
   Type:     ERROR 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:35:45 AM   ID:       1060 
Message text not available.  Insertion strings:
	? \??\C:\Windows\SysWow64\drivers\myfault.sys  

[483] Service Control Manager
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:35:45 AM   ID:       7045 
   User:     37AACD8D-548A-4\user
A service was installed in the system.
  Service Name:  MYFAULT
Service File Name:  C:\Windows\system32\drivers\myfault.sys
Service Type:  kernel mode driver
Service Start Type:  demand start
Service Account:  ?

[482] Application Popup
   Type:     ERROR 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:35:40 AM   ID:       1060 
Message text not available.  Insertion strings:
	? \??\C:\Windows\SysWow64\drivers\myfault.sys  

[481] Service Control Manager
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:35:40 AM   ID:       7045 
   User:     37AACD8D-548A-4\user
A service was installed in the system.
  Service Name:  MYFAULT
Service File Name:  C:\Windows\system32\drivers\myfault.sys
Service Type:  kernel mode driver
Service Start Type:  demand start
Service Account:  ?

[480] Application Popup
   Type:     ERROR 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:35:40 AM   ID:       1060 
Message text not available.  Insertion strings:
	? \??\C:\Windows\SysWow64\drivers\myfault.sys  

[479] Service Control Manager
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:35:40 AM   ID:       7045 
   User:     37AACD8D-548A-4\user
A service was installed in the system.
  Service Name:  MYFAULT
Service File Name:  C:\Windows\system32\drivers\myfault.sys
Service Type:  kernel mode driver
Service Start Type:  demand start
Service Account:  ?

[478] Application Popup
   Type:     ERROR 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:35:40 AM   ID:       1060 
Message text not available.  Insertion strings:
	? \??\C:\Windows\SysWow64\drivers\myfault.sys  

[477] Service Control Manager
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:35:40 AM   ID:       7045 
   User:     37AACD8D-548A-4\user
A service was installed in the system.
  Service Name:  MYFAULT
Service File Name:  C:\Windows\system32\drivers\myfault.sys
Service Type:  kernel mode driver
Service Start Type:  demand start
Service Account:  ?

[476] Microsoft-Windows-FilterManager
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:24:34 AM   ID:       6 
   User:     NT AUTHORITY\SYSTEM
File System Filter 'PROCMON24' (0.0, 2020-09-17T12:57:21.0000000Z) has successfully loaded and registered with Filter Manager.

[475] Service Control Manager
   Type:     ERROR 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:24:08 AM   ID:       7000 
The PORTMON service failed to start due to the following error: 
%%1275

[474] Application Popup
   Type:     ERROR 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:24:08 AM   ID:       1060 
Message text not available.  Insertion strings:
	? \??\C:\SysinternalsSuite\PORTMSYS.SYS  

[473] Application Popup
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:24:08 AM   ID:       26 
Message text not available.  Insertion strings:
	? \??\C:\SysinternalsSuite\PORTMSYS.SYS failed to load  

[472] Service Control Manager
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:24:08 AM   ID:       7045 
   User:     37AACD8D-548A-4\user
A service was installed in the system.
  Service Name:  PORTMON
Service File Name:  C:\SysinternalsSuite\PORTMSYS.SYS
Service Type:  kernel mode driver
Service Start Type:  demand start
Service Account:  ?

[471] Service Control Manager
   Type:     ERROR 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:24:03 AM   ID:       7000 
The PORTMON service failed to start due to the following error: 
%%1275

[470] Application Popup
   Type:     ERROR 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:24:03 AM   ID:       1060 
Message text not available.  Insertion strings:
	? \??\C:\SysinternalsSuite\PORTMSYS.SYS  

[469] Application Popup
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:24:03 AM   ID:       26 
Message text not available.  Insertion strings:
	? \??\C:\SysinternalsSuite\PORTMSYS.SYS failed to load  

[468] Service Control Manager
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:24:03 AM   ID:       7045 
   User:     37AACD8D-548A-4\user
A service was installed in the system.
  Service Name:  PORTMON
Service File Name:  C:\SysinternalsSuite\PORTMSYS.SYS
Service Type:  kernel mode driver
Service Start Type:  demand start
Service Account:  ?

[467] Application Popup
   Type:     ERROR 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:23:40 AM   ID:       1060 
Message text not available.  Insertion strings:
	? \??\C:\Windows\SysWow64\Drivers\PAGEDFRG.SYS  

[466] Application Popup
   Type:     ERROR 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:23:24 AM   ID:       1060 
Message text not available.  Insertion strings:
	? \??\C:\Windows\SysWow64\drivers\myfault.sys  

[465] Service Control Manager
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:23:24 AM   ID:       7045 
   User:     37AACD8D-548A-4\user
A service was installed in the system.
  Service Name:  MYFAULT
Service File Name:  C:\Windows\system32\drivers\myfault.sys
Service Type:  kernel mode driver
Service Start Type:  demand start
Service Account:  ?

[464] Application Popup
   Type:     ERROR 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:23:24 AM   ID:       1060 
Message text not available.  Insertion strings:
	? \??\C:\Windows\SysWow64\drivers\myfault.sys  

[463] Service Control Manager
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:23:24 AM   ID:       7045 
   User:     37AACD8D-548A-4\user
A service was installed in the system.
  Service Name:  MYFAULT
Service File Name:  C:\Windows\system32\drivers\myfault.sys
Service Type:  kernel mode driver
Service Start Type:  demand start
Service Account:  ?

[462] Application Popup
   Type:     ERROR 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:23:24 AM   ID:       1060 
Message text not available.  Insertion strings:
	? \??\C:\Windows\SysWow64\drivers\myfault.sys  

[461] Service Control Manager
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:23:24 AM   ID:       7045 
   User:     37AACD8D-548A-4\user
A service was installed in the system.
  Service Name:  MYFAULT
Service File Name:  C:\Windows\system32\drivers\myfault.sys
Service Type:  kernel mode driver
Service Start Type:  demand start
Service Account:  ?

[460] Service Control Manager
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:18:46 AM   ID:       7040 
   User:     NT AUTHORITY\SYSTEM
The start type of the Background Intelligent Transfer Service service was changed from auto start to demand start.

[459] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:18:01 AM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	45 \??\C:\Windows\AppCompat\Programs\Amcache.hve 1 1  

[458] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:17:14 AM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	117 \??\C:\Users\user\AppData\Local\Packages\Microsoft.AAD.BrokerPlugin_cw5n1h2txyewy\Settings\settings.dat 6 1  

[457] DCOM
   Type:     ERROR 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:17:13 AM   ID:       10010 
   User:     37AACD8D-548A-4\user
Message text not available.  Insertion strings:
	MicrosoftWindows.Client.CBS_120.2212.31.0_x64__cw5n1h2txyewy!InputApp  

[456] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:17:12 AM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	132 \??\C:\Users\user\AppData\Local\Packages\Microsoft.Windows.StartMenuExperienceHost_cw5n1h2txyewy\Settings\settings.dat 4 1  

[455] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:16:53 AM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	119 \??\C:\Windows\ServiceProfiles\NetworkService\AppData\Local\Microsoft\Windows\DeliveryOptimization\State\dosvcState.dat 2 1  

[454] Service Control Manager
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:16:35 AM   ID:       7040 
   User:     NT AUTHORITY\SYSTEM
The start type of the Background Intelligent Transfer Service service was changed from demand start to auto start.

[453] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:15:37 AM   ID:       16 
   User:     37AACD8D-548A-4\user
Message text not available.  Insertion strings:
	118 \??\C:\Users\user\AppData\Local\Packages\MicrosoftWindows.Client.CBS_cw5n1h2txyewy\Settings\settings.dat 2 1  

[452] DCOM
   Type:     ERROR 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:15:36 AM   ID:       10010 
   User:     37AACD8D-548A-4\user
Message text not available.  Insertion strings:
	MicrosoftWindows.Client.CBS_120.2212.31.0_x64__cw5n1h2txyewy!InputApp  

[451] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:15:31 AM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	131 \??\C:\Users\user\AppData\Local\Packages\Microsoft.Windows.ContentDeliveryManager_cw5n1h2txyewy\Settings\settings.dat 81 4  

[450] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:15:22 AM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	115 \??\C:\Users\user\AppData\Local\Packages\Microsoft.Windows.Search_cw5n1h2txyewy\Settings\settings.dat 85 9  

[449] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:15:12 AM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	114 \??\C:\Users\user\AppData\Local\Packages\Microsoft.MicrosoftEdge_8wekyb3d8bbwe\Settings\settings.dat 5 1  

[448] Microsoft-Windows-TPM-WMI
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:15:10 AM   ID:       1281 
   User:     NT AUTHORITY\SYSTEM
This event triggers the TBS device identifier generation.

[447] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:15:08 AM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	76 \??\C:\Users\user\AppData\Local\Microsoft\Windows\UsrClass.dat 1189 126  

[446] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:15:08 AM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	42 \??\C:\Users\user\ntuser.dat 1752 92  

[445] Microsoft-Windows-Winlogon
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:15:08 AM   ID:       7001 
   User:     NT AUTHORITY\SYSTEM
User Logon Notification for Customer Experience Improvement Program

[444] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:15:05 AM   ID:       1 
   User:     NT AUTHORITY\SYSTEM
Possible detection of CVE: 2020-09-25T12:15:05.7161853Z
Additional Information: 2020-09-25T12:15:05.7161853Z
  This Event is generated when an attempt to exploit a known vulnerability (2020-09-25T12:15:05.7161853Z) is detected.
This Event is raised by a User mode process.
  
[443] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:15:05 AM   ID:       24 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	0 240 2 0 0  

[442] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:15:05 AM   ID:       22 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	240 0  

[441] Microsoft-Windows-Hyper-V-Netvsc
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:15:05 AM   ID:       11 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	33 Microsoft Hyper-V Network Adapter  

[440] Microsoft-Windows-Hyper-V-Netvsc
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:15:05 AM   ID:       3 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	33 Microsoft Hyper-V Network Adapter  

[439] Microsoft-Windows-Hyper-V-Netvsc
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:15:05 AM   ID:       12 
Message text not available.  Insertion strings:
	33 Microsoft Hyper-V Network Adapter  

[438] Microsoft-Windows-Hyper-V-Netvsc
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:15:05 AM   ID:       13 
Message text not available.  Insertion strings:
	33 Microsoft Hyper-V Network Adapter  

[437] Microsoft-Windows-Hyper-V-Netvsc
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:15:05 AM   ID:       1 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	3 6.1 0  

[436] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:15:04 AM   ID:       1 
   User:     NT AUTHORITY\LOCAL SERVICE
Possible detection of CVE: 2020-09-25T12:15:04.0010000Z
Additional Information: 2020-09-20T15:27:48.9217623Z
  This Event is generated when an attempt to exploit a known vulnerability (2020-09-25T12:15:04.0010000Z) is detected.
This Event is raised by a User mode process.
  
[435] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:15:04 AM   ID:       24 
   User:     NT AUTHORITY\LOCAL SERVICE
Message text not available.  Insertion strings:
	0 0 0 0 0  

[434] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/20/2020 11:27:48 AM   ID:       1 
   User:     NT AUTHORITY\LOCAL SERVICE
Possible detection of CVE: 2020-09-20T15:27:48.6350000Z
Additional Information: 2020-09-09T07:08:11.7239767Z
  This Event is generated when an attempt to exploit a known vulnerability (2020-09-20T15:27:48.6350000Z) is detected.
This Event is raised by a User mode process.
  
[433] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/20/2020 11:27:48 AM   ID:       24 
   User:     NT AUTHORITY\LOCAL SERVICE
Message text not available.  Insertion strings:
	0 0 0 0 0  

[432] EventLog
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/25/2020 8:15:04 AM   ID:       6013 
The system uptime is 28 seconds.

[431] EventLog
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/20/2020 11:27:48 AM   ID:       6013 
The system uptime is 28 seconds.

[430] Service Control Manager
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/9/2020 3:08:01 AM   ID:       7026 
The following boot-start or system-start driver(s) did not load: 
CSC
dam

[429] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/9/2020 3:08:01 AM   ID:       1 
   User:     NT AUTHORITY\SYSTEM
Possible detection of CVE: 2020-09-09T07:08:01.5569041Z
Additional Information: 2020-09-09T07:08:01.5569041Z
  This Event is generated when an attempt to exploit a known vulnerability (2020-09-09T07:08:01.5569041Z) is detected.
This Event is raised by a User mode process.
  
[428] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/9/2020 3:08:01 AM   ID:       24 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	0 0 0 0 0  

[427] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/9/2020 3:08:01 AM   ID:       22 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	0 420  

[426] Microsoft-Windows-DHCPv6-Client
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/9/2020 3:07:59 AM   ID:       51046 
   User:     NT AUTHORITY\LOCAL SERVICE
DHCPv6 client service is started

[425] Microsoft-Windows-Dhcp-Client
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/9/2020 3:07:59 AM   ID:       50103 
   User:     NT AUTHORITY\LOCAL SERVICE
DHCPv4 client registered for shutdown notification

[424] Microsoft-Windows-Dhcp-Client
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/9/2020 3:07:59 AM   ID:       50036 
   User:     NT AUTHORITY\LOCAL SERVICE
DHCPv4 client service is started

[423] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/9/2020 3:07:59 AM   ID:       1 
   User:     NT AUTHORITY\LOCAL SERVICE
Possible detection of CVE: 2020-09-09T07:07:59.8210000Z
Additional Information: 2020-09-09T10:07:59.2597578Z
  This Event is generated when an attempt to exploit a known vulnerability (2020-09-09T07:07:59.8210000Z) is detected.
This Event is raised by a User mode process.
  
[422] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/9/2020 3:07:59 AM   ID:       24 
   User:     NT AUTHORITY\LOCAL SERVICE
Message text not available.  Insertion strings:
	0 420 2 0 0  

[421] Microsoft-Windows-FilterManager
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/9/2020 6:07:59 AM   ID:       6 
   User:     NT AUTHORITY\SYSTEM
File System Filter 'bindflt' (10.0, 2090-10-31T12:47:32.0000000Z) has successfully loaded and registered with Filter Manager.

[420] Microsoft-Windows-FilterManager
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/9/2020 6:07:59 AM   ID:       6 
   User:     NT AUTHORITY\SYSTEM
File System Filter 'CldFlt' (10.0, 2003-03-20T16:36:50.0000000Z) has successfully loaded and registered with Filter Manager.

[419] Microsoft-Windows-FilterManager
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/9/2020 6:07:59 AM   ID:       1 
   User:     NT AUTHORITY\SYSTEM
File System Filter 'CldFlt' (Version 10.0, 2003-03-20T16:36:50.0000000Z) unloaded successfully.

[418] Microsoft-Windows-FilterManager
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/9/2020 6:07:59 AM   ID:       6 
   User:     NT AUTHORITY\SYSTEM
File System Filter 'CldFlt' (10.0, 2003-03-20T16:36:50.0000000Z) has successfully loaded and registered with Filter Manager.

[417] Service Control Manager
   Type:     ERROR 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/9/2020 6:07:59 AM   ID:       7000 
The luafv service failed to start due to the following error: 
%%1275

[416] Microsoft-Windows-Directory-Services-SAM
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/9/2020 6:07:58 AM   ID:       16977 
   User:     NT AUTHORITY\SYSTEM
The domain is configured with the following minimum password length-related settings.
  MinimumPasswordLength: 0
  RelaxMinimumPasswordLengthLimits: 0
  MinimumPasswordLengthAudit: -1
  For more information see https://go.microsoft.com/fwlink/?LinkId=2097191.
  
[415] Microsoft-Windows-Directory-Services-SAM
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/9/2020 6:07:58 AM   ID:       16962 
   User:     NT AUTHORITY\SYSTEM
Remote calls to the SAM database are being restricted using the default security descriptor: O:SYG:SYD:(A;;RC;;;BA).
For more information please see http://go.microsoft.com/fwlink/?LinkId=787651.

[414] Microsoft-Windows-Wininit
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/9/2020 6:07:57 AM   ID:       14 
   User:     NT AUTHORITY\SYSTEM
Credential Guard configuration: 0, 0

[413] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/9/2020 6:07:57 AM   ID:       24 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	0 420 2 0 0  

[412] Microsoft-Windows-CoreSystem-InitMachineConfig
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/9/2020 6:07:56 AM   ID:       2 
   User:     NT AUTHORITY\SYSTEM
Initial Machine Configuration processing of hive 'SYSTEM' has completed.

[411] Microsoft-Windows-Kernel-Power
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/9/2020 6:07:55 AM   ID:       521 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	1 0 0  

[410] Microsoft-Windows-Kernel-Power
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/9/2020 6:07:55 AM   ID:       521 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	0 0 0  

[409] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/9/2020 6:07:55 AM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 7 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2394
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[408] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/9/2020 6:07:55 AM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 6 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2394
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[407] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/9/2020 6:07:55 AM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 5 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2394
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[406] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/9/2020 6:07:55 AM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 4 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2394
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[405] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/9/2020 6:07:55 AM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 3 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2394
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[404] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/9/2020 6:07:55 AM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 2 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2394
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[403] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/9/2020 6:07:55 AM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 1 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2394
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[402] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/9/2020 6:07:55 AM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 0 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2394
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[401] Microsoft-Windows-Kernel-Power
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/9/2020 6:07:55 AM   ID:       172 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	2 6  

[400] Microsoft-Windows-FilterManager
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/9/2020 6:07:55 AM   ID:       6 
   User:     NT AUTHORITY\SYSTEM
File System Filter 'npsvctrig' (10.0, 2025-01-05T19:41:12.0000000Z) has successfully loaded and registered with Filter Manager.

[399] Microsoft-Windows-FilterManager
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/9/2020 6:07:48 AM   ID:       6 
   User:     NT AUTHORITY\SYSTEM
File System Filter 'FileCrypt' (10.0, 2002-03-01T04:12:42.0000000Z) has successfully loaded and registered with Filter Manager.

[398] Microsoft-Windows-Ntfs
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/9/2020 6:07:47 AM   ID:       98 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	C: \Device\HarddiskVolume2 0  

[397] TermService
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/9/2020 3:08:01 AM   ID:       1056 
A new self signed certificate to be used for RD Session Host Server authentication on SSL connections was generated. The name on this certificate is 37aacd8d-548a-4e5b-8f88-125853a1ecae. The SHA1 hash of the certificate is in the event data.

[396] Microsoft-Windows-FilterManager
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/9/2020 6:07:47 AM   ID:       6 
   User:     NT AUTHORITY\SYSTEM
File System Filter 'wcifs' (10.0, 2027-01-31T19:32:49.0000000Z) has successfully loaded and registered with Filter Manager.

[395] Microsoft-Windows-FilterManager
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/9/2020 6:07:47 AM   ID:       6 
   User:     NT AUTHORITY\SYSTEM
File System Filter 'FileInfo' (10.0, 2062-12-22T22:21:06.0000000Z) has successfully loaded and registered with Filter Manager.

[394] Microsoft-Windows-HAL
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/9/2020 6:07:47 AM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
The iommu fault reporting has been initialized.

[393] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/9/2020 6:07:47 AM   ID:       20 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	0 true 0 0  

[392] Microsoft-Windows-Kernel-Boot
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/9/2020 6:07:47 AM   ID:       30 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	0 65 68 4465 4478  

[391] Microsoft-Windows-Kernel-Boot
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/9/2020 6:07:47 AM   ID:       27 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	0  NOEXECUTE=OPTIN  NOVGA  

[390] Microsoft-Windows-Kernel-Boot
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/9/2020 6:07:47 AM   ID:       25 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	1  

[389] Microsoft-Windows-Kernel-Boot
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/9/2020 6:07:47 AM   ID:       238 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	2047 0  

[388] Microsoft-Windows-Kernel-Boot
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/9/2020 6:07:47 AM   ID:       20 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	true true 2 2  

[387] Microsoft-Windows-Kernel-Boot
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/9/2020 6:07:47 AM   ID:       32 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	0  

[386] Microsoft-Windows-Kernel-Boot
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/9/2020 6:07:47 AM   ID:       18 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	1  

[385] Microsoft-Windows-Kernel-Boot
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/9/2020 6:07:47 AM   ID:       153 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	0 0 0  

[384] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/9/2020 6:07:47 AM   ID:       12 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	10 0 19041 508 0 0 2020-09-09T10:07:42.5000000Z  

[383] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/6/2020 5:26:47 PM   ID:       13 
Message text not available.  Insertion strings:
	2020-09-06T21:26:47.7120040Z  

[382] Microsoft-Windows-Kernel-Power
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/6/2020 5:26:47 PM   ID:       109 
Message text not available.  Insertion strings:
	4 0 5  

[381] EventLog
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/9/2020 6:07:59 AM   ID:       6013 
The system uptime is 16 seconds.

[380] EventLog
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/9/2020 6:07:59 AM   ID:       6005 
The Event log service was started.

[379] EventLog
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/9/2020 6:07:59 AM   ID:       6009 
Microsoft (R) Windows (R) 10.00. 19041 ? Multiprocessor Free.

[378] EventLog
   Type:     INFORMATION 
   Computer: 37aacd8d-548a-4e5b-8f88-125853a1ecae
   Time:     9/9/2020 6:07:59 AM   ID:       6011 
The NetBIOS name and DNS host name of this machine have been changed from DESKTOP-11ON0OT to 37AACD8D-548A-4.

[377] Microsoft-Windows-Dhcp-Client
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:26:46 PM   ID:       50037 
   User:     NT AUTHORITY\LOCAL SERVICE
DHCPv4 client service is stopped. ShutDown Flag value is 1

[376] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:26:46 PM   ID:       1 
   User:     NT AUTHORITY\LOCAL SERVICE
Possible detection of CVE: 2020-09-06T21:26:46.6345344Z
Additional Information: 2020-09-06T21:26:46.6287622Z
  This Event is generated when an attempt to exploit a known vulnerability (2020-09-06T21:26:46.6345344Z) is detected.
This Event is raised by a User mode process.
  
[375] Microsoft-Windows-Dhcp-Client
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:26:46 PM   ID:       50106 
   User:     NT AUTHORITY\LOCAL SERVICE
DHCPv4 is waiting on DHCPv6 service to stop

[374] Microsoft-Windows-DHCPv6-Client
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:26:46 PM   ID:       51047 
   User:     NT AUTHORITY\LOCAL SERVICE
DHCPv6 client service is stopped. ShutDown Flag value is 1

[373] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:26:46 PM   ID:       24 
   User:     NT AUTHORITY\LOCAL SERVICE
Message text not available.  Insertion strings:
	0 420 2 0 0  

[372] Microsoft-Windows-Dhcp-Client
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:26:46 PM   ID:       50105 
   User:     NT AUTHORITY\LOCAL SERVICE
DHCPv4 client ProcessDHCPRequestForever received TERMINATE_EVENT

[371] Microsoft-Windows-Dhcp-Client
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:26:46 PM   ID:       50104 
   User:     NT AUTHORITY\LOCAL SERVICE
DHCPv4 client received shutdown notification

[370] EventLog
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:26:46 PM   ID:       6006 
The Event log service was stopped.

[369] Service Control Manager
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:26:46 PM   ID:       7040 
   User:     NT AUTHORITY\SYSTEM
The start type of the Windows Modules Installer service was changed from auto start to demand start.

[368] Microsoft-Windows-Winlogon
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:26:45 PM   ID:       7002 
   User:     NT AUTHORITY\SYSTEM
User Logoff Notification for Customer Experience Improvement Program

[367] DCOM
   Type:     ERROR 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:26:44 PM   ID:       10010 
   User:     37AACD8D-548A-4\user
Message text not available.  Insertion strings:
	{D63B10C5-BB46-4990-A94F-E40B9D520160}  

[366] DCOM
   Type:     ERROR 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:26:44 PM   ID:       10010 
   User:     37AACD8D-548A-4\user
Message text not available.  Insertion strings:
	{AB8902B4-09CA-4BB6-B78D-A8F59079A8D5}  

[365] DCOM
   Type:     ERROR 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:26:44 PM   ID:       10010 
   User:     37AACD8D-548A-4\user
Message text not available.  Insertion strings:
	{AB8902B4-09CA-4BB6-B78D-A8F59079A8D5}  

[364] DCOM
   Type:     ERROR 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:26:44 PM   ID:       10010 
   User:     37AACD8D-548A-4\user
Message text not available.  Insertion strings:
	{AB8902B4-09CA-4BB6-B78D-A8F59079A8D5}  

[363] DCOM
   Type:     ERROR 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:26:44 PM   ID:       10010 
   User:     37AACD8D-548A-4\user
Message text not available.  Insertion strings:
	{AB8902B4-09CA-4BB6-B78D-A8F59079A8D5}  

[362] DCOM
   Type:     ERROR 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:26:44 PM   ID:       10010 
   User:     37AACD8D-548A-4\user
Message text not available.  Insertion strings:
	{AB8902B4-09CA-4BB6-B78D-A8F59079A8D5}  

[361] DCOM
   Type:     ERROR 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:26:44 PM   ID:       10010 
   User:     37AACD8D-548A-4\user
Message text not available.  Insertion strings:
	{AB8902B4-09CA-4BB6-B78D-A8F59079A8D5}  

[360] Service Control Manager
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:26:44 PM   ID:       7040 
   User:     NT AUTHORITY\SYSTEM
The start type of the Windows Modules Installer service was changed from demand start to auto start.

[359] DCOM
   Type:     ERROR 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:26:44 PM   ID:       10010 
   User:     37AACD8D-548A-4\user
Message text not available.  Insertion strings:
	{AB8902B4-09CA-4BB6-B78D-A8F59079A8D5}  

[358] DCOM
   Type:     ERROR 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:26:44 PM   ID:       10010 
   User:     37AACD8D-548A-4\user
Message text not available.  Insertion strings:
	{AB8902B4-09CA-4BB6-B78D-A8F59079A8D5}  

[357] DCOM
   Type:     ERROR 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:26:44 PM   ID:       10010 
   User:     37AACD8D-548A-4\user
Message text not available.  Insertion strings:
	{AB8902B4-09CA-4BB6-B78D-A8F59079A8D5}  

[356] DCOM
   Type:     ERROR 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:26:44 PM   ID:       10010 
   User:     37AACD8D-548A-4\user
Message text not available.  Insertion strings:
	{AB8902B4-09CA-4BB6-B78D-A8F59079A8D5}  

[355] DCOM
   Type:     ERROR 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:26:44 PM   ID:       10010 
   User:     37AACD8D-548A-4\user
Message text not available.  Insertion strings:
	{AB8902B4-09CA-4BB6-B78D-A8F59079A8D5}  

[354] DCOM
   Type:     ERROR 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:26:44 PM   ID:       10010 
   User:     37AACD8D-548A-4\user
Message text not available.  Insertion strings:
	{AB8902B4-09CA-4BB6-B78D-A8F59079A8D5}  

[353] DCOM
   Type:     ERROR 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:26:43 PM   ID:       10010 
   User:     37AACD8D-548A-4\user
Message text not available.  Insertion strings:
	{AB8902B4-09CA-4BB6-B78D-A8F59079A8D5}  

[352] DCOM
   Type:     ERROR 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:26:43 PM   ID:       10010 
   User:     37AACD8D-548A-4\user
Message text not available.  Insertion strings:
	{AB8902B4-09CA-4BB6-B78D-A8F59079A8D5}  

[351] DCOM
   Type:     ERROR 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:26:43 PM   ID:       10010 
   User:     37AACD8D-548A-4\user
Message text not available.  Insertion strings:
	{AB8902B4-09CA-4BB6-B78D-A8F59079A8D5}  

[350] DCOM
   Type:     ERROR 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:26:43 PM   ID:       10010 
   User:     37AACD8D-548A-4\user
Message text not available.  Insertion strings:
	{AB8902B4-09CA-4BB6-B78D-A8F59079A8D5}  

[349] DCOM
   Type:     ERROR 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:26:43 PM   ID:       10010 
   User:     37AACD8D-548A-4\user
Message text not available.  Insertion strings:
	{AB8902B4-09CA-4BB6-B78D-A8F59079A8D5}  

[348] DCOM
   Type:     ERROR 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:26:43 PM   ID:       10010 
   User:     37AACD8D-548A-4\user
Message text not available.  Insertion strings:
	{AB8902B4-09CA-4BB6-B78D-A8F59079A8D5}  

[347] DCOM
   Type:     ERROR 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:26:43 PM   ID:       10010 
   User:     37AACD8D-548A-4\user
Message text not available.  Insertion strings:
	{AB8902B4-09CA-4BB6-B78D-A8F59079A8D5}  

[346] DCOM
   Type:     ERROR 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:26:43 PM   ID:       10010 
   User:     37AACD8D-548A-4\user
Message text not available.  Insertion strings:
	{AB8902B4-09CA-4BB6-B78D-A8F59079A8D5}  

[345] DCOM
   Type:     ERROR 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:26:43 PM   ID:       10010 
   User:     37AACD8D-548A-4\user
Message text not available.  Insertion strings:
	{A463FCB9-6B1C-4E0D-A80B-A2CA7999E25D}  

[344] DCOM
   Type:     ERROR 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:26:43 PM   ID:       10010 
   User:     37AACD8D-548A-4\user
Message text not available.  Insertion strings:
	{AB8902B4-09CA-4BB6-B78D-A8F59079A8D5}  

[343] DCOM
   Type:     ERROR 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:26:43 PM   ID:       10010 
   User:     37AACD8D-548A-4\user
Message text not available.  Insertion strings:
	{AB8902B4-09CA-4BB6-B78D-A8F59079A8D5}  

[342] DCOM
   Type:     ERROR 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:26:43 PM   ID:       10010 
   User:     37AACD8D-548A-4\user
Message text not available.  Insertion strings:
	{AB8902B4-09CA-4BB6-B78D-A8F59079A8D5}  

[341] DCOM
   Type:     ERROR 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:26:43 PM   ID:       10010 
   User:     37AACD8D-548A-4\user
Message text not available.  Insertion strings:
	{AB8902B4-09CA-4BB6-B78D-A8F59079A8D5}  

[340] User32
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:26:42 PM   ID:       1074 
   User:     NT AUTHORITY\SYSTEM
The process C:\Windows\System32\wcsetupagent.exe (Default-PC) has initiated the shutdown of computer DESKTOP-11ON0OT on behalf of user NT AUTHORITY\SYSTEM for the following reason: Operating System: Reconfiguration (Planned)
 Reason Code: 0x80020004
 Shutdown Type: shutdown
 Comment: ?

[339] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:26:42 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	120 \??\C:\Users\user\AppData\Local\Packages\windows.immersivecontrolpanel_cw5n1h2txyewy\Settings\settings.dat 3 1  

[338] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:26:42 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	122 \??\C:\Users\user\AppData\Local\Packages\MicrosoftWindows.UndockedDevKit_cw5n1h2txyewy\Settings\settings.dat 3 1  

[337] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:26:42 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	118 \??\C:\Users\user\AppData\Local\Packages\MicrosoftWindows.Client.CBS_cw5n1h2txyewy\Settings\settings.dat 3 1  

[336] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:26:42 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	128 \??\C:\Users\user\AppData\Local\Packages\Microsoft.Windows.ShellExperienceHost_cw5n1h2txyewy\Settings\settings.dat 3 1  

[335] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:26:42 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	134 \??\C:\Users\user\AppData\Local\Packages\Microsoft.Windows.OOBENetworkConnectionFlow_cw5n1h2txyewy\Settings\settings.dat 3 1  

[334] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:26:42 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	133 \??\C:\Users\user\AppData\Local\Packages\Microsoft.Windows.OOBENetworkCaptivePortal_cw5n1h2txyewy\Settings\settings.dat 3 1  

[333] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:26:42 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	128 \??\C:\Users\user\AppData\Local\Packages\Microsoft.Windows.CloudExperienceHost_cw5n1h2txyewy\Settings\settings.dat 3 1  

[332] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:26:42 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	114 \??\C:\Users\user\AppData\Local\Packages\Microsoft.MicrosoftEdge_8wekyb3d8bbwe\Settings\settings.dat 3 1  

[331] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:26:42 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	114 \??\C:\Users\user\AppData\Local\Packages\Microsoft.BioEnrollment_cw5n1h2txyewy\Settings\settings.dat 3 1  

[330] Microsoft-Windows-Time-Service
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:46 PM   ID:       35 
   User:     NT AUTHORITY\LOCAL SERVICE
The time service is now synchronizing the system time with the time source VM IC Time Synchronization Provider with reference id 1347702102. Current local stratum number is 6.

[329] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:42 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	117 \??\C:\Users\user\AppData\Local\Packages\Microsoft.AAD.BrokerPlugin_cw5n1h2txyewy\Settings\settings.dat 3 1  

[328] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:41 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	115 \??\C:\Users\user\AppData\Local\Packages\Microsoft.Windows.Search_cw5n1h2txyewy\Settings\settings.dat 3 1  

[327] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:41 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	132 \??\C:\Users\user\AppData\Local\Packages\Microsoft.Windows.StartMenuExperienceHost_cw5n1h2txyewy\Settings\settings.dat 3 1  

[326] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:40 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	131 \??\C:\Users\user\AppData\Local\Packages\Microsoft.Windows.ContentDeliveryManager_cw5n1h2txyewy\Settings\settings.dat 3 1  

[325] Microsoft-Windows-GroupPolicy
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:35 PM   ID:       1501 
   User:     37AACD8D-548A-4\user
The Group Policy settings for the user were processed successfully. There were no changes detected since the last successful processing of Group Policy.

[324] Microsoft-Windows-Winlogon
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:35 PM   ID:       7001 
   User:     NT AUTHORITY\SYSTEM
User Logon Notification for Customer Experience Improvement Program

[323] Service Control Manager
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:35 PM   ID:       7040 
   User:     NT AUTHORITY\NETWORK SERVICE
The start type of the Delivery Optimization service was changed from demand start to auto start.

[322] Microsoft-Windows-GroupPolicy
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:34 PM   ID:       1500 
   User:     NT AUTHORITY\SYSTEM
The Group Policy settings for the computer were processed successfully. There were no changes detected since the last successful processing of Group Policy.

[321] Service Control Manager
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:34 PM   ID:       7040 
   User:     NT AUTHORITY\SYSTEM
The start type of the Windows Modules Installer service was changed from auto start to demand start.

[320] Service Control Manager
   Type:     ERROR 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:34 PM   ID:       7030 
The Printer Extensions and Notifications service is marked as an interactive service.  However, the system is configured to not allow interactive services.  This service may not function properly.

[319] Service Control Manager
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:34 PM   ID:       7045 
   User:     NT AUTHORITY\SYSTEM
A service was installed in the system.
  Service Name:  Printer Extensions and Notifications
Service File Name:  %SystemRoot%\system32\svchost.exe -k print
Service Type:  user mode service
Service Start Type:  demand start
Service Account:  LocalSystem

[318] Microsoft-Windows-Time-Service
   Type:     WARNING 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:32 PM   ID:       134 
   User:     NT AUTHORITY\LOCAL SERVICE
NtpClient was unable to set a manual peer to use as a time source because of DNS resolution error on 'time.windows.com,0x9'. NtpClient will try again in 15 minutes and double the reattempt interval thereafter. The error was: No such host is known. (0x80072AF9)

[317] TermService
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:32 PM   ID:       1056 
A new self signed certificate to be used for RD Session Host Server authentication on SSL connections was generated. The name on this certificate is DESKTOP-11ON0OT. The SHA1 hash of the certificate is in the event data.

[316] Service Control Manager
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:31 PM   ID:       7026 
The following boot-start or system-start driver(s) did not load: 
dam

[315] Microsoft-Windows-FilterManager
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:30 PM   ID:       6 
   User:     NT AUTHORITY\SYSTEM
File System Filter 'bindflt' (10.0, 2006-02-06T13:00:56.0000000Z) has successfully loaded and registered with Filter Manager.

[314] Microsoft-Windows-FilterManager
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:30 PM   ID:       6 
   User:     NT AUTHORITY\SYSTEM
File System Filter 'storqosflt' (10.0, 2007-04-09T11:08:30.0000000Z) has successfully loaded and registered with Filter Manager.

[313] Microsoft-Windows-FilterManager
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:30 PM   ID:       6 
   User:     NT AUTHORITY\SYSTEM
File System Filter 'CldFlt' (10.0, 2003-03-20T16:36:50.0000000Z) has successfully loaded and registered with Filter Manager.

[312] Microsoft-Windows-FilterManager
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:30 PM   ID:       1 
   User:     NT AUTHORITY\SYSTEM
File System Filter 'CldFlt' (Version 10.0, 2003-03-20T16:36:50.0000000Z) unloaded successfully.

[311] Microsoft-Windows-FilterManager
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:30 PM   ID:       6 
   User:     NT AUTHORITY\SYSTEM
File System Filter 'CldFlt' (10.0, 2003-03-20T16:36:50.0000000Z) has successfully loaded and registered with Filter Manager.

[310] Microsoft-Windows-FilterManager
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:30 PM   ID:       6 
   User:     NT AUTHORITY\SYSTEM
File System Filter 'wcifs' (10.0, 1971-08-10T04:27:38.0000000Z) has successfully loaded and registered with Filter Manager.

[309] Service Control Manager
   Type:     ERROR 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:30 PM   ID:       7000 
The luafv service failed to start due to the following error: 
%%1275

[308] Microsoft-Windows-Time-Service
   Type:     WARNING 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:30 PM   ID:       134 
   User:     NT AUTHORITY\LOCAL SERVICE
NtpClient was unable to set a manual peer to use as a time source because of DNS resolution error on 'time.windows.com,0x9'. NtpClient will try again in 15 minutes and double the reattempt interval thereafter. The error was: No such host is known. (0x80072AF9)

[307] Microsoft-Windows-DHCPv6-Client
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:30 PM   ID:       51046 
   User:     NT AUTHORITY\LOCAL SERVICE
DHCPv6 client service is started

[306] Microsoft-Windows-Dhcp-Client
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:30 PM   ID:       50103 
   User:     NT AUTHORITY\LOCAL SERVICE
DHCPv4 client registered for shutdown notification

[305] Microsoft-Windows-Dhcp-Client
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:30 PM   ID:       50036 
   User:     NT AUTHORITY\LOCAL SERVICE
DHCPv4 client service is started

[304] Microsoft-Windows-Directory-Services-SAM
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:29 PM   ID:       16977 
   User:     NT AUTHORITY\SYSTEM
The domain is configured with the following minimum password length-related settings.
  MinimumPasswordLength: 0
  RelaxMinimumPasswordLengthLimits: 0
  MinimumPasswordLengthAudit: -1
  For more information see https://go.microsoft.com/fwlink/?LinkId=2097191.
  
[303] Microsoft-Windows-Directory-Services-SAM
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:24 PM   ID:       16977 
   User:     NT AUTHORITY\SYSTEM
The domain is configured with the following minimum password length-related settings.
  MinimumPasswordLength: 0
  RelaxMinimumPasswordLengthLimits: 0
  MinimumPasswordLengthAudit: -1
  For more information see https://go.microsoft.com/fwlink/?LinkId=2097191.
  
[302] Microsoft-Windows-Directory-Services-SAM
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:24 PM   ID:       16962 
   User:     NT AUTHORITY\SYSTEM
Remote calls to the SAM database are being restricted using the default security descriptor: O:SYG:SYD:(A;;RC;;;BA).
For more information please see http://go.microsoft.com/fwlink/?LinkId=787651.

[301] Microsoft-Windows-Wininit
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:24 PM   ID:       14 
   User:     NT AUTHORITY\SYSTEM
Credential Guard configuration: 0, 0

[300] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:23 PM   ID:       24 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	0 420 2 0 0  

[299] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:23 PM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 35 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2300
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[298] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:23 PM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 34 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2300
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[297] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:23 PM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 33 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2300
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[296] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:23 PM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 32 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2300
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[295] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:23 PM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 31 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2300
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[294] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:23 PM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 30 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2300
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[293] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:23 PM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 29 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2300
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[292] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:23 PM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 28 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2300
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[291] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:23 PM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 27 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2300
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[290] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:23 PM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 26 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2300
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[289] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:23 PM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 25 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2300
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[288] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:23 PM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 24 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2300
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[287] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:23 PM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 23 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2300
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[286] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:23 PM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 22 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2300
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[285] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:23 PM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 21 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2300
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[284] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:23 PM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 20 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2300
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[283] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:23 PM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 19 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2300
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[282] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:23 PM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 18 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2300
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[281] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:23 PM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 17 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2300
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[280] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:23 PM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 16 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2300
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[279] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:23 PM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 15 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2300
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[278] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:23 PM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 14 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2300
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[277] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:23 PM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 13 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2300
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[276] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:23 PM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 12 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2300
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[275] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:23 PM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 11 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2300
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[274] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:23 PM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 10 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2300
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[273] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:23 PM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 9 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2300
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[272] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:23 PM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 8 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2300
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[271] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:23 PM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 7 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2300
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[270] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:23 PM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 6 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2300
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[269] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:23 PM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 5 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2300
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[268] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:23 PM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 4 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2300
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[267] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:23 PM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 3 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2300
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[266] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:23 PM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 2 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2300
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[265] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:23 PM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 1 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2300
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[264] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:23 PM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 0 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2300
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[263] Microsoft-Windows-Kernel-Power
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:22 PM   ID:       172 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	2 6  

[262] Microsoft-Windows-FilterManager
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:22 PM   ID:       6 
   User:     NT AUTHORITY\SYSTEM
File System Filter 'npsvctrig' (10.0, 2025-01-05T19:41:12.0000000Z) has successfully loaded and registered with Filter Manager.

[261] Microsoft-Windows-FilterManager
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:22 PM   ID:       6 
   User:     NT AUTHORITY\SYSTEM
File System Filter 'FileCrypt' (10.0, 2002-03-01T04:12:42.0000000Z) has successfully loaded and registered with Filter Manager.

[260] Microsoft-Windows-Ntfs
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:22 PM   ID:       98 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	C: \Device\HarddiskVolume2 0  

[259] Microsoft-Windows-FilterManager
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:22 PM   ID:       6 
   User:     NT AUTHORITY\SYSTEM
File System Filter 'WdFilter' (10.0, 2066-04-08T21:52:09.0000000Z) has successfully loaded and registered with Filter Manager.

[258] Microsoft-Windows-FilterManager
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:22 PM   ID:       6 
   User:     NT AUTHORITY\SYSTEM
File System Filter 'Wof' (10.0, 2050-10-18T06:21:08.0000000Z) has successfully loaded and registered with Filter Manager.

[257] Microsoft-Windows-FilterManager
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:22 PM   ID:       6 
   User:     NT AUTHORITY\SYSTEM
File System Filter 'FileInfo' (10.0, 2062-12-22T22:21:06.0000000Z) has successfully loaded and registered with Filter Manager.

[256] Microsoft-Windows-HAL
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:22 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
The iommu fault reporting has been initialized.

[255] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:22 PM   ID:       20 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	0 true 0 0  

[254] Microsoft-Windows-Kernel-Boot
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:22 PM   ID:       32 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	0  

[253] Microsoft-Windows-Kernel-Boot
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:22 PM   ID:       18 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	1  

[252] Microsoft-Windows-Kernel-Boot
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:22 PM   ID:       27 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	0  NOEXECUTE=OPTIN  NOVGA  

[251] Microsoft-Windows-Kernel-Boot
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:22 PM   ID:       25 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	1  

[250] Microsoft-Windows-Kernel-Boot
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:22 PM   ID:       238 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	2047 0  

[249] Microsoft-Windows-Kernel-Boot
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:22 PM   ID:       20 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	true true 1 2  

[248] Microsoft-Windows-Kernel-Boot
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:22 PM   ID:       153 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	0 0 0  

[247] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:22 PM   ID:       12 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	10 0 19041 508 0 0 2020-09-06T21:25:21.5000000Z  

[246] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:05 PM   ID:       13 
Message text not available.  Insertion strings:
	2020-09-06T21:25:05.8666705Z  

[245] Microsoft-Windows-Kernel-Power
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:05 PM   ID:       109 
Message text not available.  Insertion strings:
	5 0 5  

[244] EventLog
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:30 PM   ID:       6013 
The system uptime is 9 seconds.

[243] EventLog
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:30 PM   ID:       6005 
The Event log service was started.

[242] EventLog
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:30 PM   ID:       6009 
Microsoft (R) Windows (R) 10.00. 19041 ? Multiprocessor Free.

[241] EventLog
   Type:     INFORMATION 
   Computer: DESKTOP-11ON0OT
   Time:     9/6/2020 5:25:30 PM   ID:       6011 
The NetBIOS name and DNS host name of this machine have been changed from Default-PC to DESKTOP-11ON0OT.

[240] Microsoft-Windows-Dhcp-Client
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:25:00 PM   ID:       50037 
   User:     NT AUTHORITY\LOCAL SERVICE
DHCPv4 client service is stopped. ShutDown Flag value is 1

[239] Microsoft-Windows-Dhcp-Client
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:25:00 PM   ID:       50106 
   User:     NT AUTHORITY\LOCAL SERVICE
DHCPv4 is waiting on DHCPv6 service to stop

[238] Microsoft-Windows-DHCPv6-Client
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:25:00 PM   ID:       51047 
   User:     NT AUTHORITY\LOCAL SERVICE
DHCPv6 client service is stopped. ShutDown Flag value is 1

[237] Microsoft-Windows-Dhcp-Client
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:25:00 PM   ID:       50105 
   User:     NT AUTHORITY\LOCAL SERVICE
DHCPv4 client ProcessDHCPRequestForever received TERMINATE_EVENT

[236] Microsoft-Windows-Dhcp-Client
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:25:00 PM   ID:       50104 
   User:     NT AUTHORITY\LOCAL SERVICE
DHCPv4 client received shutdown notification

[235] User32
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:25:00 PM   ID:       1074 
   User:     NT AUTHORITY\SYSTEM
The process C:\Windows\system32\winlogon.exe (MINWINPC) has initiated the restart of computer Default-PC on behalf of user NT AUTHORITY\SYSTEM for the following reason: Operating System: Upgrade (Planned)
 Reason Code: 0x80020003
 Shutdown Type: restart
 Comment: ?

[234] Microsoft-Windows-Setup
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:24:59 PM   ID:       2004 
   User:     NT AUTHORITY\SYSTEM
Successfully logged OS information

[233] EventLog
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:25:00 PM   ID:       6006 
The Event log service was stopped.

[232] Microsoft-Windows-UserModePowerService
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:24:59 PM   ID:       22 
   User:     NT AUTHORITY\SYSTEM
Reapply power settings upon completion of the provisioning engine's turn 1

[231] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:24:56 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	85 \??\C:\ProgramData\Microsoft\Provisioning\Microsoft-Desktop-Provisioning-Sequence.dat 0 0  

[230] Virtual Disk Service
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:24:56 PM   ID:       4 
Service stopped.

[229] Virtual Disk Service
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:24:55 PM   ID:       3 
Service started.

[228] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:24:50 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	135 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\Microsoft.ZuneVideo_10.19071.19011.0_x64__8wekyb3d8bbwe\ActivationStore.dat 0 0  

[227] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:24:49 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	135 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\Microsoft.ZuneMusic_10.19071.19011.0_x64__8wekyb3d8bbwe\ActivationStore.dat 0 0  

[226] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:24:48 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	130 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\Microsoft.YourPhone_0.19051.7.0_x64__8wekyb3d8bbwe\ActivationStore.dat 0 0  

[225] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:24:47 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	145 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\Microsoft.XboxSpeechToTextOverlay_1.17.29001.0_x64__8wekyb3d8bbwe\ActivationStore.dat 0 0  

[224] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:24:46 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	142 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\Microsoft.XboxIdentityProvider_12.50.6001.0_x64__8wekyb3d8bbwe\ActivationStore.dat 0 0  

[223] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:24:46 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	139 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\Microsoft.XboxGamingOverlay_2.34.28001.0_x64__8wekyb3d8bbwe\ActivationStore.dat 0 0  

[222] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:24:45 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	137 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\Microsoft.XboxGameOverlay_1.46.11001.0_x64__8wekyb3d8bbwe\ActivationStore.dat 0 0  

[221] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:24:45 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	130 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\Microsoft.XboxApp_48.49.31001.0_x64__8wekyb3d8bbwe\ActivationStore.dat 0 0  

[220] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:24:43 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	131 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\Microsoft.Xbox.TCUI_1.23.28002.0_x64__8wekyb3d8bbwe\ActivationStore.dat 0 0  

[219] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:24:43 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	136 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\Microsoft.WindowsStore_11910.1002.5.0_x64__8wekyb3d8bbwe\ActivationStore.dat 0 0  

[218] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:24:41 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	144 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\Microsoft.WindowsSoundRecorder_10.1906.1972.0_x64__8wekyb3d8bbwe\ActivationStore.dat 0 0  

[217] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:24:41 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	134 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\Microsoft.WindowsMaps_5.1906.1972.0_x64__8wekyb3d8bbwe\ActivationStore.dat 0 0  

[216] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:24:38 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	141 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\Microsoft.WindowsFeedbackHub_1.1907.3152.0_x64__8wekyb3d8bbwe\ActivationStore.dat 0 0  

[215] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:24:37 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	154 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\microsoft.windowscommunicationsapps_16005.11629.20316.0_x64__8wekyb3d8bbwe\ActivationStore.dat 0 0  

[214] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:24:33 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	136 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\Microsoft.WindowsCamera_2018.826.98.0_x64__8wekyb3d8bbwe\ActivationStore.dat 0 0  

[213] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:24:32 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	139 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\Microsoft.WindowsCalculator_10.1906.55.0_x64__8wekyb3d8bbwe\ActivationStore.dat 0 0  

[212] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:24:31 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	137 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\Microsoft.WindowsAlarms_10.1906.2182.0_x64__8wekyb3d8bbwe\ActivationStore.dat 0 0  

[211] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:24:29 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	142 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\Microsoft.Windows.Photos_2019.19071.12548.0_x64__8wekyb3d8bbwe\ActivationStore.dat 0 0  

[210] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:24:27 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	139 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\Microsoft.WebMediaExtensions_1.0.20875.0_x64__8wekyb3d8bbwe\ActivationStore.dat 0 0  

[209] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:24:26 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	127 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\Microsoft.Wallet_2.4.18324.0_x64__8wekyb3d8bbwe\ActivationStore.dat 0 0  

[208] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:24:25 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	135 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\Microsoft.UI.Xaml.2.0_2.1810.18004.0_x64__8wekyb3d8bbwe\ActivationStore.dat 0 0  

[207] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:24:25 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	141 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\Microsoft.StorePurchaseApp_11811.1001.18.0_x64__8wekyb3d8bbwe\ActivationStore.dat 0 0  

[206] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:24:24 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	128 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\Microsoft.SkypeApp_14.53.77.0_x64__kzf8qxf38zg5c\ActivationStore.dat 0 0  

[205] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:24:22 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	147 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\Microsoft.Services.Store.Engagement_10.0.18101.0_x86__8wekyb3d8bbwe\ActivationStore.dat 0 0  

[204] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:24:22 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	147 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\Microsoft.Services.Store.Engagement_10.0.18101.0_x64__8wekyb3d8bbwe\ActivationStore.dat 0 0  

[203] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:24:22 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	136 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\Microsoft.ScreenSketch_10.1907.2471.0_x64__8wekyb3d8bbwe\ActivationStore.dat 0 0  

[202] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:24:21 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	129 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\Microsoft.People_10.1902.633.0_x64__8wekyb3d8bbwe\ActivationStore.dat 0 0  

[201] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:24:20 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	143 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\Microsoft.Office.OneNote_16001.12026.20112.0_x64__8wekyb3d8bbwe\ActivationStore.dat 0 0  

[200] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:24:17 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	131 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\Microsoft.MSPaint_6.1907.29027.0_x64__8wekyb3d8bbwe\ActivationStore.dat 0 0  

[199] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:24:15 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	146 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\Microsoft.MixedReality.Portal_2000.19081.1301.0_x64__8wekyb3d8bbwe\ActivationStore.dat 0 0  

[198] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:24:15 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	138 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\Microsoft.MicrosoftStickyNotes_3.6.73.0_x64__8wekyb3d8bbwe\ActivationStore.dat 0 0  

[197] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:24:14 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	148 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\Microsoft.MicrosoftSolitaireCollection_4.4.8204.0_x64__8wekyb3d8bbwe\ActivationStore.dat 0 0  

[196] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:24:13 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	142 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\Microsoft.MicrosoftOfficeHub_18.1903.1152.0_x64__8wekyb3d8bbwe\ActivationStore.dat 0 0  

[195] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:24:12 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	140 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\Microsoft.Microsoft3DViewer_6.1908.2042.0_x64__8wekyb3d8bbwe\ActivationStore.dat 0 0  

[194] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:24:10 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	131 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\Microsoft.Getstarted_8.2.22942.0_x64__8wekyb3d8bbwe\ActivationStore.dat 0 0  

[193] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:24:09 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	132 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\Microsoft.GetHelp_10.1706.13331.0_x64__8wekyb3d8bbwe\ActivationStore.dat 0 0  

[192] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:24:09 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	140 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\Microsoft.DesktopAppInstaller_1.0.30251.0_x64__8wekyb3d8bbwe\ActivationStore.dat 0 0  

[191] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:24:08 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	133 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\Microsoft.BingWeather_4.25.20211.0_x64__8wekyb3d8bbwe\ActivationStore.dat 0 0  

[190] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:24:07 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	137 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\Microsoft.Advertising.Xaml_10.1808.3.0_x64__8wekyb3d8bbwe\ActivationStore.dat 0 0  

[189] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:24:06 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	137 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\Microsoft.549981C3F5F10_1.1911.21713.0_x64__8wekyb3d8bbwe\ActivationStore.dat 0 0  

[188] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:24:06 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	137 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\Windows.PrintDialog_6.2.1.0_neutral_neutral_cw5n1h2txyewy\ActivationStore.dat 0 0  

[187] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:24:05 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	151 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\windows.immersivecontrolpanel_10.0.2.1000_neutral_neutral_cw5n1h2txyewy\ActivationStore.dat 0 0  

[186] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:24:05 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	143 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\Windows.CBSPreview_10.0.19041.423_neutral_neutral_cw5n1h2txyewy\ActivationStore.dat 0 0  

[185] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:24:05 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	137 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\NcsiUwpApp_1000.19041.423.0_neutral_neutral_8wekyb3d8bbwe\ActivationStore.dat 0 0  

[184] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:24:05 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	156 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\MicrosoftWindows.UndockedDevKit_10.0.19041.423_neutral_neutral_cw5n1h2txyewy\ActivationStore.dat 0 0  

[183] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:24:04 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	140 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\MicrosoftWindows.Client.CBS_120.2212.31.0_x64__cw5n1h2txyewy\ActivationStore.dat 0 0  

[182] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:24:04 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	155 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\Microsoft.XboxGameCallableUI_1000.19041.423.0_neutral_neutral_cw5n1h2txyewy\ActivationStore.dat 0 0  

[181] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:24:04 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	158 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\Microsoft.Windows.XGpuEjectDialog_10.0.19041.423_neutral_neutral_cw5n1h2txyewy\ActivationStore.dat 0 0  

[180] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:24:04 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	166 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\Microsoft.Windows.StartMenuExperienceHost_10.0.19041.423_neutral_neutral_cw5n1h2txyewy\ActivationStore.dat 0 0  

[179] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:24:03 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	162 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\Microsoft.Windows.ShellExperienceHost_10.0.19041.423_neutral_neutral_cw5n1h2txyewy\ActivationStore.dat 0 0  

[178] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:24:03 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	166 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\Microsoft.Windows.SecureAssessmentBrowser_10.0.19041.423_neutral_neutral_cw5n1h2txyewy\ActivationStore.dat 0 0  

[177] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:24:03 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	147 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\Microsoft.Windows.SecHealthUI_10.0.19041.423_neutral__cw5n1h2txyewy\ActivationStore.dat 0 0  

[176] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:24:02 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	147 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\Microsoft.Windows.Search_1.14.0.19041_neutral_neutral_cw5n1h2txyewy\ActivationStore.dat 0 0  

[175] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:24:02 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	163 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\Microsoft.Windows.PinningConfirmationDialog_1000.19041.423.0_neutral__cw5n1h2txyewy\ActivationStore.dat 0 0  

[174] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:24:02 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	163 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\Microsoft.Windows.PeopleExperienceHost_10.0.19041.423_neutral_neutral_cw5n1h2txyewy\ActivationStore.dat 0 0  

[173] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:24:02 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	161 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\Microsoft.Windows.ParentalControls_1000.19041.423.0_neutral_neutral_cw5n1h2txyewy\ActivationStore.dat 0 0  

[172] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:24:01 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	161 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\Microsoft.Windows.OOBENetworkConnectionFlow_10.0.19041.423_neutral__cw5n1h2txyewy\ActivationStore.dat 0 0  

[171] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:24:01 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	160 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\Microsoft.Windows.OOBENetworkCaptivePortal_10.0.19041.423_neutral__cw5n1h2txyewy\ActivationStore.dat 0 0  

[170] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:24:01 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	161 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\Microsoft.Windows.NarratorQuickStart_10.0.19041.423_neutral_neutral_8wekyb3d8bbwe\ActivationStore.dat 0 0  

[169] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:24:01 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	165 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\Microsoft.Windows.ContentDeliveryManager_10.0.19041.423_neutral_neutral_cw5n1h2txyewy\ActivationStore.dat 0 0  

[168] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:24:00 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	162 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\Microsoft.Windows.CloudExperienceHost_10.0.19041.423_neutral_neutral_cw5n1h2txyewy\ActivationStore.dat 0 0  

[167] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:24:00 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	149 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\Microsoft.Windows.CapturePicker_10.0.19041.423_neutral__cw5n1h2txyewy\ActivationStore.dat 0 0  

[166] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:24:00 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	160 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\Microsoft.Windows.CallingShellApp_1000.19041.423.0_neutral_neutral_cw5n1h2txyewy\ActivationStore.dat 0 0  

[165] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:24:00 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	166 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\Microsoft.Windows.AssignedAccessLockApp_1000.19041.423.0_neutral_neutral_cw5n1h2txyewy\ActivationStore.dat 0 0  

[164] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:59 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	158 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\Microsoft.Windows.Apprep.ChxApp_1000.19041.423.0_neutral_neutral_cw5n1h2txyewy\ActivationStore.dat 0 0  

[163] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:59 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	151 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\Microsoft.Win32WebViewHost_10.0.19041.423_neutral_neutral_cw5n1h2txyewy\ActivationStore.dat 0 0  

[162] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:59 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	35 \??\C:\Windows\system32\Config\Elam 1 1  

[161] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:59 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	141 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\Microsoft.MicrosoftEdge_44.19041.423.0_neutral__8wekyb3d8bbwe\ActivationStore.dat 0 0  

[160] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:58 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	135 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\Microsoft.LockApp_10.0.19041.423_neutral__cw5n1h2txyewy\ActivationStore.dat 0 0  

[159] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:58 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	133 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\Microsoft.ECApp_10.0.19041.423_neutral__8wekyb3d8bbwe\ActivationStore.dat 0 0  

[158] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:58 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	142 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\Microsoft.CredDialogHost_10.0.19041.423_neutral__cw5n1h2txyewy\ActivationStore.dat 0 0  

[157] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:58 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	141 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\Microsoft.BioEnrollment_10.0.19041.423_neutral__cw5n1h2txyewy\ActivationStore.dat 0 0  

[156] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:57 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	144 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\Microsoft.AsyncTextService_10.0.19041.423_neutral__8wekyb3d8bbwe\ActivationStore.dat 0 0  

[155] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:57 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	143 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\Microsoft.AccountsControl_10.0.19041.423_neutral__cw5n1h2txyewy\ActivationStore.dat 0 0  

[154] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:57 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	153 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\Microsoft.AAD.BrokerPlugin_1000.19041.423.0_neutral_neutral_cw5n1h2txyewy\ActivationStore.dat 0 0  

[153] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:57 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	161 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\F46D4000-FD22-4DB4-AC8E-4E1DDDE828FE_10.0.19041.423_neutral_neutral_cw5n1h2txyewy\ActivationStore.dat 0 0  

[152] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:57 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	161 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\E2A4F912-2574-4A75-9BB0-0D023378592B_10.0.19041.423_neutral_neutral_cw5n1h2txyewy\ActivationStore.dat 0 0  

[151] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:56 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	161 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\c5e2524a-ea46-4f67-841f-6a9465d9d515_10.0.19041.423_neutral_neutral_cw5n1h2txyewy\ActivationStore.dat 0 0  

[150] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:56 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	161 \??\C:\ProgramData\Microsoft\Windows\AppRepository\Packages\1527c705-839a-4832-9118-54d4Bd6a0c89_10.0.19041.423_neutral_neutral_cw5n1h2txyewy\ActivationStore.dat 0 0  

[149] Service Control Manager
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:55 PM   ID:       7040 
   User:     NT AUTHORITY\SYSTEM
The start type of the IKE and AuthIP IPsec Keying Modules service was changed from demand start to auto start.

[148] Microsoft-Windows-Kernel-PnP
   Type:     WARNING 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       225 
   User:     NT AUTHORITY\SYSTEM
The application \Device\HarddiskVolume2\Windows\System32\drvinst.exe with process id 4372 stopped the removal or ejection for the device ACPI\ACPI0004\0.

[147] Microsoft-Windows-Kernel-PnP
   Type:     WARNING 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       225 
   User:     NT AUTHORITY\SYSTEM
The application \Device\HarddiskVolume2\Windows\System32\drvinst.exe with process id 4360 stopped the removal or ejection for the device ACPI\ACPI0004\0.

[146] Microsoft-Windows-Kernel-PnP
   Type:     WARNING 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       225 
   User:     NT AUTHORITY\SYSTEM
The application \Device\HarddiskVolume2\Windows\System32\conhost.exe with process id 4288 stopped the removal or ejection for the device ACPI\ACPI0004\0.

[145] Microsoft-Windows-Kernel-PnP
   Type:     WARNING 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       225 
   User:     NT AUTHORITY\SYSTEM
The application \Device\HarddiskVolume2\Windows\System32\wbem\mofcomp.exe with process id 4280 stopped the removal or ejection for the device ACPI\ACPI0004\0.

[144] Microsoft-Windows-Kernel-PnP
   Type:     WARNING 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       225 
   User:     NT AUTHORITY\SYSTEM
The application \Device\HarddiskVolume2\Windows\System32\svchost.exe with process id 4172 stopped the removal or ejection for the device ACPI\ACPI0004\0.

[143] Microsoft-Windows-Kernel-PnP
   Type:     WARNING 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       225 
   User:     NT AUTHORITY\SYSTEM
The application \Device\HarddiskVolume2\Windows\System32\svchost.exe with process id 4104 stopped the removal or ejection for the device ACPI\ACPI0004\0.

[142] Microsoft-Windows-Kernel-PnP
   Type:     WARNING 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       225 
   User:     NT AUTHORITY\SYSTEM
The application \Device\HarddiskVolume2\Program Files\Windows Defender\MsMpEng.exe with process id 4056 stopped the removal or ejection for the device ACPI\ACPI0004\0.

[141] Microsoft-Windows-Kernel-PnP
   Type:     WARNING 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       225 
   User:     NT AUTHORITY\SYSTEM
The application \Device\HarddiskVolume2\Windows\System32\CExecSvc.exe with process id 4000 stopped the removal or ejection for the device ACPI\ACPI0004\0.

[140] Microsoft-Windows-Kernel-PnP
   Type:     WARNING 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       225 
   User:     NT AUTHORITY\SYSTEM
The application \Device\HarddiskVolume2\Windows\System32\wcsetupagent.exe with process id 3984 stopped the removal or ejection for the device ACPI\ACPI0004\0.

[139] Microsoft-Windows-Kernel-PnP
   Type:     WARNING 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       225 
   User:     NT AUTHORITY\SYSTEM
The application \Device\HarddiskVolume2\Windows\System32\svchost.exe with process id 3976 stopped the removal or ejection for the device ACPI\ACPI0004\0.

[138] Microsoft-Windows-Kernel-PnP
   Type:     WARNING 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       225 
   User:     NT AUTHORITY\SYSTEM
The application \Device\HarddiskVolume2\Windows\System32\svchost.exe with process id 3968 stopped the removal or ejection for the device ACPI\ACPI0004\0.

[137] Microsoft-Windows-Kernel-PnP
   Type:     WARNING 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       225 
   User:     NT AUTHORITY\SYSTEM
The application \Device\HarddiskVolume2\Windows\System32\svchost.exe with process id 3960 stopped the removal or ejection for the device ACPI\ACPI0004\0.

[136] Microsoft-Windows-Kernel-PnP
   Type:     WARNING 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       225 
   User:     NT AUTHORITY\SYSTEM
The application \Device\HarddiskVolume2\Windows\System32\svchost.exe with process id 3952 stopped the removal or ejection for the device ACPI\ACPI0004\0.

[135] Microsoft-Windows-Kernel-PnP
   Type:     WARNING 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       225 
   User:     NT AUTHORITY\SYSTEM
The application \Device\HarddiskVolume2\Windows\System32\svchost.exe with process id 3944 stopped the removal or ejection for the device ACPI\ACPI0004\0.

[134] Microsoft-Windows-Kernel-PnP
   Type:     WARNING 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       225 
   User:     NT AUTHORITY\SYSTEM
The application \Device\HarddiskVolume2\Windows\System32\svchost.exe with process id 3936 stopped the removal or ejection for the device ACPI\ACPI0004\0.

[133] Microsoft-Windows-Kernel-PnP
   Type:     WARNING 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       225 
   User:     NT AUTHORITY\SYSTEM
The application \Device\HarddiskVolume2\Windows\System32\svchost.exe with process id 3844 stopped the removal or ejection for the device ACPI\ACPI0004\0.

[132] Microsoft-Windows-Kernel-PnP
   Type:     WARNING 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       225 
   User:     NT AUTHORITY\SYSTEM
The application \Device\HarddiskVolume2\Windows\System32\svchost.exe with process id 3784 stopped the removal or ejection for the device ACPI\ACPI0004\0.

[131] Microsoft-Windows-Kernel-PnP
   Type:     WARNING 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       225 
   User:     NT AUTHORITY\SYSTEM
The application \Device\HarddiskVolume2\Windows\System32\svchost.exe with process id 3736 stopped the removal or ejection for the device ACPI\ACPI0004\0.

[130] Microsoft-Windows-Kernel-PnP
   Type:     WARNING 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       225 
   User:     NT AUTHORITY\SYSTEM
The application \Device\HarddiskVolume2\Windows\System32\spoolsv.exe with process id 3664 stopped the removal or ejection for the device ACPI\ACPI0004\0.

[129] Microsoft-Windows-Kernel-PnP
   Type:     WARNING 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       225 
   User:     NT AUTHORITY\SYSTEM
The application \Device\HarddiskVolume2\Windows\System32\svchost.exe with process id 3624 stopped the removal or ejection for the device ACPI\ACPI0004\0.

[128] Microsoft-Windows-Kernel-PnP
   Type:     WARNING 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       225 
   User:     NT AUTHORITY\SYSTEM
The application \Device\HarddiskVolume2\Windows\System32\svchost.exe with process id 3504 stopped the removal or ejection for the device ACPI\ACPI0004\0.

[127] Microsoft-Windows-Kernel-PnP
   Type:     WARNING 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       225 
   User:     NT AUTHORITY\SYSTEM
The application \Device\HarddiskVolume2\Windows\System32\svchost.exe with process id 3412 stopped the removal or ejection for the device ACPI\ACPI0004\0.

[126] Microsoft-Windows-Kernel-PnP
   Type:     WARNING 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       225 
   User:     NT AUTHORITY\SYSTEM
The application \Device\HarddiskVolume2\Windows\System32\svchost.exe with process id 3404 stopped the removal or ejection for the device ACPI\ACPI0004\0.

[125] Microsoft-Windows-Kernel-PnP
   Type:     WARNING 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       225 
   User:     NT AUTHORITY\SYSTEM
The application \Device\HarddiskVolume2\Windows\System32\svchost.exe with process id 3396 stopped the removal or ejection for the device ACPI\ACPI0004\0.

[124] Microsoft-Windows-Kernel-PnP
   Type:     WARNING 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       225 
   User:     NT AUTHORITY\SYSTEM
The application \Device\HarddiskVolume2\Windows\System32\svchost.exe with process id 3388 stopped the removal or ejection for the device ACPI\ACPI0004\0.

[123] Microsoft-Windows-Kernel-PnP
   Type:     WARNING 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       225 
   User:     NT AUTHORITY\SYSTEM
The application \Device\HarddiskVolume2\Windows\System32\svchost.exe with process id 3292 stopped the removal or ejection for the device ACPI\ACPI0004\0.

[122] Microsoft-Windows-Kernel-PnP
   Type:     WARNING 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       225 
   User:     NT AUTHORITY\SYSTEM
The application \Device\HarddiskVolume2\Windows\System32\svchost.exe with process id 3212 stopped the removal or ejection for the device ACPI\ACPI0004\0.

[121] Microsoft-Windows-Kernel-PnP
   Type:     WARNING 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       225 
   User:     NT AUTHORITY\SYSTEM
The application \Device\HarddiskVolume2\Windows\System32\svchost.exe with process id 3164 stopped the removal or ejection for the device ACPI\ACPI0004\0.

[120] Microsoft-Windows-Kernel-PnP
   Type:     WARNING 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       225 
   User:     NT AUTHORITY\SYSTEM
The application \Device\HarddiskVolume2\Windows\System32\svchost.exe with process id 3152 stopped the removal or ejection for the device ACPI\ACPI0004\0.

[119] Microsoft-Windows-Kernel-PnP
   Type:     WARNING 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       225 
   User:     NT AUTHORITY\SYSTEM
The application \Device\HarddiskVolume2\Windows\System32\svchost.exe with process id 3104 stopped the removal or ejection for the device ACPI\ACPI0004\0.

[118] Microsoft-Windows-Kernel-PnP
   Type:     WARNING 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       225 
   User:     NT AUTHORITY\SYSTEM
The application \Device\HarddiskVolume2\Windows\System32\svchost.exe with process id 3028 stopped the removal or ejection for the device ACPI\ACPI0004\0.

[117] Microsoft-Windows-Kernel-PnP
   Type:     WARNING 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       225 
   User:     NT AUTHORITY\SYSTEM
The application \Device\HarddiskVolume2\Windows\System32\svchost.exe with process id 2964 stopped the removal or ejection for the device ACPI\ACPI0004\0.

[116] Microsoft-Windows-Kernel-PnP
   Type:     WARNING 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       225 
   User:     NT AUTHORITY\SYSTEM
The application \Device\HarddiskVolume2\Windows\servicing\TrustedInstaller.exe with process id 2904 stopped the removal or ejection for the device ACPI\ACPI0004\0.

[115] Microsoft-Windows-Kernel-PnP
   Type:     WARNING 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       225 
   User:     NT AUTHORITY\SYSTEM
The application \Device\HarddiskVolume2\Windows\System32\svchost.exe with process id 2888 stopped the removal or ejection for the device ACPI\ACPI0004\0.

[114] Microsoft-Windows-Kernel-PnP
   Type:     WARNING 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       225 
   User:     NT AUTHORITY\SYSTEM
The application \Device\HarddiskVolume2\Windows\System32\svchost.exe with process id 2876 stopped the removal or ejection for the device ACPI\ACPI0004\0.

[113] Microsoft-Windows-Kernel-PnP
   Type:     WARNING 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       225 
   User:     NT AUTHORITY\SYSTEM
The application \Device\HarddiskVolume2\Windows\System32\svchost.exe with process id 2868 stopped the removal or ejection for the device ACPI\ACPI0004\0.

[112] Microsoft-Windows-Kernel-PnP
   Type:     WARNING 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       225 
   User:     NT AUTHORITY\SYSTEM
The application \Device\HarddiskVolume2\Windows\System32\svchost.exe with process id 2860 stopped the removal or ejection for the device ACPI\ACPI0004\0.

[111] Microsoft-Windows-Kernel-PnP
   Type:     WARNING 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       225 
   User:     NT AUTHORITY\SYSTEM
The application \Device\HarddiskVolume2\Windows\System32\svchost.exe with process id 2852 stopped the removal or ejection for the device ACPI\ACPI0004\0.

[110] Microsoft-Windows-Kernel-PnP
   Type:     WARNING 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       225 
   User:     NT AUTHORITY\SYSTEM
The application \Device\HarddiskVolume2\Windows\System32\VSSVC.exe with process id 2800 stopped the removal or ejection for the device ACPI\ACPI0004\0.

[109] Microsoft-Windows-Kernel-PnP
   Type:     WARNING 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       225 
   User:     NT AUTHORITY\SYSTEM
The application \Device\HarddiskVolume2\Windows\System32\svchost.exe with process id 2588 stopped the removal or ejection for the device ACPI\ACPI0004\0.

[108] Microsoft-Windows-Kernel-PnP
   Type:     WARNING 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       225 
   User:     NT AUTHORITY\SYSTEM
The application \Device\HarddiskVolume2\Windows\System32\svchost.exe with process id 2580 stopped the removal or ejection for the device ACPI\ACPI0004\0.

[107] Microsoft-Windows-Kernel-PnP
   Type:     WARNING 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       225 
   User:     NT AUTHORITY\SYSTEM
The application \Device\HarddiskVolume2\Windows\System32\svchost.exe with process id 2556 stopped the removal or ejection for the device ACPI\ACPI0004\0.

[106] Microsoft-Windows-Kernel-PnP
   Type:     WARNING 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       225 
   User:     NT AUTHORITY\SYSTEM
The application \Device\HarddiskVolume2\Windows\System32\svchost.exe with process id 2512 stopped the removal or ejection for the device ACPI\ACPI0004\0.

[105] Microsoft-Windows-Kernel-PnP
   Type:     WARNING 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       225 
   User:     NT AUTHORITY\SYSTEM
The application \Device\HarddiskVolume2\Windows\System32\svchost.exe with process id 2484 stopped the removal or ejection for the device ACPI\ACPI0004\0.

[104] Microsoft-Windows-Kernel-PnP
   Type:     WARNING 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       225 
   User:     NT AUTHORITY\SYSTEM
The application \Device\HarddiskVolume2\Windows\System32\svchost.exe with process id 2464 stopped the removal or ejection for the device ACPI\ACPI0004\0.

[103] Microsoft-Windows-Kernel-PnP
   Type:     WARNING 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       225 
   User:     NT AUTHORITY\SYSTEM
The application \Device\HarddiskVolume2\Windows\System32\svchost.exe with process id 2456 stopped the removal or ejection for the device ACPI\ACPI0004\0.

[102] Microsoft-Windows-Kernel-PnP
   Type:     WARNING 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       225 
   User:     NT AUTHORITY\SYSTEM
The application \Device\HarddiskVolume2\Windows\System32\svchost.exe with process id 2436 stopped the removal or ejection for the device ACPI\ACPI0004\0.

[101] Microsoft-Windows-Kernel-PnP
   Type:     WARNING 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       225 
   User:     NT AUTHORITY\SYSTEM
The application \Device\HarddiskVolume2\Windows\System32\svchost.exe with process id 2360 stopped the removal or ejection for the device ACPI\ACPI0004\0.

[100] Microsoft-Windows-Kernel-PnP
   Type:     WARNING 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       225 
   User:     NT AUTHORITY\SYSTEM
The application \Device\HarddiskVolume2\Windows\System32\svchost.exe with process id 2316 stopped the removal or ejection for the device ACPI\ACPI0004\0.

[099] Microsoft-Windows-Kernel-PnP
   Type:     WARNING 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       225 
   User:     NT AUTHORITY\SYSTEM
The application \Device\HarddiskVolume2\Windows\System32\secinit.exe with process id 2228 stopped the removal or ejection for the device ACPI\ACPI0004\0.

[098] Microsoft-Windows-Kernel-PnP
   Type:     WARNING 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       225 
   User:     NT AUTHORITY\SYSTEM
The application \Device\HarddiskVolume2\Windows\System32\oobe\Setup.exe with process id 2184 stopped the removal or ejection for the device ACPI\ACPI0004\0.

[097] Microsoft-Windows-Kernel-PnP
   Type:     WARNING 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       225 
   User:     NT AUTHORITY\SYSTEM
The application \Device\HarddiskVolume2\Windows\System32\oobe\windeploy.exe with process id 2156 stopped the removal or ejection for the device ACPI\ACPI0004\0.

[096] Microsoft-Windows-Kernel-PnP
   Type:     WARNING 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       225 
   User:     NT AUTHORITY\SYSTEM
The application \Device\HarddiskVolume2\Windows\System32\svchost.exe with process id 2068 stopped the removal or ejection for the device ACPI\ACPI0004\0.

[095] Microsoft-Windows-Kernel-PnP
   Type:     WARNING 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       225 
   User:     NT AUTHORITY\SYSTEM
The application \Device\HarddiskVolume2\Windows\System32\svchost.exe with process id 2044 stopped the removal or ejection for the device ACPI\ACPI0004\0.

[094] Microsoft-Windows-Kernel-PnP
   Type:     WARNING 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       225 
   User:     NT AUTHORITY\SYSTEM
The application \Device\HarddiskVolume2\Windows\System32\svchost.exe with process id 2008 stopped the removal or ejection for the device ACPI\ACPI0004\0.

[093] Microsoft-Windows-Kernel-PnP
   Type:     WARNING 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       225 
   User:     NT AUTHORITY\SYSTEM
The application \Device\HarddiskVolume2\Windows\System32\sppsvc.exe with process id 1964 stopped the removal or ejection for the device ACPI\ACPI0004\0.

[092] Microsoft-Windows-Kernel-PnP
   Type:     WARNING 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       225 
   User:     NT AUTHORITY\SYSTEM
The application \Device\HarddiskVolume2\Windows\System32\svchost.exe with process id 1920 stopped the removal or ejection for the device ACPI\ACPI0004\0.

[091] Microsoft-Windows-Kernel-PnP
   Type:     WARNING 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       225 
   User:     NT AUTHORITY\SYSTEM
The application \Device\HarddiskVolume2\Windows\System32\svchost.exe with process id 1880 stopped the removal or ejection for the device ACPI\ACPI0004\0.

[090] Microsoft-Windows-Kernel-PnP
   Type:     WARNING 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       225 
   User:     NT AUTHORITY\SYSTEM
The application \Device\HarddiskVolume2\Windows\System32\fontdrvhost.exe with process id 1804 stopped the removal or ejection for the device ACPI\ACPI0004\0.

[089] Microsoft-Windows-Kernel-PnP
   Type:     WARNING 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       225 
   User:     NT AUTHORITY\SYSTEM
The application \Device\HarddiskVolume2\Windows\System32\fontdrvhost.exe with process id 1788 stopped the removal or ejection for the device ACPI\ACPI0004\0.

[088] Microsoft-Windows-Kernel-PnP
   Type:     WARNING 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       225 
   User:     NT AUTHORITY\SYSTEM
The application \Device\HarddiskVolume2\Windows\System32\svchost.exe with process id 1764 stopped the removal or ejection for the device ACPI\ACPI0004\0.

[087] Microsoft-Windows-Kernel-PnP
   Type:     WARNING 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       225 
   User:     NT AUTHORITY\SYSTEM
The application \Device\HarddiskVolume2\Windows\System32\svchost.exe with process id 1740 stopped the removal or ejection for the device ACPI\ACPI0004\0.

[086] Microsoft-Windows-Kernel-PnP
   Type:     WARNING 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       225 
   User:     NT AUTHORITY\SYSTEM
The application \Device\HarddiskVolume2\Windows\System32\lsass.exe with process id 1620 stopped the removal or ejection for the device ACPI\ACPI0004\0.

[085] Microsoft-Windows-Kernel-PnP
   Type:     WARNING 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       225 
   User:     NT AUTHORITY\SYSTEM
The application \Device\HarddiskVolume2\Windows\System32\services.exe with process id 1600 stopped the removal or ejection for the device ACPI\ACPI0004\0.

[084] Microsoft-Windows-Kernel-PnP
   Type:     WARNING 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       225 
   User:     NT AUTHORITY\SYSTEM
The application \Device\HarddiskVolume2\Windows\System32\svchost.exe with process id 1596 stopped the removal or ejection for the device ACPI\ACPI0004\0.

[083] Microsoft-Windows-Kernel-PnP
   Type:     WARNING 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       225 
   User:     NT AUTHORITY\SYSTEM
The application \Device\HarddiskVolume2\Windows\System32\winlogon.exe with process id 1556 stopped the removal or ejection for the device ACPI\ACPI0004\0.

[082] Microsoft-Windows-Kernel-PnP
   Type:     WARNING 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       225 
   User:     NT AUTHORITY\SYSTEM
The application \Device\HarddiskVolume2\Windows\System32\csrss.exe with process id 1472 stopped the removal or ejection for the device ACPI\ACPI0004\0.

[081] Microsoft-Windows-Kernel-PnP
   Type:     WARNING 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       225 
   User:     NT AUTHORITY\SYSTEM
The application \Device\HarddiskVolume2\Windows\System32\wininit.exe with process id 1456 stopped the removal or ejection for the device ACPI\ACPI0004\0.

[080] Microsoft-Windows-Kernel-PnP
   Type:     WARNING 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       225 
   User:     NT AUTHORITY\SYSTEM
The application \Device\HarddiskVolume2\Windows\System32\svchost.exe with process id 1396 stopped the removal or ejection for the device ACPI\ACPI0004\0.

[079] Microsoft-Windows-Kernel-PnP
   Type:     WARNING 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       225 
   User:     NT AUTHORITY\SYSTEM
The application \Device\HarddiskVolume2\Windows\System32\csrss.exe with process id 1352 stopped the removal or ejection for the device ACPI\ACPI0004\0.

[078] Microsoft-Windows-Kernel-PnP
   Type:     WARNING 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       225 
   User:     NT AUTHORITY\SYSTEM
The application \Device\HarddiskVolume2\Windows\System32\dwm.exe with process id 1248 stopped the removal or ejection for the device ACPI\ACPI0004\0.

[077] Microsoft-Windows-Kernel-PnP
   Type:     WARNING 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       225 
   User:     NT AUTHORITY\SYSTEM
The application \Device\HarddiskVolume2\Windows\System32\smss.exe with process id 1228 stopped the removal or ejection for the device ACPI\ACPI0004\0.

[076] Microsoft-Windows-Kernel-PnP
   Type:     WARNING 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       225 
   User:     NT AUTHORITY\SYSTEM
The application System with process id 4 stopped the removal or ejection for the device ACPI\ACPI0004\0.

[075] Service Control Manager
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       7026 
The following boot-start or system-start driver(s) did not load: 
CSC
dam

[074] Service Control Manager
   Type:     ERROR 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       7023 
The netprofm service terminated with the following error: 
%%21

[073] Microsoft-Windows-DHCPv6-Client
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       51046 
   User:     NT AUTHORITY\LOCAL SERVICE
DHCPv6 client service is started

[072] Microsoft-Windows-Dhcp-Client
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       50103 
   User:     NT AUTHORITY\LOCAL SERVICE
DHCPv4 client registered for shutdown notification

[071] Microsoft-Windows-Dhcp-Client
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       50036 
   User:     NT AUTHORITY\LOCAL SERVICE
DHCPv4 client service is started

[070] Microsoft-Windows-FilterManager
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       6 
   User:     NT AUTHORITY\SYSTEM
File System Filter 'bindflt' (10.0, 2006-02-06T13:00:56.0000000Z) has successfully loaded and registered with Filter Manager.

[069] Microsoft-Windows-FilterManager
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       6 
   User:     NT AUTHORITY\SYSTEM
File System Filter 'storqosflt' (10.0, 2007-04-09T11:08:30.0000000Z) has successfully loaded and registered with Filter Manager.

[068] Microsoft-Windows-FilterManager
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       6 
   User:     NT AUTHORITY\SYSTEM
File System Filter 'CldFlt' (10.0, 2003-03-20T16:36:50.0000000Z) has successfully loaded and registered with Filter Manager.

[067] Microsoft-Windows-FilterManager
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       1 
   User:     NT AUTHORITY\SYSTEM
File System Filter 'CldFlt' (Version 10.0, 2003-03-20T16:36:50.0000000Z) unloaded successfully.

[066] Microsoft-Windows-FilterManager
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       6 
   User:     NT AUTHORITY\SYSTEM
File System Filter 'CldFlt' (10.0, 2003-03-20T16:36:50.0000000Z) has successfully loaded and registered with Filter Manager.

[065] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       1 
   User:     NT AUTHORITY\LOCAL SERVICE
Possible detection of CVE: 2020-09-06T21:23:54.4020000Z
Additional Information: 2020-09-06T21:23:52.4095216Z
  This Event is generated when an attempt to exploit a known vulnerability (2020-09-06T21:23:54.4020000Z) is detected.
This Event is raised by a User mode process.
  
[064] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       24 
   User:     NT AUTHORITY\LOCAL SERVICE
Message text not available.  Insertion strings:
	0 420 2 0 0  

[063] Microsoft-Windows-FilterManager
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:52 PM   ID:       6 
   User:     NT AUTHORITY\SYSTEM
File System Filter 'wcifs' (10.0, 1971-08-10T04:27:38.0000000Z) has successfully loaded and registered with Filter Manager.

[062] Service Control Manager
   Type:     ERROR 
   Computer: Default-PC
   Time:     9/6/2020 5:23:52 PM   ID:       7000 
The luafv service failed to start due to the following error: 
%%1275

[061] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:52 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	31 \SystemRoot\System32\Config\BBI 1 1  

[060] Microsoft-Windows-Directory-Services-SAM
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:51 PM   ID:       16977 
   User:     NT AUTHORITY\SYSTEM
The domain is configured with the following minimum password length-related settings.
  MinimumPasswordLength: 0
  RelaxMinimumPasswordLengthLimits: 0
  MinimumPasswordLengthAudit: -1
  For more information see https://go.microsoft.com/fwlink/?LinkId=2097191.
  
[059] Workstation
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       3261 
This computer has been successfully joined to workgroup 'WORKGROUP'.

[058] Microsoft-Windows-Directory-Services-SAM
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:46 PM   ID:       16977 
   User:     NT AUTHORITY\SYSTEM
The domain is configured with the following minimum password length-related settings.
  MinimumPasswordLength: 0
  RelaxMinimumPasswordLengthLimits: 0
  MinimumPasswordLengthAudit: -1
  For more information see https://go.microsoft.com/fwlink/?LinkId=2097191.
  
[057] Microsoft-Windows-Directory-Services-SAM
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:46 PM   ID:       16962 
   User:     NT AUTHORITY\SYSTEM
Remote calls to the SAM database are being restricted using the default security descriptor: O:SYG:SYD:(A;;RC;;;BA).
For more information please see http://go.microsoft.com/fwlink/?LinkId=787651.

[056] Microsoft-Windows-Wininit
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:46 PM   ID:       14 
   User:     NT AUTHORITY\SYSTEM
Credential Guard configuration: 0, 0

[055] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:39 PM   ID:       24 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	0 420 2 0 0  

[054] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:38 PM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 35 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2300
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[053] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:38 PM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 34 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2300
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[052] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:38 PM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 33 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2300
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[051] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:38 PM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 32 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2300
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[050] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:38 PM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 31 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2300
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[049] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:38 PM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 30 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2300
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[048] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:38 PM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 29 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2300
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[047] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:38 PM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 28 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2300
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[046] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:38 PM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 27 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2300
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[045] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:38 PM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 26 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2300
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[044] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:38 PM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 25 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2300
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[043] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:38 PM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 24 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2300
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[042] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:38 PM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 23 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2300
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[041] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:38 PM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 22 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2300
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[040] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:38 PM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 21 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2300
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[039] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:38 PM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 20 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2300
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[038] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:38 PM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 19 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2300
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[037] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:38 PM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 18 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2300
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[036] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:38 PM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 17 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2300
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[035] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:38 PM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 16 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2300
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[034] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:38 PM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 15 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2300
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[033] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:38 PM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 14 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2300
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[032] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:38 PM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 13 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2300
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[031] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:38 PM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 12 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2300
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[030] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:38 PM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 11 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2300
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[029] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:38 PM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 10 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2300
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[028] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:38 PM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 9 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2300
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[027] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:38 PM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 8 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2300
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[026] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:38 PM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 7 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2300
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[025] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:38 PM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 6 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2300
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[024] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:38 PM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 5 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2300
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[023] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:38 PM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 4 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2300
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[022] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:38 PM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 3 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2300
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[021] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:38 PM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 2 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2300
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[020] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:38 PM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 1 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2300
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[019] Microsoft-Windows-Kernel-Processor-Power
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:38 PM   ID:       55 
   User:     NT AUTHORITY\SYSTEM
Hyper-V logical processor 0 exposes the following power management capabilities:
  Idle state type: 1 (1 state(s))
  Performance state type: 0
Nominal Frequency (MHz): 2300
Maximum performance percentage: 100
Minimum performance percentage: 100
Minimum throttle percentage: 100

[018] Microsoft-Windows-Kernel-Power
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:38 PM   ID:       172 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	2 6  

[017] Microsoft-Windows-FilterManager
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:38 PM   ID:       6 
   User:     NT AUTHORITY\SYSTEM
File System Filter 'npsvctrig' (10.0, 2025-01-05T19:41:12.0000000Z) has successfully loaded and registered with Filter Manager.

[016] Microsoft-Windows-FilterManager
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:38 PM   ID:       6 
   User:     NT AUTHORITY\SYSTEM
File System Filter 'FileCrypt' (10.0, 2002-03-01T04:12:42.0000000Z) has successfully loaded and registered with Filter Manager.

[015] Microsoft-Windows-Ntfs
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:38 PM   ID:       98 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	\\?\Volume{2e8c6d8b-790b-41c9-95d7-0f93286c694b} \Device\HarddiskVolume2 0  

[014] Microsoft-Windows-FilterManager
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:37 PM   ID:       6 
   User:     NT AUTHORITY\SYSTEM
File System Filter 'WdFilter' (10.0, 2066-04-08T21:52:09.0000000Z) has successfully loaded and registered with Filter Manager.

[013] Microsoft-Windows-FilterManager
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:37 PM   ID:       6 
   User:     NT AUTHORITY\SYSTEM
File System Filter 'Wof' (10.0, 2050-10-18T06:21:08.0000000Z) has successfully loaded and registered with Filter Manager.

[012] Microsoft-Windows-FilterManager
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:37 PM   ID:       6 
   User:     NT AUTHORITY\SYSTEM
File System Filter 'FileInfo' (10.0, 2062-12-22T22:21:06.0000000Z) has successfully loaded and registered with Filter Manager.

[011] Microsoft-Windows-HAL
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:37 PM   ID:       16 
   User:     NT AUTHORITY\SYSTEM
The iommu fault reporting has been initialized.

[010] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:37 PM   ID:       20 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	0 true 0 0  

[009] Microsoft-Windows-Kernel-Boot
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:37 PM   ID:       32 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	0  

[008] Microsoft-Windows-Kernel-Boot
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:37 PM   ID:       18 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	1  

[007] Microsoft-Windows-Kernel-Boot
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:37 PM   ID:       27 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	0  NOEXECUTE=OPTIN  NOVGA  

[006] Microsoft-Windows-Kernel-Boot
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:37 PM   ID:       25 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	1  

[005] Microsoft-Windows-Kernel-Boot
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:37 PM   ID:       238 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	2047 0  

[004] Microsoft-Windows-Kernel-Boot
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:37 PM   ID:       153 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	0 0 0  

[003] EventLog
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       6005 
The Event log service was started.

[002] EventLog
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:54 PM   ID:       6009 
Microsoft (R) Windows (R) 10.00. 19041 ? Multiprocessor Free.

[001] Microsoft-Windows-Kernel-General
   Type:     INFORMATION 
   Computer: Default-PC
   Time:     9/6/2020 5:23:37 PM   ID:       12 
   User:     NT AUTHORITY\SYSTEM
Message text not available.  Insertion strings:
	10 0 19041 508 0 0 2020-09-06T21:23:37.5000000Z  


```

### Usage (stderr):
```cmhg
The system cannot find the file specified.
Could not open the specified event log Registry key on 37AACD8D-548A-4:

```

### Loaded Modules:

Path |
-- |
C:\SysinternalsSuite\psloglist.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001B1DDEDBA54E965B85F0001000001B1`
* Thumbprint: `9DC17888B5CFAD98B3CB35C1994E96227F061675`
* Issuer: CN=Microsoft Code Signing PCA, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: psloglist.exe
* Product Name: Sysinternals PsLogList
* Company Name: Sysinternals - www.sysinternals.com
* File Version: 2.81
* Product Version: 2.81
* Language: English (United States)
* Legal Copyright: Copyright (C) 2000-2019 Mark Russinovich
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/57dc27269669402152518dc7683e0a9cc372a3c3125efe1c7ecd8e8516f556f3/detection/





MIT License. Copyright (c) 2020 Strontic.


