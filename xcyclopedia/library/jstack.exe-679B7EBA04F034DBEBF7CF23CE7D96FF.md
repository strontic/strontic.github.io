---
title: jstack.exe | OpenJDK Platform binary
---

# jstack.exe 

* File Path: `C:\program files\Amazon Corretto\jdk1.8.0_265\bin\jstack.exe`
* Description: OpenJDK Platform binary

## Hashes

Type | Hash
-- | --
MD5 | `679B7EBA04F034DBEBF7CF23CE7D96FF`
SHA1 | `79673D1E879219F5B69EBF930D9A02590CD88070`
SHA256 | `48F4E66DCB53AA0ECB9B12A7BBB0CCF7C8878F0E10AAC3109E012F352BDB3640`
SHA384 | `D8341BFC5466DA894E9D4E4A8B7215E661BC2598C93287693C9B2B035C05A74E87FB0C7681AAFCA2C4BB123358054010`
SHA512 | `202D59942E355C1DFF65DCB6780822E6A9402F7774CF4E903D4556ED673A7D4F9589579046F6365EAB418737107137EDA010CD33751134B75AD5696FBFD85BFB`
SSDEEP | `192:wvmg3Fzfn1fKVIKEfoHCscAyeEXw4yK6CYlLWwsUMAJ9b945Wa9sgfxIZHM:C751fKiKNHCsNyeEXwK6jSXApDgf2hM`

## Runtime Data

### Usage (stdout):
```cmhg
Attaching to remote server help, please wait...

```

### Usage (stderr):
```cmhg
Error attaching to remote server: java.rmi.ConnectException: Connection refused to host: 172.20.207.139; nested exception is: 
	java.net.ConnectException: Connection refused: connect
sun.jvm.hotspot.debugger.DebuggerException: java.rmi.ConnectException: Connection refused to host: 172.20.207.139; nested exception is: 
	java.net.ConnectException: Connection refused: connect
	at sun.jvm.hotspot.RMIHelper.lookup(RMIHelper.java:115)
	at sun.jvm.hotspot.HotSpotAgent.connectRemoteDebugger(HotSpotAgent.java:518)
	at sun.jvm.hotspot.HotSpotAgent.setupDebugger(HotSpotAgent.java:374)
	at sun.jvm.hotspot.HotSpotAgent.go(HotSpotAgent.java:304)
	at sun.jvm.hotspot.HotSpotAgent.attach(HotSpotAgent.java:183)
	at sun.jvm.hotspot.tools.Tool.start(Tool.java:196)
	at sun.jvm.hotspot.tools.Tool.execute(Tool.java:118)
	at sun.jvm.hotspot.tools.JStack.main(JStack.java:92)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at sun.tools.jstack.JStack.runJStackTool(JStack.java:140)
	at sun.tools.jstack.JStack.main(JStack.java:106)
Caused by: java.rmi.ConnectException: Connection refused to host: 172.20.207.139; nested exception is: 
	java.net.ConnectException: Connection refused: connect
	at sun.rmi.transport.tcp.TCPEndpoint.newSocket(TCPEndpoint.java:623)
	at sun.rmi.transport.tcp.TCPChannel.createConnection(TCPChannel.java:216)
	at sun.rmi.transport.tcp.TCPChannel.newConnection(TCPChannel.java:202)
	at sun.rmi.server.UnicastRef.newCall(UnicastRef.java:343)
	at sun.rmi.registry.RegistryImpl_Stub.lookup(RegistryImpl_Stub.java:116)
	at java.rmi.Naming.lookup(Naming.java:101)
	at sun.jvm.hotspot.RMIHelper.lookup(RMIHelper.java:113)
	... 13 more
Caused by: java.net.ConnectException: Connection refused: connect
	at java.net.DualStackPlainSocketImpl.connect0(Native Method)
	at java.net.DualStackPlainSocketImpl.socketConnect(DualStackPlainSocketImpl.java:79)
	at java.net.AbstractPlainSocketImpl.doConnect(AbstractPlainSocketImpl.java:350)
	at java.net.AbstractPlainSocketImpl.connectToAddress(AbstractPlainSocketImpl.java:206)
	at java.net.AbstractPlainSocketImpl.connect(AbstractPlainSocketImpl.java:188)
	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:172)
	at java.net.SocksSocketImpl.connect(SocksSocketImpl.java:392)
	at java.net.Socket.connect(Socket.java:607)
	at java.net.Socket.connect(Socket.java:556)
	at java.net.Socket.<init>(Socket.java:452)
	at java.net.Socket.<init>(Socket.java:229)
	at sun.rmi.transport.proxy.RMIDirectSocketFactory.createSocket(RMIDirectSocketFactory.java:40)
	at sun.rmi.transport.proxy.RMIMasterSocketFactory.createSocket(RMIMasterSocketFactory.java:148)
	at sun.rmi.transport.tcp.TCPEndpoint.newSocket(TCPEndpoint.java:617)
	... 19 more


```

