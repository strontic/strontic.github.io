---
title: PsService.exe | Service information and configuration utility
excerpt: What is PsService.exe?
---

# PsService.exe 

* File Path: `C:\SysinternalsSuite\PsService.exe`
* Description: Service information and configuration utility

## Hashes

Type | Hash
-- | --
MD5 | `02FE68328F96FEE688DA5885EB4C3CF0`
SHA1 | `0DB6B656AB0505903BC47F47E63E3451A93F41E1`
SHA256 | `9454BA56BCB470D330559573AFBC10F6989BA46F3E656C20979DE6F92E051752`
SHA384 | `F8462FEE57C11BB02C807BBCE5B7174E39BFD0B0072AFE3447AF611BB7381518C134E9EFD552CD99FDC3425182233555`
SHA512 | `1B64F0246C539B72D7F8B0098EA8647DE58BDD985BB2D646CBB45BA33F80CB3DEB8A7421E9801E2DA1CC2D55819E5DB7E527C7D996997F245CE494DB3D25B0F3`
SSDEEP | `3072:Ubk+b/Lx7nourckixvwRzDW/ZUFiasDkLsIJxw0umJPFpWE0XoK:9CtRXWiJiTm56oK`
IMP | `C0AEC3871D899CFE05E4110234641E7F`
PESHA1 | `396962564462FBC5943D8D2DE84656046DC8DD46`
PE256 | `A62B47AB05F8EAC1C735C4CFD774035E32BA0DFB697612031BEA6F6B8CBEAA44`

## Runtime Data

