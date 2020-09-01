---
title: vncserver.exe | VNC Server
---

# vncserver.exe 

* File Path: `C:\program files\RealVNC\VNC Server\vncserver.exe`
* Description: VNC Server

## Hashes

Type | Hash
-- | --
MD5 | `5DAB0BC23F2D721B7C2EF80E94694514`
SHA1 | `2C9E7BCC0B50D1D1C345E77565D1469492374F14`
SHA256 | `1C8B26AA02BBF235D59EF953D471B53D964987772C8F255645F04522C46FBF69`
SHA384 | `FB6E4B48BD08FA05EE68410D588469922673E002758B0CBE4785711AB48D26EAB09A6381957B35FF27E8C07151420A44`
SHA512 | `B43014362E8543A2B071C18F657D1B0A4602F069A352610B8F727F6BDEA396DE9C868AE385B00560F0225E7BDBE79944607DCB3B2CA0C8F594847B52EA945449`
SSDEEP | `49152:Us+AiPieC+eXqBfo2dlksuYfNK2P3E5F1T8mfVW+IwjWAIDMFl0H8PA9vat8WtMM:B6PizavnrUfVJ9boD3wNhGCQzk`

## Runtime Data

### Usage (stdout):
```Batchfile
VNC(R) Server 6.1.1 (r28093) x64 (May 19 2017 12:39:54)
Copyright (C) 2002-2017 RealVNC Ltd.
RealVNC and VNC are trademarks of RealVNC Ltd and are protected by trademark
registrations and/or pending trademark applications in the European Union,
United States of America and other jurisdictions.
Protected by UK patent 2481870; US patent 8760366; EU patent 2652951.
See https://www.realvnc.com for information on VNC.
For third party acknowledgements see:
https://www.realvnc.com/docs/6.1/foss.html

Usage: vncserver [OPTION...]
       vncserver [MODE] [OPTION...] COMMAND

Mode:
  -service                COMMAND applies to VNC Server in Service Mode; the
                          default is VNC Server in User Mode.

Commands:
  -h[elp] [all]           Provide [advanced] usage information.
  -joinCloud JOIN-TOKEN [-joinGroup GROUP-NAME]...
                          Add VNC Server to a team to enable cloud
                          connectivity, optionally adding to groups GROUP-NAME.
                          Obtain the token JOIN-TOKEN from your RealVNC account
                          online.
  -start [-showstatus]    Start the VNC Server service, registering it if
                          necessary.
  -unregister             Unregister (and stop) the VNC Server service.
  -status                 Query the VNC Server service status.
  -stop                   Stop an existing VNC Server. Precede with -service to
                          stop the VNC Server service, but do not unregister
                          it.
  -reload                 Reload license keys and parameters for an existing
                          VNC Server.
  -showexistingstatus     Display the status dialog of an existing VNC Server.
  -disconnect             Disconnect all users from an existing VNC Server.
  -getconfig [PARAMETER]  Fetch the parameters in effect on a running instance
                          of VNC Server.
  -setconfig [FILE]       Read parameters from FILE (or "-" for stdin) and set
                          them on a single running instance of VNC Server; the
                          parameters will not be used when VNC Server next
                          starts.
  -generatekeys [force]   Generate and store an RSA private key; "force"
                          overwrites an existing key. Rsa* parameters may be
                          specified first (in particular RsaModulusBits).

Options are parameters, and also the following:
  -noconsole              Run without a console (i.e. no stderr/stdout).
  -vncconfigfile FILE     Load parameters from FILE.
  -showstatus             Show status dialog at startup.
  -newinstance            Start a new instance of VNC Server in User Mode.
                          Specify -RfbPort to avoid a port conflict.
  -iconnect HOST[::PORT]  Start VNC Server and connect out to Listening VNC
                          Viewer on HOST at PORT (default 5500).

Parameters can be turned on with -<param> or off with -<param>=0
Values can be specified as -<param> <value>
Other valid forms are <param>=<value> -<param>=<value> --<param>=<value>
Names are case-insensitive.  Valid parameters are listed below.

Global parameters:
  AcceptCutText  - Allow connected VNC Viewer users to paste text to this
                   computer. (default=1)
  AcceptKeyEvents - Allow connected VNC Viewer users to control this computer
                   using their keyboards. (default=1)
  AcceptPointerEvents - Allow connected VNC Viewer users to control this
                   computer using their mice. (default=1)
  AllowChangeDefaultPrinter - If printing is enabled, change this computer's
                   default printer to the local printer of the first VNC Viewer
                   user who connects. (default=1)
  AllowCloudRfb  - VNC Server in Service Mode only. Allow cloud connections via
                   RealVNC services. (default=1)
  AllowTcpListenRfb - Allow direct VNC connections over TCP. (default=1)
  AlwaysShared   - Determine whether multiple VNC Viewer users can be connected
                   at the same time, in conjunction with NeverShared.
                   (default=0)
  Authentication - The authentication scheme(s) to offer for incoming
                   connections (SingleSignOn | SystemAuth | VncAuth |
                   Certificate | Radius), or None to turn off password
                   protection (direct connections only, and not recommended).
                   (default=SystemAuth)
  AuthTimeout    - The number of seconds to give connecting VNC Viewer users
                   time to authenticate. (default=900)
  AutoLogonOverride - VNC Server in Service Mode only. Allow connected VNC
                   Viewer users pressing Shift while logging the current user
                   account off to bypass set ForceAutoLogon and
                   IgnoreShiftOverride Windows Registry values, and prevent the
                   same user account automatically logging back on. (default=0)
  BlacklistThreshold - The number of unsuccessful authentication attempts that
                   can be made before a particular connecting computer is
                   blacklisted for a timeout period. (default=5)
  BlacklistTimeout - The initial number of seconds during which connections
                   from a blacklisted computer are rejected before the
                   connecting user can attempt to authenticate again.
                   (default=10)
  BlankScreen    - Blank the monitor or screen of this computer while VNC
                   Viewer users are connected. (default=0)
  ClipboardFT    - Allow connected VNC Viewer users on Windows computers to
                   transfer files via copy and paste. (default=1)
  CompareFB      - Perform pixel comparison on framebuffer to reduce
                   unnecessary updates. (default=1)
  ConnNotifyTimeout - The number of seconds to display connection and
                   disconnection notification messages for, or 0 to disable
                   notifications. (default=4)
  ConnTimeout    - The maximum number of seconds a connection may last, or 0
                   for no timeout. (default=0)
  Desktop        - A name for the desktop to display to connected VNC Viewer
                   users. (default=$HOSTNAME)
  DisableAddNewClient - Disable the Connect to Listening VNC Viewer option on
                   the shortcut menu. (default=0)
  DisableAero    - Disable the Windows Aero interface to improve performance
                   while VNC Viewer users are connected. (default=0)
  DisableClose   - Disable the Stop VNC Server option on the shortcut menu.
                   (default=0)
  DisableEffects - Disable special effects such as font smoothing to improve
                   performance while VNC Viewer users are connected.
                   (default=0)
  DisableLocalInputs - Disable the keyboard and mouse of this computer to
                   protect the privacy of connected VNC Viewer users.
                   (default=0)
  DisableOptions - Disable the Options option on the shortcut menu. Note that
                   if you do this you will need to manually edit the
                   appropriate Registry key (Windows) or VNC configuration file
                   (other platforms) in order to access the Options dialog
                   again. (default=0)
  DisableTrayIcon - Specify 1 to hide the VNC Server icon in the notification
                   area when no VNC Viewer users are connected. (default=0)
  DisconnectAction - VNC Server in Service Mode only. Protect the computer when
                   the last user disconnects (Lock | Logoff), or do nothing
                   (None). (default=None)
  DisconnectClients - Determine whether multiple VNC Viewer users can be
                   connected at the same time, in conjunction with
                   AlwaysShared, NeverShared, and VNC Viewer. (default=1)
  EnableAnalytics - Send anonymous usage data to help improve RealVNC products.
                   (default=0)
  EnableAutoUpdateChecks - Allow automatic checks for critical software patches
                   and product updates (1), do not allow automatic checks (0),
                   or let the user decide when the VNC Server user interface
                   first appears (2). (default=2)
  EnableChat     - Allow connected VNC Viewer users to chat. (default=1)
  EnableGuestLogin - Turn on the Guest Access option on the shortcut menu when
                   VNC Server starts. (default=0)
  EnableManualUpdateChecks - Disable the Check for updates option on the
                   shortcut menu. (default=1)
  EnableRemotePrinting - Allow connected VNC Viewer users to print directly to
                   their local printers. (default=1)
  Encryption     - The level of encryption to offer for incoming connections
                   (AlwaysMaximum | AlwaysOn | PreferOn | PreferOff), or
                   AlwaysOff to turn off encryption (direct connections only,
                   and not recommended). (default=AlwaysOn)
  GuestAccess    - Allow guests to connect with particular permissions.
                   (default=)
  Hosts          - Filter connections by IPv4 address to allow, query, or
                   reject particular VNC Viewer computers, or + to allow
                   connections from all. (default=+)
  IdleTimeout    - The number of seconds to wait before disconnecting idle VNC
                   Viewer users, or 0 to set no timeout. (default=3600)
  LdapCertificateIntermediateStore - Optional URL containing intermediate
                   certificates for user public keys.  "file://" and "ldap://"
                   are supported, or "enterprise://" (Windows).
                   (default=enterprise://)
  LdapCertificateRevocation - Choose 'Enforce' to strictly check CRLs for user
                   public keys fetched from LDAP, 'CheckIfAvailable' to skip
                   the check if the CRL cannot be fetched, or 'Ignore' to
                   bypass CRL checking. (default=Enforce)
  LdapCertificateTrustStore - URL containing the trusted root certificates for
                   authenticating user public keys.  "file://" and "ldap://"
                   are supported, or "enterprise://" (Windows).
                   (default=enterprise://)
  LdapCertificateUserStore - URL of the LDAP server used for authenticating
                   user public keys, of the form
                   "ldap[s]://[creds@][host]/[search-base]".  If the host or
                   base is left empty, the system default will be used.
                   Specify "GSSAPI@" for Kerberos authentication,
                   "binddn:password@" for a simple bind, or no credentials for
                   anonymous access. (default=ldap://GSSAPI@/CN=Users,)
  LdapSecurity   - Choose LDAP security when not using LDAPS: use signatures
                   with Kerberos and StartTLS with simple binding (Auto), use
                   StartTLS always (StartTLS), or no encryption (None)
                   (default=Auto)
  Locale         - Locale to use. Specify one of en_US, de_DE, es_ES, or fr_FR,
                   or leave empty to select the user or system locale as
                   appropriate. (default=)
  localhost      - Restrict direct VNC connections over TCP to those
                   originating from this computer. (default=0)
  Log            - Record events in the format <log>:<target>:<level>[,...].
                   (default=*:file:10)
  LogDir         - Directory in which to store log output directed to file.
                   (default=$LOCAL_APPDATA_COMPANY)
  LogFile        - File in which to store log output directed to file.
                   (default=vncserver.log)
  NeverShared    - Determine whether multiple VNC Viewer users can be connected
                   at the same time, in conjunction with AlwaysShared and
                   DisconnectClients. (default=0)
  NtLogonAsInteractive - Establish connections as Windows Network logon type 3,
                   rather than Interactive logon type 2. (default=0)
  Permissions    - Register user accounts or groups with VNC Server so
                   connecting VNC Viewer users can authenticate using familiar,
                   securely-managed credentials. Grant permissions to these
                   users to use remote control features while connections are
                   in progress. (default=:f)
  ProtocolVersion - The maximum version number of the RFB protocol to support,
                   or empty for all. (default=)
  ProxyServer    - The URL of a proxy server, or alternatively "<system>" to
                   use IE or system proxy settings. (default=<system>)
  ProxyUserName  - The user name with which to authenticate to a proxy server.
                   (default=)
  QueryConnect   - Show a prompt identifying each connecting VNC Viewer user,
                   where possible, enabling the connection to be accepted,
                   rejected, or made view-only. (default=0)
  QueryConnectTimeout - The number of seconds to show the accept/reject prompt
                   for, before connections are automatically granted timeout
                   permissions. (default=10)
  QueryOnlyIfLoggedOn - Only show the accept/reject prompt if there is likely
                   to be a user present to respond. (default=0)
  QueryTimeoutRights - Determine whether connections exceeding the
                   accept/reject prompt's timeout are accepted or made
                   view-only. Leave empty to reject connections. (default=)
  QuitOnCloseStatusDialog - Stop VNC Server if the status dialog is closed.
                   (default=0)
  RadiusAddress  - The address to bind to for sending RADIUS requests, or empty
                   to use the default route to the RADIUS server (default=)
  RadiusAuthenticationProtocol - The authentication protocol to use (CHAP |
                   PAP).  Note that CHAP is potentially more secure than PAP,
                   but requires the server to have access to plaintext
                   credentials, so PAP is more widely supported. (default=CHAP)
  RadiusNasId    - The 'Network Access Server' identifier to present to the
                   RADIUS server, which identifies this RADIUS client, or empty
                   to send the IP address as the identifier instead
                   (RadiusAddress). (default=vncserver)
  RadiusNormalizeUsername - Strip the domain/realm component from usernames
                   when contacting the RADIUS server (default=0)
  RadiusPrompt   - The initial prompt to present to VNC Viewer users, or empty
                   to send a blank password to the RADIUS server initially
                   (default=RADIUS password:)
  RadiusServer   - The RADIUS server to use for authentication (host/IP address
                   with optional port).  Fallback servers can be specified
                   using a comma-separated list. (default=)
  RadiusTimeout  - The time spent waiting per RADIUS server; a few retries are
                   sent at 1-second intervals, then the rest of the timeout
                   interval is spent waiting before falling back to the next
                   server. (default=60)
  RemapKeys      - Map or swap keyboard keys. Specify a comma-separated list of
                   hexadecimal keysyms, prefixed by 0x and separated by -> (to
                   map) or <> (to swap). (default=)
  RemovePattern  - Hide the desktop background from connected VNC Viewer users.
                   (default=0)
  RemoveWallpaper - Hide the desktop wallpaper from connected VNC Viewer users.
                   (default=0)
  RfbPort        - TCP/IP port on which to accept VNC connections.
                   (default=5900)
  SendCutText    - Allow connected VNC Viewer users to copy and paste text to
                   their own computers. (default=1)
  ServerPreferredEncoding - Specify an encoding for VNC Server to use (if
                   supported), or 'Viewer' to grant the VNC Viewer preference
                   (default=Viewer)
  ServiceDiscoveryEnabled - Advertise VNC Server using Zeroconf on the local
                   domain. Requires the Bonjour library (Windows, MacOS,
                   Solaris) or Avahi (Linux). (default=1)
  ShareFiles     - Allow connected VNC Viewer users to transfer files.
                   (default=1)
  ShowCloudHints - VNC Server in Service Mode only. Show RealVNC services
                   information. (default=1)
  SimulateSAS    - VNC Server in Service Mode on Vista or later only. Either
                   allow connected VNC Viewer users to send Ctrl-Alt-Delete
                   when the SoftwareSASGeneration Windows policy setting is
                   unconfigured or disabled (1), or obey the policy setting
                   (0), or bypass Windows policy (2). (default=1)
  TcpListenAddresses - Comma-separated list of IP addresses on which to listen
                   for TCP connections, or empty to listen on all available IP
                   addresses. Note this parameter is ignored if the localhost
                   parameter is set to True. (default=)
  UpdateCheckFrequencyDays - The number of days to leave between automatic
                   checks for critical software patches or product updates.
                   (default=1)
Agent Parameters:
  CaptureMethod  - Capture screen updates using the optimal method (0), by
                   polling (1), or by using application hooks if possible (2).
                   For VNC Server in Service Mode, the optimal method uses
                   DirectX on Windows 8+ or VNC Mirror Driver on earlier
                   platforms. For VNC Server in User Mode, the optimal method
                   uses polling since XP. (default=0)
  DisplayDevice  - The name of the monitor to remote to connected VNC Viewer
                   users, or empty to remote all monitors. (default=)
  UseCaptureBlt  - Always capture screen updates to semi-transparent windows
                   and tooltips, to give connected VNC Viewer users perfect
                   picture fidelity at the possible expense of performance.
                   (default=1)

```

### Usage (stderr):
```Batchfile
Bad argument 'help'.  Run with -help for usage.

```

### Loaded Modules:

Path |
-- |
C:\program files\RealVNC\VNC Server\vncserver.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `2EB260DBC51427A731CD2519701AE3C0`
* Thumbprint: `9A6B5D6FC7D2F940C91AF3875B61849B129F85A6`
* Issuer: CN=VeriSign Class 3 Code Signing 2010 CA, OU=Terms of use at https://www.verisign.com/rpa (c)10, OU=VeriSign Trust Network, O="VeriSign, Inc.", C=US
* Subject: CN=RealVNC Ltd, O=RealVNC Ltd, L=Cambridge, S=Cambridgeshire, C=GB

## File Metadata

* Original Filename: vncserver.exe
* Product Name: VNC
* Company Name: RealVNC Ltd
* File Version: 6.1.1 (r28093)
* Product Version: 6.1.1 (r28093)
* Language: English (United Kingdom)
* Legal Copyright: Copyright  2002-2017 RealVNC Ltd.





MIT License. Copyright (c) 2020 Strontic.