### Child Processes:
conhost.exe

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Users\user\AppData\Local\Temp\hsperfdata_user\5740 | File
(R-D)   C:\Windows\System32\en-US\kernel32.dll.mui | File
(RW-)   C:\Program Files\Amazon Corretto\jdk1.8.0_265\jre\lib\ext\jfxrt.jar | File
(RW-)   C:\Program Files\Amazon Corretto\jdk1.8.0_265\jre\lib\jfr.jar | File
(RW-)   C:\Program Files\Amazon Corretto\jdk1.8.0_265\jre\lib\jsse.jar | File
(RW-)   C:\Program Files\Amazon Corretto\jdk1.8.0_265\jre\lib\rt.jar | File
(RW-)   C:\Program Files\Amazon Corretto\jdk1.8.0_265\lib\sa-jdi.jar | File
(RW-)   C:\Program Files\Amazon Corretto\jdk1.8.0_265\lib\tools.jar | File
(RW-)   C:\Users\user\Documents | File
(RW-)   C:\Windows\WinSxS\amd64_microsoft.windows.common-controls_6595b64144ccf1df_6.0.19041.1_none_b555e41d4684ddec | File
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\Sessions\1\BaseNamedObjects\hsperfdata_user_5740 | Section
\Sessions\1\BaseNamedObjects\windows_shell_global_counters | Section


### Loaded Modules:

Path |
-- |
C:\program files\Amazon Corretto\jdk1.8.0_265\bin\jstack.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `2F83C35B5136353D68CE9EB669FD1B0B`
* Thumbprint: `4BAD227329ADEF18F215B6475FB7948E1629B505`
* Issuer: CN=Symantec Class 3 SHA256 Code Signing CA, OU=Symantec Trust Network, O=Symantec Corporation, C=US
* Subject: CN=Amazon.com Services LLC, OU=Software Services, O=Amazon.com Services LLC, L=Seattle, S=Washington, C=US

## File Metadata