### Usage (stdout):
```cmhg

PsService v2.25 - Service information and configuration utility
Copyright (C) 2001-2010 Mark Russinovich
Sysinternals - www.sysinternals.com

SERVICE_NAME: AJRouter
DISPLAY_NAME: AllJoyn Router Service
Routes AllJoyn messages for the local AllJoyn clients. If this service is stopped the AllJoyn clients that do not have their own bundled routers will be unable to run.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: ALG
DISPLAY_NAME: Application Layer Gateway Service
Provides support for 3rd party protocol plug-ins for Internet Connection Sharing
	TYPE		  : 10 WIN32_OWN_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: AppIDSvc
DISPLAY_NAME: Application Identity
Determines and verifies the identity of an application. Disabling this service will prevent AppLocker from being enforced.
	GROUP		  : ProfSvc_Group
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: Appinfo
DISPLAY_NAME: Application Information
Facilitates the running of interactive applications with additional administrative privileges.  If this service is stopped, users will be unable to launch applications with the additional administrative privileges they may require to perform desired user tasks.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: AppMgmt
DISPLAY_NAME: Application Management
Processes installation, removal, and enumeration requests for software deployed through Group Policy. If the service is disabled, users will be unable to install, remove, or enumerate software deployed through Group Policy. If this service is disabled, any services that explicitly depend on it will fail to start.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: AppReadiness
DISPLAY_NAME: App Readiness
Gets apps ready for use the first time a user signs in to this PC and when adding new apps.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: AppVClient
DISPLAY_NAME: Microsoft App-V Client
Manages App-V users and virtual applications
	TYPE		  : 10 WIN32_OWN_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: AppXSvc
DISPLAY_NAME: AppX Deployment Service (AppXSVC)
Provides infrastructure support for deploying Store applications. This service is started on demand and if disabled Store applications will not be deployed to the system, and may not function properly.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: AssignedAccessManagerSvc
DISPLAY_NAME: AssignedAccessManager Service
AssignedAccessManager Service supports kiosk experience in Windows.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: AudioEndpointBuilder
DISPLAY_NAME: Windows Audio Endpoint Builder
Manages audio devices for the Windows Audio service.  If this service is stopped, audio devices and effects will not function properly.  If this service is disabled, any services that explicitly depend on it will fail to start
	GROUP		  : AudioGroup
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 4  RUNNING
			       (STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: Audiosrv
DISPLAY_NAME: Windows Audio
Manages audio for Windows-based programs.  If this service is stopped, audio devices and effects will not function properly.  If this service is disabled, any services that explicitly depend on it will fail to start
	GROUP		  : AudioGroup
	TYPE		  : 10 WIN32_OWN_PROCESS 
	STATE		  : 4  RUNNING
			       (STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: autotimesvc
DISPLAY_NAME: Cellular Time
This service sets time based on NITZ messages from a Mobile Network
	TYPE		  : 10 WIN32_OWN_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: AxInstSV
DISPLAY_NAME: ActiveX Installer (AxInstSV)
Provides User Account Control validation for the installation of ActiveX controls from the Internet and enables management of ActiveX control installation based on Group Policy settings. This service is started on demand and if disabled the installation of ActiveX controls will behave according to default browser settings.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: BDESVC
DISPLAY_NAME: BitLocker Drive Encryption Service
BDESVC hosts the BitLocker Drive Encryption service. BitLocker Drive Encryption provides secure startup for the operating system, as well as full volume encryption for OS, fixed or removable volumes. This service allows BitLocker to prompt users for various actions related to their volumes when mounted, and unlocks volumes automatically without user interaction. Additionally, it stores recovery information to Active Directory, if available, and, if necessary, ensures the most recent recovery certificates are used.  Stopping or disabling the service would prevent users from leveraging this functionality.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: BFE
DISPLAY_NAME: Base Filtering Engine
The Base Filtering Engine (BFE) is a service that manages firewall and Internet Protocol security (IPsec) policies and implements user mode filtering. Stopping or disabling the BFE service will significantly reduce the security of the system. It will also result in unpredictable behavior in IPsec management and firewall applications.
	GROUP		  : NetworkProvider
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 4  RUNNING
			       (STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: BITS
DISPLAY_NAME: Background Intelligent Transfer Service
Transfers files in the background using idle network bandwidth. If the service is disabled, then any applications that depend on BITS, such as Windows Update or MSN Explorer, will be unable to automatically download programs and other information.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: BrokerInfrastructure
DISPLAY_NAME: Background Tasks Infrastructure Service
Windows infrastructure service that controls which background tasks can run on the system.
	GROUP		  : COM Infrastructure
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 4  RUNNING
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: BTAGService
DISPLAY_NAME: Bluetooth Audio Gateway Service
Service supporting the audio gateway role of the Bluetooth Handsfree Profile.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: BthAvctpSvc
DISPLAY_NAME: AVCTP service
This is Audio Video Control Transport Protocol service
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: bthserv
DISPLAY_NAME: Bluetooth Support Service
The Bluetooth service supports discovery and association of remote Bluetooth devices.  Stopping or disabling this service may cause already installed Bluetooth devices to fail to operate properly and prevent new devices from being discovered or associated.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: camsvc
DISPLAY_NAME: Capability Access Manager Service
Provides facilities for managing UWP apps access to app capabilities as well as checking an app's access to specific app capabilities
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: CDPSvc
DISPLAY_NAME: Connected Devices Platform Service
This service is used for Connected Devices Platform scenarios
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 4  RUNNING
			       (STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: CertPropSvc
DISPLAY_NAME: Certificate Propagation
Copies user certificates and root certificates from smart cards into the current user's certificate store, detects when a smart card is inserted into a smart card reader, and, if needed, installs the smart card Plug and Play minidriver.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: cexecsvc
DISPLAY_NAME: Container Execution Agent
Provides support for executing commands in a Windows Containers.
	TYPE		  : 10 WIN32_OWN_PROCESS 
	STATE		  : 4  RUNNING
			       (STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: ClipSVC
DISPLAY_NAME: Client License Service (ClipSVC)
Provides infrastructure support for the Microsoft Store. This service is started on demand and if disabled applications bought using Windows Store will not behave correctly.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: COMSysApp
DISPLAY_NAME: COM+ System Application
Manages the configuration and tracking of Component Object Model (COM)+-based components. If the service is stopped, most COM+-based components will not function properly. If this service is disabled, any services that explicitly depend on it will fail to start.
	TYPE		  : 10 WIN32_OWN_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: CoreMessagingRegistrar
DISPLAY_NAME: CoreMessaging
Manages communication between system components.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 4  RUNNING
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: CryptSvc
DISPLAY_NAME: Cryptographic Services
Provides three management services: Catalog Database Service, which confirms the signatures of Windows files and allows new programs to be installed; Protected Root Service, which adds and removes Trusted Root Certification Authority certificates from this computer; and Automatic Root Certificate Update Service, which retrieves root certificates from Windows Update and enable scenarios such as SSL. If this service is stopped, these management services will not function properly. If this service is disabled, any services that explicitly depend on it will fail to start.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 4  RUNNING
			       (STOPPABLE,NOT_PAUSABLE,ACCEPTS_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: CscService
DISPLAY_NAME: Offline Files
The Offline Files service performs maintenance activities on the Offline Files cache, responds to user logon and logoff events, implements the internals of the public API, and dispatches interesting events to those interested in Offline Files activities and changes in cache state.
	GROUP		  : ProfSvc_Group
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: DcomLaunch
DISPLAY_NAME: DCOM Server Process Launcher
The DCOMLAUNCH service launches COM and DCOM servers in response to object activation requests. If this service is stopped or disabled, programs using COM or DCOM will not function properly. It is strongly recommended that you have the DCOMLAUNCH service running.
	GROUP		  : COM Infrastructure
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 4  RUNNING
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: defragsvc
DISPLAY_NAME: Optimize drives
Helps the computer run more efficiently by optimizing files on storage drives.
	TYPE		  : 10 WIN32_OWN_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: DeviceAssociationService
DISPLAY_NAME: Device Association Service
Enables pairing between the system and wired or wireless devices.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: DeviceInstall
DISPLAY_NAME: Device Install Service
Enables a computer to recognize and adapt to hardware changes with little or no user input. Stopping or disabling this service will result in system instability.
	GROUP		  : PlugPlay
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: DevQueryBroker
DISPLAY_NAME: DevQuery Background Discovery Broker
Enables apps to discover devices with a backgroud task
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: Dhcp
DISPLAY_NAME: DHCP Client
Registers and updates IP addresses and DNS records for this computer. If this service is stopped, this computer will not receive dynamic IP addresses and DNS updates. If this service is disabled, any services that explicitly depend on it will fail to start.
	GROUP		  : TDI
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 4  RUNNING
			       (STOPPABLE,NOT_PAUSABLE,ACCEPTS_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: diagnosticshub.standardcollector.service
DISPLAY_NAME: Microsoft (R) Diagnostics Hub Standard Collector Service
Diagnostics Hub Standard Collector Service. When running, this service collects real time ETW events and processes them.
	TYPE		  : 10 WIN32_OWN_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: diagsvc
DISPLAY_NAME: Diagnostic Execution Service
Executes diagnostic actions for troubleshooting support
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: DiagTrack
DISPLAY_NAME: Connected User Experiences and Telemetry
The Connected User Experiences and Telemetry service enables features that support in-application and connected user experiences. Additionally, this service manages the event driven collection and transmission of diagnostic and usage information (used to improve the experience and quality of the Windows Platform) when the diagnostics and usage privacy option settings are enabled under Feedback and Diagnostics.
	TYPE		  : 10 WIN32_OWN_PROCESS 
	STATE		  : 4  RUNNING
			       (STOPPABLE,NOT_PAUSABLE,ACCEPTS_PRESHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: DispBrokerDesktopSvc
DISPLAY_NAME: Display Policy Service
Manages the connection and configuration of local and remote displays
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 4  RUNNING
			       (STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: DisplayEnhancementService
DISPLAY_NAME: Display Enhancement Service
A service for managing display enhancement such as brightness control.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: DmEnrollmentSvc
DISPLAY_NAME: Device Management Enrollment Service
Performs Device Enrollment Activities for Device Management
	TYPE		  : 10 WIN32_OWN_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: dmwappushservice
DISPLAY_NAME: Device Management Wireless Application Protocol (WAP) Push message Routing Service
Routes Wireless Application Protocol (WAP) Push messages received by the device and synchronizes Device Management sessions
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: Dnscache
DISPLAY_NAME: DNS Client
The DNS Client service (dnscache) caches Domain Name System (DNS) names and registers the full computer name for this computer. If the service is stopped, DNS names will continue to be resolved. However, the results of DNS name queries will not be cached and the computer's name will not be registered. If the service is disabled, any services that explicitly depend on it will fail to start.
	GROUP		  : TDI
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 4  RUNNING
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: DoSvc
DISPLAY_NAME: Delivery Optimization
Performs content delivery optimization tasks
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: dot3svc
DISPLAY_NAME: Wired AutoConfig
The Wired AutoConfig (DOT3SVC) service is responsible for performing IEEE 802.1X authentication on Ethernet interfaces. If your current wired network deployment enforces 802.1X authentication, the DOT3SVC service should be configured to run for establishing Layer 2 connectivity and/or providing access to network resources. Wired networks that do not enforce 802.1X authentication are unaffected by the DOT3SVC service.
	GROUP		  : TDI
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: DPS
DISPLAY_NAME: Diagnostic Policy Service
The Diagnostic Policy Service enables problem detection, troubleshooting and resolution for Windows components.  If this service is stopped, diagnostics will no longer function.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 4  RUNNING
			       (STOPPABLE,NOT_PAUSABLE,ACCEPTS_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: DsmSvc
DISPLAY_NAME: Device Setup Manager
Enables the detection, download and installation of device-related software. If this service is disabled, devices may be configured with outdated software, and may not work correctly.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: DsSvc
DISPLAY_NAME: Data Sharing Service
Provides data brokering between applications.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: DusmSvc
DISPLAY_NAME: Data Usage
Network data usage, data limit, restrict background data, metered networks.
	GROUP		  : TDI
	TYPE		  : 10 WIN32_OWN_PROCESS 
	STATE		  : 4  RUNNING
			       (STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: Eaphost
DISPLAY_NAME: Extensible Authentication Protocol
The Extensible Authentication Protocol (EAP) service provides network authentication in such scenarios as 802.1x wired and wireless, VPN, and Network Access Protection (NAP).  EAP also provides application programming interfaces (APIs) that are used by network access clients, including wireless and VPN clients, during the authentication process.  If you disable this service, this computer is prevented from accessing networks that require EAP authentication.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: EFS
DISPLAY_NAME: Encrypting File System (EFS)
Provides the core file encryption technology used to store encrypted files on NTFS file system volumes. If this service is stopped or disabled, applications will be unable to access encrypted files.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 4  RUNNING
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: embeddedmode
DISPLAY_NAME: Embedded Mode
The Embedded Mode service enables scenarios related to Background Applications.  Disabling this service will prevent Background Applications from being activated.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: EntAppSvc
DISPLAY_NAME: Enterprise App Management Service
Enables enterprise application management.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: EventLog
DISPLAY_NAME: Windows Event Log
This service manages events and event logs. It supports logging events, querying events, subscribing to events, archiving event logs, and managing event metadata. It can display events in both XML and plain text format. Stopping this service may compromise security and reliability of the system.
	GROUP		  : Event Log
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 4  RUNNING
			       (STOPPABLE,NOT_PAUSABLE,ACCEPTS_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: EventSystem
DISPLAY_NAME: COM+ Event System
Supports System Event Notification Service (SENS), which provides automatic distribution of events to subscribing Component Object Model (COM) components. If the service is stopped, SENS will close and will not be able to provide logon and logoff notifications. If this service is disabled, any services that explicitly depend on it will fail to start.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 4  RUNNING
			       (STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: Fax
DISPLAY_NAME: Fax
Enables you to send and receive faxes, utilizing fax resources available on this computer or on the network.
	TYPE		  : 10 WIN32_OWN_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: fdPHost
DISPLAY_NAME: Function Discovery Provider Host
The FDPHOST service hosts the Function Discovery (FD) network discovery providers. These FD providers supply network discovery services for the Simple Services Discovery Protocol (SSDP) and Web Services  Discovery (WS-D) protocol. Stopping or disabling the FDPHOST service will disable network discovery for these protocols when using FD. When this service is unavailable, network services using FD and relying on these discovery protocols will be unable to find network devices or resources.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: FDResPub
DISPLAY_NAME: Function Discovery Resource Publication
Publishes this computer and resources attached to this computer so they can be discovered over the network.  If this service is stopped, network resources will no longer be published and they will not be discovered by other computers on the network.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: fhsvc
DISPLAY_NAME: File History Service
Protects user files from accidental loss by copying them to a backup location
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: FontCache
DISPLAY_NAME: Windows Font Cache Service
Optimizes performance of applications by caching commonly used font data. Applications will start this service if it is not already running. It can be disabled, though doing so will degrade application performance.
	GROUP		  : AudioGroup
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 4  RUNNING
			       (STOPPABLE,NOT_PAUSABLE,ACCEPTS_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: FrameServer
DISPLAY_NAME: Windows Camera Frame Server
Enables multiple clients to access video frames from camera devices.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: gcs
DISPLAY_NAME: Hyper-V Guest Compute Service
Guest Compute Service for Hyper-V Virtual Machines. This services manages containers in a utility VM.
	TYPE		  : 10 WIN32_OWN_PROCESS 
	STATE		  : 4  RUNNING
			       (STOPPABLE,NOT_PAUSABLE,ACCEPTS_PRESHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: gpsvc
DISPLAY_NAME: Group Policy Client
The service is responsible for applying settings configured by administrators for the computer and users through the Group Policy component. If the service is disabled, the settings will not be applied and applications and components will not be manageable through Group Policy. Any components or applications that depend on the Group Policy component might not be functional if the service is disabled.
	GROUP		  : ProfSvc_Group
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: GraphicsPerfSvc
DISPLAY_NAME: GraphicsPerfSvc
Graphics performance monitor service
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: hidserv
DISPLAY_NAME: Human Interface Device Service
Activates and maintains the use of hot buttons on keyboards, remote controls, and other multimedia devices. It is recommended that you keep this service running.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: HvHost
DISPLAY_NAME: HV Host Service
Provides an interface for the Hyper-V hypervisor to provide per-partition performance counters to the host operating system.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: icssvc
DISPLAY_NAME: Windows Mobile Hotspot Service
Provides the ability to share a cellular data connection with another device.
	GROUP		  : TDI
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: IKEEXT
DISPLAY_NAME: IKE and AuthIP IPsec Keying Modules
The IKEEXT service hosts the Internet Key Exchange (IKE) and Authenticated Internet Protocol (AuthIP) keying modules. These keying modules are used for authentication and key exchange in Internet Protocol security (IPsec). Stopping or disabling the IKEEXT service will disable IKE and AuthIP key exchange with peer computers. IPsec is typically configured to use IKE or AuthIP; therefore, stopping or disabling the IKEEXT service might result in an IPsec failure and might compromise the security of the system. It is strongly recommended that you have the IKEEXT service running.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 4  RUNNING
			       (STOPPABLE,NOT_PAUSABLE,ACCEPTS_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: InstallService
DISPLAY_NAME: Microsoft Store Install Service
Provides infrastructure support for the Microsoft Store.  This service is started on demand and if disabled then installations will not function properly.
	TYPE		  : 10 WIN32_OWN_PROCESS 
	STATE		  : 4  RUNNING
			       (STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: iphlpsvc
DISPLAY_NAME: IP Helper
Provides tunnel connectivity using IPv6 transition technologies (6to4, ISATAP, Port Proxy, and Teredo), and IP-HTTPS. If this service is stopped, the computer will not have the enhanced connectivity benefits that these technologies offer.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 4  RUNNING
			       (STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: IpxlatCfgSvc
DISPLAY_NAME: IP Translation Configuration Service
Configures and enables translation from v4 to v6 and vice versa
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: KeyIso
DISPLAY_NAME: CNG Key Isolation
The CNG key isolation service is hosted in the LSA process. The service provides key process isolation to private keys and associated cryptographic operations as required by the Common Criteria. The service stores and uses long-lived keys in a secure process complying with Common Criteria requirements.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 4  RUNNING
			       (STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: KtmRm
DISPLAY_NAME: KtmRm for Distributed Transaction Coordinator
Coordinates transactions between the Distributed Transaction Coordinator (MSDTC) and the Kernel Transaction Manager (KTM). If it is not needed, it is recommended that this service remain stopped. If it is needed, both MSDTC and KTM will start this service automatically. If this service is disabled, any MSDTC transaction interacting with a Kernel Resource Manager will fail and any services that explicitly depend on it will fail to start.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: LanmanServer
DISPLAY_NAME: Server
Supports file, print, and named-pipe sharing over the network for this computer. If this service is stopped, these functions will be unavailable. If this service is disabled, any services that explicitly depend on it will fail to start.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 4  RUNNING
			       (STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: LanmanWorkstation
DISPLAY_NAME: Workstation
Creates and maintains client network connections to remote servers using the SMB protocol. If this service is stopped, these connections will be unavailable. If this service is disabled, any services that explicitly depend on it will fail to start.
	GROUP		  : NetworkProvider
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 4  RUNNING
			       (STOPPABLE,PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: lfsvc
DISPLAY_NAME: Geolocation Service
This service monitors the current location of the system and manages geofences (a geographical location with associated events).  If you turn off this service, applications will be unable to use or receive notifications for geolocation or geofences.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: LicenseManager
DISPLAY_NAME: Windows License Manager Service
Provides infrastructure support for the Microsoft Store.  This service is started on demand and if disabled then content acquired through the Microsoft Store will not function properly.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 4  RUNNING
			       (STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: lltdsvc
DISPLAY_NAME: Link-Layer Topology Discovery Mapper
Creates a Network Map, consisting of PC and device topology (connectivity) information, and metadata describing each PC and device.  If this service is disabled, the Network Map will not function properly.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: lmhosts
DISPLAY_NAME: TCP/IP NetBIOS Helper
Provides support for the NetBIOS over TCP/IP (NetBT) service and NetBIOS name resolution for clients on the network, therefore enabling users to share files, print, and log on to the network. If this service is stopped, these functions might be unavailable. If this service is disabled, any services that explicitly depend on it will fail to start.
	GROUP		  : TDI
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: LSM
DISPLAY_NAME: Local Session Manager
Core Windows Service that manages local user sessions. Stopping or disabling this service will result in system instability.
	GROUP		  : COM Infrastructure
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 4  RUNNING
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: LxpSvc
DISPLAY_NAME: Language Experience Service
Provides infrastructure support for deploying and configuring localized Windows resources. This service is started on demand and, if disabled, additional Windows languages will not be deployed to the system, and Windows may not function properly.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: MapsBroker
DISPLAY_NAME: Downloaded Maps Manager
Windows service for application access to downloaded maps. This service is started on-demand by application accessing downloaded maps. Disabling this service will prevent apps from accessing maps.
	GROUP		  : NetworkService
	TYPE		  : 10 WIN32_OWN_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: MixedRealityOpenXRSvc
DISPLAY_NAME: Windows Mixed Reality OpenXR Service
Enables Mixed Reality OpenXR runtime functionality
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: mpssvc
DISPLAY_NAME: Windows Defender Firewall
Windows Defender Firewall helps protect your computer by preventing unauthorized users from gaining access to your computer through the Internet or a network.
	GROUP		  : NetworkProvider
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 4  RUNNING
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: MSDTC
DISPLAY_NAME: Distributed Transaction Coordinator
Coordinates transactions that span multiple resource managers, such as databases, message queues, and file systems. If this service is stopped, these transactions will fail. If this service is disabled, any services that explicitly depend on it will fail to start.
	TYPE		  : 10 WIN32_OWN_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: MSiSCSI
DISPLAY_NAME: Microsoft iSCSI Initiator Service
Manages Internet SCSI (iSCSI) sessions from this computer to remote iSCSI target devices. If this service is stopped, this computer will not be able to login or access iSCSI targets. If this service is disabled, any services that explicitly depend on it will fail to start.
	GROUP		  : iSCSI
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: msiserver
DISPLAY_NAME: Windows Installer
Adds, modifies, and removes applications provided as a Windows Installer (*.msi, *.msp) package. If this service is disabled, any services that explicitly depend on it will fail to start.
	TYPE		  : 10 WIN32_OWN_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: NaturalAuthentication
DISPLAY_NAME: Natural Authentication
Signal aggregator service, that evaluates signals based on time, network, geolocation, bluetooth and cdf factors. Supported features are Device Unlock, Dynamic Lock and Dynamo MDM policies
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: NcaSvc
DISPLAY_NAME: Network Connectivity Assistant
Provides DirectAccess status notification for UI components
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: NcbService
DISPLAY_NAME: Network Connection Broker
Brokers connections that allow Windows Store Apps to receive notifications from the internet.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 4  RUNNING
			       (STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: NcdAutoSetup
DISPLAY_NAME: Network Connected Devices Auto-Setup
Network Connected Devices Auto-Setup service monitors and installs qualified devices that connect to a qualified network. Stopping or disabling this service will prevent Windows from discovering and installing qualified network connected devices automatically. Users can still manually add network connected devices to a PC through the user interface.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: Netlogon
DISPLAY_NAME: Netlogon
Maintains a secure channel between this computer and the domain controller for authenticating users and services. If this service is stopped, the computer may not authenticate users and services and the domain controller cannot register DNS records. If this service is disabled, any services that explicitly depend on it will fail to start.
	GROUP		  : MS_WindowsRemoteValidation
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: Netman
DISPLAY_NAME: Network Connections
Manages objects in the Network and Dial-Up Connections folder, in which you can view both local area network and remote connections.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: netprofm
DISPLAY_NAME: Network List Service
Identifies the networks to which the computer has connected, collects and stores properties for these networks, and notifies applications when these properties change.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 4  RUNNING
			       (STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: NetSetupSvc
DISPLAY_NAME: Network Setup Service
The Network Setup Service manages the installation of network drivers and permits the configuration of low-level network settings.  If this service is stopped, any driver installations that are in-progress may be cancelled.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: NetTcpPortSharing
DISPLAY_NAME: Net.Tcp Port Sharing Service
Provides ability to share TCP ports over the net.tcp protocol.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: NgcCtnrSvc
DISPLAY_NAME: Microsoft Passport Container
Manages local user identity keys used to authenticate user to identity providers as well as TPM virtual smart cards. If this service is disabled, local user identity keys and TPM virtual smart cards will not be accessible. It is recommended that you do not reconfigure this service.
	GROUP		  : Cryptography
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: NgcSvc
DISPLAY_NAME: Microsoft Passport
Provides process isolation for cryptographic keys used to authenticate to a users associated identity providers. If this service is disabled, all uses and management of these keys will not be available, which includes machine logon and single-sign on for apps and websites. This service starts and stops automatically. It is recommended that you do not reconfigure this service.
	GROUP		  : Cryptography
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: NlaSvc
DISPLAY_NAME: Network Location Awareness
Collects and stores configuration information for the network and notifies programs when this information is modified. If this service is stopped, configuration information might be unavailable. If this service is disabled, any services that explicitly depend on it will fail to start.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 4  RUNNING
			       (STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: nsi
DISPLAY_NAME: Network Store Interface Service
This service delivers network notifications (e.g. interface addition/deleting etc) to user mode clients. Stopping this service will cause loss of network connectivity. If this service is disabled, any other services that explicitly depend on this service will fail to start.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 4  RUNNING
			       (STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: p2pimsvc
DISPLAY_NAME: Peer Networking Identity Manager
Provides identity services for the Peer Name Resolution Protocol (PNRP) and Peer-to-Peer Grouping services.  If disabled, the Peer Name Resolution Protocol (PNRP) and Peer-to-Peer Grouping services may not function, and some applications, such as HomeGroup and Remote Assistance, may not function correctly.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: p2psvc
DISPLAY_NAME: Peer Networking Grouping
Enables multi-party communication using Peer-to-Peer Grouping.  If disabled, some applications, such as HomeGroup, may not function.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: PcaSvc
DISPLAY_NAME: Program Compatibility Assistant Service
This service provides support for the Program Compatibility Assistant (PCA).  PCA monitors programs installed and run by the user and detects known compatibility problems. If this service is stopped, PCA will not function properly.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 4  RUNNING
			       (STOPPABLE,NOT_PAUSABLE,ACCEPTS_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: PeerDistSvc
DISPLAY_NAME: BranchCache
This service caches network content from peers on the local subnet.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: perceptionsimulation
DISPLAY_NAME: Windows Perception Simulation Service
Enables spatial perception simulation, virtual camera management and spatial input simulation.
	TYPE		  : 10 WIN32_OWN_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: PerfHost
DISPLAY_NAME: Performance Counter DLL Host
Enables remote users and 64-bit processes to query performance counters provided by 32-bit DLLs. If this service is stopped, only local users and 32-bit processes will be able to query performance counters provided by 32-bit DLLs.
	TYPE		  : 10 WIN32_OWN_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: PhoneSvc
DISPLAY_NAME: Phone Service
Manages the telephony state on the device
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: pla
DISPLAY_NAME: Performance Logs & Alerts
Performance Logs and Alerts Collects performance data from local or remote computers based on preconfigured schedule parameters, then writes the data to a log or triggers an alert. If this service is stopped, performance information will not be collected. If this service is disabled, any services that explicitly depend on it will fail to start.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: PlugPlay
DISPLAY_NAME: Plug and Play
Enables a computer to recognize and adapt to hardware changes with little or no user input. Stopping or disabling this service will result in system instability.
	GROUP		  : PlugPlay
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 4  RUNNING
			       (STOPPABLE,NOT_PAUSABLE,ACCEPTS_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: PNRPAutoReg
DISPLAY_NAME: PNRP Machine Name Publication Service
This service publishes a machine name using the Peer Name Resolution Protocol.  Configuration is managed via the netsh context 'p2p pnrp peer' 
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: PNRPsvc
DISPLAY_NAME: Peer Name Resolution Protocol
Enables serverless peer name resolution over the Internet using the Peer Name Resolution Protocol (PNRP). If disabled, some peer-to-peer and collaborative applications, such as Remote Assistance, may not function.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: PolicyAgent
DISPLAY_NAME: IPsec Policy Agent
Internet Protocol security (IPsec) supports network-level peer authentication, data origin authentication, data integrity, data confidentiality (encryption), and replay protection.  This service enforces IPsec policies created through the IP Security Policies snap-in or the command-line tool "netsh ipsec".  If you stop this service, you may experience network connectivity issues if your policy requires that connections use IPsec.  Also,remote management of Windows Defender Firewall is not available when this service is stopped.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 4  RUNNING
			       (STOPPABLE,NOT_PAUSABLE,ACCEPTS_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: Power
DISPLAY_NAME: Power
Manages power policy and power policy notification delivery.
	GROUP		  : Plugplay
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 4  RUNNING
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: PrintNotify
DISPLAY_NAME: Printer Extensions and Notifications
This service opens custom printer dialog boxes and handles notifications from a remote print server or a printer. If you turn off this service, you wont be able to see printer extensions or notifications.
	TYPE		  : 120 WIN32_SHARE_PROCESS INTERACTIVE_PROCESS  
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: ProfSvc
DISPLAY_NAME: User Profile Service
This service is responsible for loading and unloading user profiles. If this service is stopped or disabled, users will no longer be able to successfully sign in or sign out, apps might have problems getting to users' data, and components registered to receive profile event notifications won't receive them.
	GROUP		  : profsvc_group
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 4  RUNNING
			       (STOPPABLE,NOT_PAUSABLE,ACCEPTS_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: PushToInstall
DISPLAY_NAME: Windows PushToInstall Service
Provides infrastructure support for the Microsoft Store.  This service is started automatically and if disabled then remote installations will not function properly.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: QWAVE
DISPLAY_NAME: Quality Windows Audio Video Experience
Quality Windows Audio Video Experience (qWave) is a networking platform for Audio Video (AV) streaming applications on IP home networks. qWave enhances AV streaming performance and reliability by ensuring network quality-of-service (QoS) for AV applications. It provides mechanisms for admission control, run time monitoring and enforcement, application feedback, and traffic prioritization.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: RasAuto
DISPLAY_NAME: Remote Access Auto Connection Manager
Creates a connection to a remote network whenever a program references a remote DNS or NetBIOS name or address.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: RasMan
DISPLAY_NAME: Remote Access Connection Manager
Manages dial-up and virtual private network (VPN) connections from this computer to the Internet or other remote networks. If this service is disabled, any services that explicitly depend on it will fail to start.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: RemoteAccess
DISPLAY_NAME: Routing and Remote Access
Offers routing services to businesses in local area and wide area network environments.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: RemoteRegistry
DISPLAY_NAME: Remote Registry
Enables remote users to modify registry settings on this computer. If this service is stopped, the registry can be modified only by users on this computer. If this service is disabled, any services that explicitly depend on it will fail to start.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: RetailDemo
DISPLAY_NAME: Retail Demo Service
The Retail Demo service controls device activity while the device is in retail demo mode.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: RmSvc
DISPLAY_NAME: Radio Management Service
Radio Management and Airplane Mode Service
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: RpcEptMapper
DISPLAY_NAME: RPC Endpoint Mapper
Resolves RPC interfaces identifiers to transport endpoints. If this service is stopped or disabled, programs using Remote Procedure Call (RPC) services will not function properly.
	GROUP		  : COM Infrastructure
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 4  RUNNING
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: RpcLocator
DISPLAY_NAME: Remote Procedure Call (RPC) Locator
In Windows 2003 and earlier versions of Windows, the Remote Procedure Call (RPC) Locator service manages the RPC name service database. In Windows Vista and later versions of Windows, this service does not provide any functionality and is present for application compatibility.
	TYPE		  : 10 WIN32_OWN_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: RpcSs
DISPLAY_NAME: Remote Procedure Call (RPC)
The RPCSS service is the Service Control Manager for COM and DCOM servers. It performs object activations requests, object exporter resolutions and distributed garbage collection for COM and DCOM servers. If this service is stopped or disabled, programs using COM or DCOM will not function properly. It is strongly recommended that you have the RPCSS service running.
	GROUP		  : COM Infrastructure
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 4  RUNNING
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: SamSs
DISPLAY_NAME: Security Accounts Manager
The startup of this service signals other services that the Security Accounts Manager (SAM) is ready to accept requests.  Disabling this service will prevent other services in the system from being notified when the SAM is ready, which may in turn cause those services to fail to start correctly. This service should not be disabled.
	GROUP		  : MS_WindowsLocalValidation
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 4  RUNNING
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: SCardSvr
DISPLAY_NAME: Smart Card
Manages access to smart cards read by this computer. If this service is stopped, this computer will be unable to read smart cards. If this service is disabled, any services that explicitly depend on it will fail to start.
	GROUP		  : SmartCardGroup
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: ScDeviceEnum
DISPLAY_NAME: Smart Card Device Enumeration Service
Creates software device nodes for all smart card readers accessible to a given session. If this service is disabled, WinRT APIs will not be able to enumerate smart card readers.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: Schedule
DISPLAY_NAME: Task Scheduler
Enables a user to configure and schedule automated tasks on this computer. The service also hosts multiple Windows system-critical tasks. If this service is stopped or disabled, these tasks will not be run at their scheduled times. If this service is disabled, any services that explicitly depend on it will fail to start.
	GROUP		  : SchedulerGroup
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 4  RUNNING
			       (STOPPABLE,NOT_PAUSABLE,ACCEPTS_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: SCPolicySvc
DISPLAY_NAME: Smart Card Removal Policy
Allows the system to be configured to lock the user desktop upon smart card removal.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: SDRSVC
DISPLAY_NAME: Windows Backup
Provides Windows Backup and Restore capabilities.
	TYPE		  : 10 WIN32_OWN_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: seclogon
DISPLAY_NAME: Secondary Logon
Enables starting processes under alternate credentials. If this service is stopped, this type of logon access will be unavailable. If this service is disabled, any services that explicitly depend on it will fail to start.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: SecurityHealthService
DISPLAY_NAME: Windows Security Service
Windows Security Service handles unified device protection and health information
	TYPE		  : 10 WIN32_OWN_PROCESS 
	STATE		  : 4  RUNNING
			       (NOT_STOPPABLE,NOT_PAUSABLE,ACCEPTS_PRESHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: SEMgrSvc
DISPLAY_NAME: Payments and NFC/SE Manager
Manages payments and Near Field Communication (NFC) based secure elements.
	TYPE		  : 10 WIN32_OWN_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: SENS
DISPLAY_NAME: System Event Notification Service
Monitors system events and notifies subscribers to COM+ Event System of these events.
	GROUP		  : ProfSvc_Group
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 4  RUNNING
			       (STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: Sense
DISPLAY_NAME: Windows Defender Advanced Threat Protection Service
Windows Defender Advanced Threat Protection service helps protect against advanced threats by monitoring and reporting security events that happen on the computer.
	TYPE		  : 10 WIN32_OWN_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: SensorDataService
DISPLAY_NAME: Sensor Data Service
Delivers data from a variety of sensors
	TYPE		  : 10 WIN32_OWN_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: SensorService
DISPLAY_NAME: Sensor Service
A service for sensors that manages different sensors' functionality. Manages Simple Device Orientation (SDO) and History for sensors. Loads the SDO sensor that reports device orientation changes.  If this service is stopped or disabled, the SDO sensor will not be loaded and so auto-rotation will not occur. History collection from Sensors will also be stopped.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: SensrSvc
DISPLAY_NAME: Sensor Monitoring Service
Monitors various sensors in order to expose data and adapt to system and user state.  If this service is stopped or disabled, the display brightness will not adapt to lighting conditions. Stopping this service may affect other system functionality and features as well.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: SessionEnv
DISPLAY_NAME: Remote Desktop Configuration
Remote Desktop Configuration service (RDCS) is responsible for all Remote Desktop Services and Remote Desktop related configuration and session maintenance activities that require SYSTEM context. These include per-session temporary folders, RD themes, and RD certificates.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 4  RUNNING
			       (STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: SgrmBroker
DISPLAY_NAME: System Guard Runtime Monitor Broker
Monitors and attests to the integrity of the Windows platform.
	TYPE		  : 10 WIN32_OWN_PROCESS 
	STATE		  : 4  RUNNING
			       (NOT_STOPPABLE,NOT_PAUSABLE,ACCEPTS_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: SharedAccess
DISPLAY_NAME: Internet Connection Sharing (ICS)
Provides network address translation, addressing, name resolution and/or intrusion prevention services for a home or small office network.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: SharedRealitySvc
DISPLAY_NAME: Spatial Data Service
This service is used for Spatial Perception scenarios
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: ShellHWDetection
DISPLAY_NAME: Shell Hardware Detection
Provides notifications for AutoPlay hardware events.
	GROUP		  : ShellSvcGroup
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: shpamsvc
DISPLAY_NAME: Shared PC Account Manager
Manages profiles and accounts on a SharedPC configured device
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: smphost
DISPLAY_NAME: Microsoft Storage Spaces SMP
Host service for the Microsoft Storage Spaces management provider. If this service is stopped or disabled, Storage Spaces cannot be managed.
	TYPE		  : 10 WIN32_OWN_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: SmsRouter
DISPLAY_NAME: Microsoft Windows SMS Router Service.
Routes messages based on rules to appropriate clients.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: SNMPTRAP
DISPLAY_NAME: SNMP Trap
Receives trap messages generated by local or remote Simple Network Management Protocol (SNMP) agents and forwards the messages to SNMP management programs running on this computer. If this service is stopped, SNMP-based programs on this computer will not receive SNMP trap messages. If this service is disabled, any services that explicitly depend on it will fail to start.
	TYPE		  : 10 WIN32_OWN_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: spectrum
DISPLAY_NAME: Windows Perception Service
Enables spatial perception, spatial input, and holographic rendering.
	TYPE		  : 10 WIN32_OWN_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: Spooler
DISPLAY_NAME: Print Spooler
This service spools print jobs and handles interaction with the printer.  If you turn off this service, you wont be able to print or see your printers.
	GROUP		  : SpoolerGroup
	TYPE		  : 110 WIN32_OWN_PROCESS INTERACTIVE_PROCESS  
	STATE		  : 4  RUNNING
			       (STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: sppsvc
DISPLAY_NAME: Software Protection
Enables the download, installation and enforcement of digital licenses for Windows and Windows applications. If the service is disabled, the operating system and licensed applications may run in a notification mode. It is strongly recommended that you not disable the Software Protection service.
	TYPE		  : 10 WIN32_OWN_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: SSDPSRV
DISPLAY_NAME: SSDP Discovery
Discovers networked devices and services that use the SSDP discovery protocol, such as UPnP devices. Also announces SSDP devices and services running on the local computer. If this service is stopped, SSDP-based devices will not be discovered. If this service is disabled, any services that explicitly depend on it will fail to start.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 4  RUNNING
			       (STOPPABLE,NOT_PAUSABLE,ACCEPTS_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: ssh-agent
DISPLAY_NAME: OpenSSH Authentication Agent
Agent to hold private keys used for public key authentication.
	TYPE		  : 10 WIN32_OWN_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: SstpSvc
DISPLAY_NAME: Secure Socket Tunneling Protocol Service
Provides support for the Secure Socket Tunneling Protocol (SSTP) to connect to remote computers using VPN. If this service is disabled, users will not be able to use SSTP to access remote servers.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: StateRepository
DISPLAY_NAME: State Repository Service
Provides required infrastructure support for the application model.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 4  RUNNING
			       (STOPPABLE,NOT_PAUSABLE,ACCEPTS_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: stisvc
DISPLAY_NAME: Windows Image Acquisition (WIA)
Provides image acquisition services for scanners and cameras
	TYPE		  : 10 WIN32_OWN_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: StorSvc
DISPLAY_NAME: Storage Service
Provides enabling services for storage settings and external storage expansion
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 4  RUNNING
			       (STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: svsvc
DISPLAY_NAME: Spot Verifier
Verifies potential file system corruptions.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: swprv
DISPLAY_NAME: Microsoft Software Shadow Copy Provider
Manages software-based volume shadow copies taken by the Volume Shadow Copy service. If this service is stopped, software-based volume shadow copies cannot be managed. If this service is disabled, any services that explicitly depend on it will fail to start.
	TYPE		  : 10 WIN32_OWN_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: SysMain
DISPLAY_NAME: SysMain
Maintains and improves system performance over time.
	GROUP		  : profsvc_group
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 4  RUNNING
			       (STOPPABLE,NOT_PAUSABLE,ACCEPTS_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: SystemEventsBroker
DISPLAY_NAME: System Events Broker
Coordinates execution of background work for WinRT application. If this service is stopped or disabled, then background work might not be triggered.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 4  RUNNING
			       (STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: TabletInputService
DISPLAY_NAME: Touch Keyboard and Handwriting Panel Service
Enables Touch Keyboard and Handwriting Panel pen and ink functionality
	GROUP		  : PlugPlay
	TYPE		  : 10 WIN32_OWN_PROCESS 
	STATE		  : 4  RUNNING
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: TapiSrv
DISPLAY_NAME: Telephony
Provides Telephony API (TAPI) support for programs that control telephony devices on the local computer and, through the LAN, on servers that are also running the service.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: TermService
DISPLAY_NAME: Remote Desktop Services
Allows users to connect interactively to a remote computer. Remote Desktop and Remote Desktop Session Host Server depend on this service.  To prevent remote use of this computer, clear the checkboxes on the Remote tab of the System properties control panel item.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 4  RUNNING
			       (STOPPABLE,NOT_PAUSABLE,ACCEPTS_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: Themes
DISPLAY_NAME: Themes
Provides user experience theme management.
	GROUP		  : ProfSvc_Group
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 4  RUNNING
			       (STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: TieringEngineService
DISPLAY_NAME: Storage Tiers Management
Optimizes the placement of data in storage tiers on all tiered storage spaces in the system.
	TYPE		  : 10 WIN32_OWN_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: TimeBrokerSvc
DISPLAY_NAME: Time Broker
Coordinates execution of background work for WinRT application. If this service is stopped or disabled, then background work might not be triggered.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 4  RUNNING
			       (STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: TokenBroker
DISPLAY_NAME: Web Account Manager
This service is used by Web Account Manager to provide single-sign-on to apps and services.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 4  RUNNING
			       (STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: TrkWks
DISPLAY_NAME: Distributed Link Tracking Client
Maintains links between NTFS files within a computer or across computers in a network.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 4  RUNNING
			       (STOPPABLE,NOT_PAUSABLE,ACCEPTS_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: TroubleshootingSvc
DISPLAY_NAME: Recommended Troubleshooting Service
Enables automatic mitigation for known problems by applying recommended troubleshooting. If stopped, your device will not get recommended troubleshooting for problems on your device.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: TrustedInstaller
DISPLAY_NAME: Windows Modules Installer
Enables installation, modification, and removal of Windows updates and optional components. If this service is disabled, install or uninstall of Windows updates might fail for this computer.
	GROUP		  : ProfSvc_Group
	TYPE		  : 10 WIN32_OWN_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: tzautoupdate
DISPLAY_NAME: Auto Time Zone Updater
Automatically sets the system time zone.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: UevAgentService
DISPLAY_NAME: User Experience Virtualization Service
Provides support for application and OS settings roaming
	GROUP		  : ProfSvc_Group
	TYPE		  : 10 WIN32_OWN_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: UmRdpService
DISPLAY_NAME: Remote Desktop Services UserMode Port Redirector
Allows the redirection of Printers/Drives/Ports for RDP connections
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 4  RUNNING
			       (STOPPABLE,NOT_PAUSABLE,ACCEPTS_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: upnphost
DISPLAY_NAME: UPnP Device Host
Allows UPnP devices to be hosted on this computer. If this service is stopped, any hosted UPnP devices will stop functioning and no additional hosted devices can be added. If this service is disabled, any services that explicitly depend on it will fail to start.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: UserManager
DISPLAY_NAME: User Manager
User Manager provides the runtime components required for multi-user interaction.  If this service is stopped, some applications may not operate correctly.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 4  RUNNING
			       (STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: UsoSvc
DISPLAY_NAME: Update Orchestrator Service
Manages Windows Updates. If stopped, your devices will not be able to download and install the latest updates.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 4  RUNNING
			       (STOPPABLE,NOT_PAUSABLE,ACCEPTS_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: VacSvc
DISPLAY_NAME: Volumetric Audio Compositor Service
Hosts spatial analysis for Mixed Reality audio simulation.
	GROUP		  : AudioGroup
	TYPE		  : 10 WIN32_OWN_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: VaultSvc
DISPLAY_NAME: Credential Manager
Provides secure storage and retrieval of credentials to users, applications and security service packages.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 4  RUNNING
			       (STOPPABLE,NOT_PAUSABLE,ACCEPTS_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: vds
DISPLAY_NAME: Virtual Disk
Provides management services for disks, volumes, file systems, and storage arrays.
	TYPE		  : 10 WIN32_OWN_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: vmicguestinterface
DISPLAY_NAME: Hyper-V Guest Service Interface
Provides an interface for the Hyper-V host to interact with specific services running inside the virtual machine.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: vmicheartbeat
DISPLAY_NAME: Hyper-V Heartbeat Service
Monitors the state of this virtual machine by reporting a heartbeat at regular intervals. This service helps you identify running virtual machines that have stopped responding.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: vmickvpexchange
DISPLAY_NAME: Hyper-V Data Exchange Service
Provides a mechanism to exchange data between the virtual machine and the operating system running on the physical computer.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: vmicrdv
DISPLAY_NAME: Hyper-V Remote Desktop Virtualization Service
Provides a platform for communication between the virtual machine and the operating system running on the physical computer.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: vmicshutdown
DISPLAY_NAME: Hyper-V Guest Shutdown Service
Provides a mechanism to shut down the operating system of this virtual machine from the management interfaces on the physical computer.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: vmictimesync
DISPLAY_NAME: Hyper-V Time Synchronization Service
Synchronizes the system time of this virtual machine with the system time of the physical computer.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 4  RUNNING
			       (STOPPABLE,PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: vmicvmsession
DISPLAY_NAME: Hyper-V PowerShell Direct Service
Provides a mechanism to manage virtual machine with PowerShell via VM session without a virtual network.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: vmicvss
DISPLAY_NAME: Hyper-V Volume Shadow Copy Requestor
Coordinates the communications that are required to use Volume Shadow Copy Service to back up applications and data on this virtual machine from the operating system on the physical computer.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: VSS
DISPLAY_NAME: Volume Shadow Copy
Manages and implements Volume Shadow Copies used for backup and other purposes. If this service is stopped, shadow copies will be unavailable for backup and the backup may fail. If this service is disabled, any services that explicitly depend on it will fail to start.
	TYPE		  : 10 WIN32_OWN_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: W32Time
DISPLAY_NAME: Windows Time
Maintains date and time synchronization on all clients and servers in the network. If this service is stopped, date and time synchronization will be unavailable. If this service is disabled, any services that explicitly depend on it will fail to start.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: WaaSMedicSvc
DISPLAY_NAME: Windows Update Medic Service
Enables remediation and protection of Windows Update components.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: WalletService
DISPLAY_NAME: WalletService
Hosts objects used by clients of the wallet
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: WarpJITSvc
DISPLAY_NAME: WarpJITSvc
Provides a JIT out of process service for WARP when running with ACG enabled.
	TYPE		  : 10 WIN32_OWN_PROCESS 
	STATE		  : 4  RUNNING
			       (STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: wbengine
DISPLAY_NAME: Block Level Backup Engine Service
The WBENGINE service is used by Windows Backup to perform backup and recovery operations. If this service is stopped by a user, it may cause the currently running backup or recovery operation to fail. Disabling this service may disable backup and recovery operations using Windows Backup on this computer.
	TYPE		  : 10 WIN32_OWN_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: WbioSrvc
DISPLAY_NAME: Windows Biometric Service
The Windows biometric service gives client applications the ability to capture, compare, manipulate, and store biometric data without gaining direct access to any biometric hardware or samples. The service is hosted in a privileged SVCHOST process.
	GROUP		  : SmartCardGroup
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: Wcmsvc
DISPLAY_NAME: Windows Connection Manager
Makes automatic connect/disconnect decisions based on the network connectivity options currently available to the PC and enables management of network connectivity based on Group Policy settings.
	GROUP		  : TDI
	TYPE		  : 10 WIN32_OWN_PROCESS 
	STATE		  : 4  RUNNING
			       (STOPPABLE,NOT_PAUSABLE,ACCEPTS_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: wcncsvc
DISPLAY_NAME: Windows Connect Now - Config Registrar
WCNCSVC hosts the Windows Connect Now Configuration which is Microsoft's Implementation of Wireless Protected Setup (WPS) protocol. This is used to configure Wireless LAN settings for an Access Point (AP) or a Wireless Device. The service is started programmatically as needed.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: WdiServiceHost
DISPLAY_NAME: Diagnostic Service Host
The Diagnostic Service Host is used by the Diagnostic Policy Service to host diagnostics that need to run in a Local Service context.  If this service is stopped, any diagnostics that depend on it will no longer function.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: WdiSystemHost
DISPLAY_NAME: Diagnostic System Host
The Diagnostic System Host is used by the Diagnostic Policy Service to host diagnostics that need to run in a Local System context.  If this service is stopped, any diagnostics that depend on it will no longer function.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: WdNisSvc
DISPLAY_NAME: WdNisSvc
	TYPE		  : 10 WIN32_OWN_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: WebClient
DISPLAY_NAME: WebClient
Enables Windows-based programs to create, access, and modify Internet-based files. If this service is stopped, these functions will not be available. If this service is disabled, any services that explicitly depend on it will fail to start.
	GROUP		  : NetworkProvider
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: Wecsvc
DISPLAY_NAME: Windows Event Collector
This service manages persistent subscriptions to events from remote sources that support WS-Management protocol. This includes Windows Vista event logs, hardware and IPMI-enabled event sources. The service stores forwarded events in a local Event Log. If this service is stopped or disabled event subscriptions cannot be created and forwarded events cannot be accepted.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: WEPHOSTSVC
DISPLAY_NAME: Windows Encryption Provider Host Service
Windows Encryption Provider Host Service brokers encryption related functionalities from 3rd Party Encryption Providers to processes that need to evaluate and apply EAS policies. Stopping this will compromise EAS compliancy checks that have been established by the connected Mail Accounts
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: wercplsupport
DISPLAY_NAME: Problem Reports Control Panel Support
This service provides support for viewing, sending and deletion of system-level problem reports for the Problem Reports control panel.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: WerSvc
DISPLAY_NAME: Windows Error Reporting Service
Allows errors to be reported when programs stop working or responding and allows existing solutions to be delivered. Also allows logs to be generated for diagnostic and repair services. If this service is stopped, error reporting might not work correctly and results of diagnostic services and repairs might not be displayed.
	TYPE		  : 10 WIN32_OWN_PROCESS 
	STATE		  : 4  RUNNING
			       (STOPPABLE,PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: WFDSConMgrSvc
DISPLAY_NAME: Wi-Fi Direct Services Connection Manager Service
Manages connections to wireless services, including wireless display and docking.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: WiaRpc
DISPLAY_NAME: Still Image Acquisition Events
Launches applications associated with still image acquisition events.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: WinDefend
DISPLAY_NAME: WinDefend
	TYPE		  : 10 WIN32_OWN_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: WinHttpAutoProxySvc
DISPLAY_NAME: WinHTTP Web Proxy Auto-Discovery Service
WinHTTP implements the client HTTP stack and provides developers with a Win32 API and COM Automation component for sending HTTP requests and receiving responses. In addition, WinHTTP provides support for auto-discovering a proxy configuration via its implementation of the Web Proxy Auto-Discovery (WPAD) protocol.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 4  RUNNING
			       (NOT_STOPPABLE,NOT_PAUSABLE,ACCEPTS_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: Winmgmt
DISPLAY_NAME: Windows Management Instrumentation
Provides a common interface and object model to access management information about operating system, devices, applications and services. If this service is stopped, most Windows-based software will not function properly. If this service is disabled, any services that explicitly depend on it will fail to start.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 4  RUNNING
			       (STOPPABLE,PAUSABLE,ACCEPTS_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: WinRM
DISPLAY_NAME: Windows Remote Management (WS-Management)
Windows Remote Management (WinRM) service implements the WS-Management protocol for remote management. WS-Management is a standard web services protocol used for remote software and hardware management. The WinRM service listens on the network for WS-Management requests and processes them. The WinRM Service needs to be configured with a listener using winrm.cmd command line tool or through Group Policy in order for it to listen over the network. The WinRM service provides access to WMI data and enables event collection. Event collection and subscription to events require that the service is running. WinRM messages use HTTP and HTTPS as transports. The WinRM service does not depend on IIS but is preconfigured to share a port with IIS on the same machine.  The WinRM service reserves the /wsman URL prefix. To prevent conflicts with IIS, administrators should ensure that any websites hosted on IIS do not use the /wsman URL prefix.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: wisvc
DISPLAY_NAME: Windows Insider Service
Provides infrastructure support for the Windows Insider Program. This service must remain enabled for the Windows Insider Program to work.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: WlanSvc
DISPLAY_NAME: WLAN AutoConfig
The WLANSVC service provides the logic required to configure, discover, connect to, and disconnect from a wireless local area network (WLAN) as defined by IEEE 802.11 standards. It also contains the logic to turn your computer into a software access point so that other devices or computers can connect to your computer wirelessly using a WLAN adapter that can support this. Stopping or disabling the WLANSVC service will make all WLAN adapters on your computer inaccessible from the Windows networking UI. It is strongly recommended that you have the WLANSVC service running if your computer has a WLAN adapter.
	GROUP		  : TDI
	TYPE		  : 10 WIN32_OWN_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: wlidsvc
DISPLAY_NAME: Microsoft Account Sign-in Assistant
Enables user sign-in through Microsoft account identity services. If this service is stopped, users will not be able to logon to the computer with their Microsoft account.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: wlpasvc
DISPLAY_NAME: Local Profile Assistant Service
This service provides profile management for subscriber identity modules
	GROUP		  : TDI
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: WManSvc
DISPLAY_NAME: Windows Management Service
Performs management including Provisioning and Enrollment activities
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: wmiApSrv
DISPLAY_NAME: WMI Performance Adapter
Provides performance library information from Windows Management Instrumentation (WMI) providers to clients on the network. This service only runs when Performance Data Helper is activated.
	TYPE		  : 10 WIN32_OWN_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: WMPNetworkSvc
DISPLAY_NAME: Windows Media Player Network Sharing Service
Shares Windows Media Player libraries to other networked players and media devices using Universal Plug and Play
	TYPE		  : 10 WIN32_OWN_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: workfolderssvc
DISPLAY_NAME: Work Folders
This service syncs files with the Work Folders server, enabling you to use the files on any of the PCs and devices on which you've set up Work Folders.
	GROUP		  : LocalService
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: WpcMonSvc
DISPLAY_NAME: Parental Controls
Enforces parental controls for child accounts in Windows. If this service is stopped or disabled, parental controls may not be enforced.
	TYPE		  : 10 WIN32_OWN_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: WPDBusEnum
DISPLAY_NAME: Portable Device Enumerator Service
Enforces group policy for removable mass-storage devices. Enables applications such as Windows Media Player and Image Import Wizard to transfer and synchronize content using removable mass-storage devices.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: WpnService
DISPLAY_NAME: Windows Push Notifications System Service
This service runs in session 0 and hosts the notification platform and connection provider which handles the connection between the device and WNS server.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 4  RUNNING
			       (STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: wscsvc
DISPLAY_NAME: Security Center
The WSCSVC (Windows Security Center) service monitors and reports security health settings on the computer.  The health settings include firewall (on/off), antivirus (on/off/out of date), antispyware (on/off/out of date), Windows Update (automatically/manually download and install updates), User Account Control (on/off), and Internet settings (recommended/not recommended). The service provides COM APIs for independent software vendors to register and record the state of their products to the Security Center service.  The Security and Maintenance UI uses the service to provide systray alerts and a graphical view of the security health states in the Security and Maintenance control panel.  Network Access Protection (NAP) uses the service to report the security health states of clients to the NAP Network Policy Server to make network quarantine decisions.  The service also has a public API that allows external consumers to programmatically retrieve the aggregated security health state of the system.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 4  RUNNING
			       (STOPPABLE,NOT_PAUSABLE,ACCEPTS_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: WSearch
DISPLAY_NAME: Windows Search
Provides content indexing, property caching, and search results for files, e-mail, and other content.
	TYPE		  : 10 WIN32_OWN_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: wuauserv
DISPLAY_NAME: Windows Update
Enables the detection, download, and installation of updates for Windows and other programs. If this service is disabled, users of this computer will not be able to use Windows Update or its automatic updating feature, and programs will not be able to use the Windows Update Agent (WUA) API.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: WwanSvc
DISPLAY_NAME: WWAN AutoConfig
This service manages mobile broadband (GSM & CDMA) data card/embedded module adapters and connections by auto-configuring the networks. It is strongly recommended that this service be kept running for best user experience of mobile broadband devices.
	GROUP		  : TDI
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: XblAuthManager
DISPLAY_NAME: Xbox Live Auth Manager
Provides authentication and authorization services for interacting with Xbox Live. If this service is stopped, some applications may not operate correctly.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: XblGameSave
DISPLAY_NAME: Xbox Live Game Save
This service syncs save data for Xbox Live save enabled games.  If this service is stopped, game save data will not upload to or download from Xbox Live.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: XboxGipSvc
DISPLAY_NAME: Xbox Accessory Management Service
This service manages connected Xbox Accessories.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: XboxNetApiSvc
DISPLAY_NAME: Xbox Live Networking Service
This service supports the Windows.Networking.XboxLive application programming interface.
	TYPE		  : 20 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: AarSvc_43a0b
DISPLAY_NAME: Agent Activation Runtime_43a0b
Runtime for activating conversational agent applications
	TYPE		  : e0 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: BcastDVRUserService_43a0b
DISPLAY_NAME: GameDVR and Broadcast User Service_43a0b
This user service is used for Game Recordings and Live Broadcasts
	TYPE		  : e0 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: BluetoothUserService_43a0b
DISPLAY_NAME: Bluetooth User Support Service_43a0b
The Bluetooth user service supports proper functionality of Bluetooth features relevant to each user session.
	TYPE		  : e0 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: CaptureService_43a0b
DISPLAY_NAME: CaptureService_43a0b
Enables optional screen capture functionality for applications that call the Windows.Graphics.Capture API.
	TYPE		  : e0 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: cbdhsvc_43a0b
DISPLAY_NAME: Clipboard User Service_43a0b
This user service is used for Clipboard scenarios
	TYPE		  : e0 WIN32_SHARE_PROCESS 
	STATE		  : 4  RUNNING
			       (STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: CDPUserSvc_43a0b
DISPLAY_NAME: Connected Devices Platform User Service_43a0b
This user service is used for Connected Devices Platform scenarios
	TYPE		  : e0 WIN32_SHARE_PROCESS 
	STATE		  : 4  RUNNING
			       (STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: ConsentUxUserSvc_43a0b
DISPLAY_NAME: ConsentUX_43a0b
Allows ConnectUX and PC Settings to Connect and Pair with WiFi displays and Bluetooth devices.
	TYPE		  : e0 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: CredentialEnrollmentManagerUserSvc_43a0b
DISPLAY_NAME: CredentialEnrollmentManagerUserSvc_43a0b
Credential Enrollment Manager
	TYPE		  : d0 WIN32_OWN_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: DeviceAssociationBrokerSvc_43a0b
DISPLAY_NAME: DeviceAssociationBroker_43a0b
Enables apps to pair devices
	TYPE		  : e0 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: DevicePickerUserSvc_43a0b
DISPLAY_NAME: DevicePicker_43a0b
This user service is used for managing the Miracast, DLNA, and DIAL UI
	TYPE		  : e0 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: DevicesFlowUserSvc_43a0b
DISPLAY_NAME: DevicesFlow_43a0b
Allows ConnectUX and PC Settings to Connect and Pair with WiFi displays and Bluetooth devices.
	TYPE		  : e0 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: MessagingService_43a0b
DISPLAY_NAME: MessagingService_43a0b
Service supporting text messaging and related functionality.
	TYPE		  : e0 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: OneSyncSvc_43a0b
DISPLAY_NAME: Sync Host_43a0b
This service synchronizes mail, contacts, calendar and various other user data. Mail and other applications dependent on this functionality will not work properly when this service is not running.
	TYPE		  : e0 WIN32_SHARE_PROCESS 
	STATE		  : 4  RUNNING
			       (STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: PimIndexMaintenanceSvc_43a0b
DISPLAY_NAME: Contact Data_43a0b
Indexes contact data for fast contact searching. If you stop or disable this service, contacts might be missing from your search results.
	TYPE		  : e0 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: PrintWorkflowUserSvc_43a0b
DISPLAY_NAME: PrintWorkflow_43a0b
Provides support for Print Workflow applications. If you turn off this service, you may not be able to print successfully.
	TYPE		  : e0 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: UdkUserSvc_43a0b
DISPLAY_NAME: Udk User Service_43a0b
Shell components service
	TYPE		  : e0 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: UnistoreSvc_43a0b
DISPLAY_NAME: User Data Storage_43a0b
Handles storage of structured user data, including contact info, calendars, messages, and other content. If you stop or disable this service, apps that use this data might not work correctly.
	TYPE		  : e0 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: UserDataSvc_43a0b
DISPLAY_NAME: User Data Access_43a0b
Provides apps access to structured user data, including contact info, calendars, messages, and other content. If you stop or disable this service, apps that use this data might not work correctly.
	TYPE		  : e0 WIN32_SHARE_PROCESS 
	STATE		  : 1  STOPPED
			       (NOT_STOPPABLE,NOT_PAUSABLE,IGNORES_SHUTDOWN)
	WIN32_EXIT_CODE	  : 1077 (0x435)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms

SERVICE_NAME: WpnUserService_43a0b
DISPLAY_NAME: Windows Push Notifications User Service_43a0b
This service hosts Windows notification platform which provides support for local and push notifications. Supported notifications are tile, toast and raw.
	TYPE		  : e0 WIN32_SHARE_PROCESS 
	STATE		  : 4  RUNNING
			       (STOPPABLE,NOT_PAUSABLE,ACCEPTS_PRESHUTDOWN)
	WIN32_EXIT_CODE	  : 0  (0x0)
	SERVICE_EXIT_CODE : 0  (0x0)
	CHECKPOINT	  : 0x0
	WAIT_HINT	  : 0 ms


```

### Loaded Modules:

Path |
-- |
C:\SysinternalsSuite\PsService.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `330000010A2C79AED7797BA6AC00010000010A`
* Thumbprint: `3BDA323E552DB1FDE5F4FBEE75D6D5B2B187EEDC`
* Issuer: CN=Microsoft Code Signing PCA, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, OU=MOPR, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: psservice.exe
* Product Name: Sysinternals psservice
* Company Name: Sysinternals - www.sysinternals.com
* File Version: 2.25
* Product Version: 2.25
* Language: English (United States)
* Legal Copyright: Copyright (C) 2001-2010 Mark Russinovich
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/9454ba56bcb470d330559573afbc10f6989ba46f3e656c20979de6f92e051752/detection/





MIT License. Copyright (c) 2020 Strontic.