* Original Filename: jstack.exe
* Product Name: OpenJDK Platform 8
* Company Name: Amazon.com Inc.
* File Version: 8.0.2650.1
* Product Version: 8.0.2650.1
* Language: Language Neutral
* Legal Copyright: Copyright  2020

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\program files\Amazon Corretto\jdk1.8.0_265\bin\appletviewer.exe](appletviewer.exe-430C820B9C25F84873606F9577ED885C.md) | 54
[C:\program files\Amazon Corretto\jdk1.8.0_265\bin\clhsdb.exe](clhsdb.exe-E1BCE5AE504EC02D6CE72820D5C65104.md) | 55
[C:\program files\Amazon Corretto\jdk1.8.0_265\bin\extcheck.exe](extcheck.exe-1558E9C8EB7C811CE72AF08BBDE7BC1C.md) | 55
[C:\program files\Amazon Corretto\jdk1.8.0_265\bin\hsdb.exe](hsdb.exe-814D8D11A58015EF79936248A91FF87A.md) | 57
[C:\program files\Amazon Corretto\jdk1.8.0_265\bin\idlj.exe](idlj.exe-B8FF03F3747D2220B78EF20F5BDFB1A6.md) | 57
[C:\program files\Amazon Corretto\jdk1.8.0_265\bin\jar.exe](jar.exe-FDE3CD0231E7F936B7914D4BC1DEE713.md) | 55
[C:\program files\Amazon Corretto\jdk1.8.0_265\bin\jarsigner.exe](jarsigner.exe-916A8B80152B0A5F09F755A6B0F0CEEE.md) | 57
[C:\program files\Amazon Corretto\jdk1.8.0_265\bin\javac.exe](javac.exe-E1A9361E0F13035D3450B2E5BF9F565A.md) | 57
[C:\program files\Amazon Corretto\jdk1.8.0_265\bin\javadoc.exe](javadoc.exe-D58A3821C950F9A8810571758D454BF3.md) | 57
[C:\program files\Amazon Corretto\jdk1.8.0_265\bin\javah.exe](javah.exe-738EEF3648337D35FE7FDDAEDB7A7AE6.md) | 55
[C:\program files\Amazon Corretto\jdk1.8.0_265\bin\javap.exe](javap.exe-263625513CED1A2F3CC530A873DA78D8.md) | 57
[C:\program files\Amazon Corretto\jdk1.8.0_265\bin\jcmd.exe](jcmd.exe-2F08542DE06EE7A5312A3DA2EE2B24BC.md) | 58
[C:\program files\Amazon Corretto\jdk1.8.0_265\bin\jconsole.exe](jconsole.exe-F6A2528FAF7F94C21B6171C7714CF312.md) | 54
[C:\program files\Amazon Corretto\jdk1.8.0_265\bin\jdb.exe](jdb.exe-0D18C300EDB8083FE7DF9EBCB73272B7.md) | 57
[C:\program files\Amazon Corretto\jdk1.8.0_265\bin\jdeps.exe](jdeps.exe-6160FFF11CB9E55F3A5914649A287D42.md) | 58
[C:\program files\Amazon Corretto\jdk1.8.0_265\bin\jfr.exe](jfr.exe-963613DC729D1F04DBFC1AE070C62FBC.md) | 57
[C:\program files\Amazon Corretto\jdk1.8.0_265\bin\jhat.exe](jhat.exe-6775B43B078A43741B7A88D7C83E3250.md) | 57
[C:\program files\Amazon Corretto\jdk1.8.0_265\bin\jinfo.exe](jinfo.exe-698B44C29D5E55EA17046DB44381EAF7.md) | 69
[C:\program files\Amazon Corretto\jdk1.8.0_265\bin\jjs.exe](jjs.exe-59BBE7560FAA914F246C4E3F29662273.md) | 55
[C:\program files\Amazon Corretto\jdk1.8.0_265\bin\jmap.exe](jmap.exe-196C8715740CAA592B223567FC81892F.md) | 71
[C:\program files\Amazon Corretto\jdk1.8.0_265\bin\jps.exe](jps.exe-3E2339751905B0F23F2B60479567B4C5.md) | 61
[C:\program files\Amazon Corretto\jdk1.8.0_265\bin\jrunscript.exe](jrunscript.exe-26D55A136CF4A9375EBC15B1CC1E3A87.md) | 58
[C:\program files\Amazon Corretto\jdk1.8.0_265\bin\jsadebugd.exe](jsadebugd.exe-EDD35409A96C24BAA80F32D8A153DBD5.md) | 58
[C:\program files\Amazon Corretto\jdk1.8.0_265\bin\jstat.exe](jstat.exe-4D42D198AEA1B89EA69C6C1EB589A5CF.md) | 58
[C:\program files\Amazon Corretto\jdk1.8.0_265\bin\jstatd.exe](jstatd.exe-DCB5BED30B4C0C0DBB8909533ECB53FA.md) | 57
[C:\program files\Amazon Corretto\jdk1.8.0_265\bin\keytool.exe](keytool.exe-8E9FA6337C05EA19B49857407FE76324.md) | 54
[C:\program files\Amazon Corretto\jdk1.8.0_265\bin\klist.exe](klist.exe-46C3EFEFBB84EF261A21CE50DD82538B.md) | 54
[C:\program files\Amazon Corretto\jdk1.8.0_265\bin\native2ascii.exe](native2ascii.exe-4E0D48DBD27C912BAA95BB16392B98DA.md) | 55
[C:\program files\Amazon Corretto\jdk1.8.0_265\bin\orbd.exe](orbd.exe-88A71D46CF9DAD0A1A922B7A81FF3F94.md) | 65
[C:\program files\Amazon Corretto\jdk1.8.0_265\bin\pack200.exe](pack200.exe-194F7DAC4BF0CE689B11E658EE4BE4EC.md) | 58
[C:\program files\Amazon Corretto\jdk1.8.0_265\bin\policytool.exe](policytool.exe-84733E93F92F1C702AD8D51085A0C141.md) | 57
[C:\program files\Amazon Corretto\jdk1.8.0_265\bin\rmid.exe](rmid.exe-B2EC7C7A298A74A6A7FE6994EEA30AEB.md) | 57
[C:\program files\Amazon Corretto\jdk1.8.0_265\bin\rmiregistry.exe](rmiregistry.exe-A1B6A0957EDC2CE30464D592058BDCFF.md) | 57
[C:\program files\Amazon Corretto\jdk1.8.0_265\bin\schemagen.exe](schemagen.exe-2E0814457A3FA699E49A19A5951071A9.md) | 57
[C:\program files\Amazon Corretto\jdk1.8.0_265\bin\serialver.exe](serialver.exe-7E2682A55024756C0D6988648EC46F80.md) | 54
[C:\program files\Amazon Corretto\jdk1.8.0_265\bin\servertool.exe](servertool.exe-DA2C531652A2C306B02D9A7598ABFA86.md) | 57
[C:\program files\Amazon Corretto\jdk1.8.0_265\bin\tnameserv.exe](tnameserv.exe-B95BD13779CB322743ABB3C3AC406B1D.md) | 61
[C:\program files\Amazon Corretto\jdk1.8.0_265\bin\wsgen.exe](wsgen.exe-FE1C1F8495990F2BCB301E53BCAB2B79.md) | 57
[C:\program files\Amazon Corretto\jdk1.8.0_265\bin\wsimport.exe](wsimport.exe-1789534F6D671FA68ACD4FB49179C70B.md) | 57
[C:\program files\Amazon Corretto\jdk1.8.0_265\bin\xjc.exe](xjc.exe-D7067F41EA6E860CC7EFCEF110406D16.md) | 57
[C:\program files\Amazon Corretto\jdk1.8.0_265\jre\bin\java-rmi.exe](java-rmi.exe-2C8BE8549F5A30706D882BF98BA1F593.md) | 58
[C:\program files\Amazon Corretto\jdk1.8.0_265\jre\bin\jjs.exe](jjs.exe-83B89AADBE362DAAF3AEFDE9B90A7E70.md) | 55
[C:\program files\Amazon Corretto\jdk1.8.0_265\jre\bin\keytool.exe](keytool.exe-E64A133341297033FB908CF0412A32EC.md) | 55
[C:\program files\Amazon Corretto\jdk1.8.0_265\jre\bin\kinit.exe](kinit.exe-8279A6B305002709B2FA0E42D508F5B7.md) | 55
[C:\program files\Amazon Corretto\jdk1.8.0_265\jre\bin\klist.exe](klist.exe-CB6F44DE9B3831B042E93254E6C90991.md) | 54
[C:\program files\Amazon Corretto\jdk1.8.0_265\jre\bin\ktab.exe](ktab.exe-4E10E111BC97C675CFE3BF5A40E0D29F.md) | 55
[C:\program files\Amazon Corretto\jdk1.8.0_265\jre\bin\orbd.exe](orbd.exe-B7D6DFE20B64D0E89E2CAAC0918C7ABF.md) | 61
[C:\program files\Amazon Corretto\jdk1.8.0_265\jre\bin\pack200.exe](pack200.exe-3BA7B22C46AB4E39C166185B6C5644EB.md) | 57
[C:\program files\Amazon Corretto\jdk1.8.0_265\jre\bin\policytool.exe](policytool.exe-9000C71F8C10BE60FDC45CDCBF93D25B.md) | 54
[C:\program files\Amazon Corretto\jdk1.8.0_265\jre\bin\rmid.exe](rmid.exe-49EA4C57E276B964B770F36A4ACDD764.md) | 55
[C:\program files\Amazon Corretto\jdk1.8.0_265\jre\bin\rmiregistry.exe](rmiregistry.exe-AC45D66B78E93F793F684492A0A3BCF8.md) | 54
[C:\program files\Amazon Corretto\jdk1.8.0_265\jre\bin\servertool.exe](servertool.exe-7CC71DC253D94C84121954F54EB18BCA.md) | 57
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\javadoc.exe](javadoc.exe-0F018693795EEBE8E09C80212FA8F046.md) | 27
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\jconsole.exe](jconsole.exe-D8C95F3A553D05CB200221FFFB6BA28A.md) | 33
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\jinfo.exe](jinfo.exe-714D372EF77EB0C6C5F3DA8F7BAFED2F.md) | 30
[C:\program files\Amazon Corretto\jre8\bin\java-rmi.exe](java-rmi.exe-ABB442793EFD5B49BCBD985457471CBA.md) | 58
[C:\program files\Amazon Corretto\jre8\bin\jjs.exe](jjs.exe-88F2557464000E73373C35FC2F541DBD.md) | 54
[C:\program files\Amazon Corretto\jre8\bin\keytool.exe](keytool.exe-5B2EED8BF1F4AD2266D1AB4DACD5EFB5.md) | 55
[C:\program files\Amazon Corretto\jre8\bin\kinit.exe](kinit.exe-279AB5BC8B1580FBD051A17B03A105FC.md) | 57
[C:\program files\Amazon Corretto\jre8\bin\klist.exe](klist.exe-485D7DCE45873697DD951A75B3358C7A.md) | 55
[C:\program files\Amazon Corretto\jre8\bin\ktab.exe](ktab.exe-7273553C79E43A7A0FC111E39B2D7462.md) | 55
[C:\program files\Amazon Corretto\jre8\bin\orbd.exe](orbd.exe-D0E99C227083E332225BC7C56D66CC32.md) | 65
[C:\program files\Amazon Corretto\jre8\bin\pack200.exe](pack200.exe-A7A5CFDD68743FCA89B2006B483F778F.md) | 57
[C:\program files\Amazon Corretto\jre8\bin\policytool.exe](policytool.exe-1F96ACF1BC80FE1A0CAD540611C6EBC2.md) | 57
[C:\program files\Amazon Corretto\jre8\bin\rmid.exe](rmid.exe-216048544A1924DDFFD12C96094A23F1.md) | 57
[C:\program files\Amazon Corretto\jre8\bin\rmiregistry.exe](rmiregistry.exe-11A6CEF71C782AF4B29951C8EA0C4541.md) | 55
[C:\program files\Amazon Corretto\jre8\bin\tnameserv.exe](tnameserv.exe-0D875404AEA73CD0FCD92880DA829E70.md) | 61




MIT License. Copyright (c) 2020 Strontic.


