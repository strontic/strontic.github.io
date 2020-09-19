---
title: jcmd.exe | OpenJDK Platform binary
---

# jcmd.exe 

* File Path: `C:\program files\Amazon Corretto\jdk11.0.8_10\bin\jcmd.exe`
* Description: OpenJDK Platform binary

## Hashes

Type | Hash
-- | --
MD5 | `8B031007B293E1B238FE7040C1E78BA9`
SHA1 | `CD7F4158DC2D6C556F14E847C8F43D5BF1820B7D`
SHA256 | `10822DDECEB04E4E454BFBB3008E076281AA1E95B5DF2EC98E8C9D5E74C4D8E4`
SHA384 | `CFA4586F850E0820BD3CE1A99CF9F9A3F11A33BDA0ED3FBD339FE2BAEA45C2446651334E787E29395D800F841D3DF543`
SHA512 | `1B5C3E7106C86745CEA3F67C0B744263E5D83D5F2879892C12C5DB6936D2B1B76706F89490E15046332CDDFA3965C7360600C3369894ED74E57267BC90EA6613`
SSDEEP | `384:qbdNt3yyvpWABbFCu5AdRK6jSA5m5blDgf2hiF:+O+A+FCu5oKgpmTUf2h4`

## Runtime Data

### Usage (stdout):
```cmhg
Usage: jcmd <pid | main class> <command ...|PerfCounter.print|-f file>
   or: jcmd -l                                                    
   or: jcmd -h                                                    
                                                                  
  command must be a valid jcmd command for the selected jvm.      
  Use the command "help" to see which commands are available.   
  If the pid is 0, commands will be sent to all Java processes.   
  The main class argument will be used to match (either partially 
  or fully) the class used to start Java.                         
  If no options are given, lists Java processes (same as -l).     
                                                                  
  PerfCounter.print display the counters exposed by this process  
  -f  read and execute commands from the file                     
  -l  list JVM processes on the local machine                     
  -? -h --help print this help message                            

```

### Usage (stderr):
```cmhg
Could not find any processes matching : 'help'

```

### Loaded Modules:

Path |
-- |
C:\program files\Amazon Corretto\jdk11.0.8_10\bin\jcmd.exe |
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

* Original Filename: jcmd.exe
* Product Name: OpenJDK Platform 11
* Company Name: Amazon.com Inc.
* File Version: 11.0.8
* Product Version: 11.0.8
* Language: Language Neutral
* Legal Copyright: Copyright  2020

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jar.exe](jar.exe-B39F84FB8C26E73075627CF8A3E30B00.md) | 41
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\javap.exe](javap.exe-E53972D2FEB5711E552CE72695BF2572.md) | 35
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jcmd.exe](jcmd.exe-B264E0660D3BF070AAD25F2F033B9436.md) | 49
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jdeps.exe](jdeps.exe-A2D8568F6868C17A7A8C88B625FDB100.md) | 38
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jfr.exe](jfr.exe-08F03ABD9FF453E929D3232120C51BD7.md) | 46
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jimage.exe](jimage.exe-D25C31744405D6ACAA96E47DE6F8D837.md) | 40
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jmod.exe](jmod.exe-66A78959DA40CE102F7BB09A8C73395A.md) | 47
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jps.exe](jps.exe-8B98A486BF91B0F184B1C587BB2B680F.md) | 46
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jstat.exe](jstat.exe-92DD217A9387CDFD9D0F65CACD5DE308.md) | 38
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jstatd.exe](jstatd.exe-F51B29210060B0377FB4EA13AFD3FD9D.md) | 38
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\kinit.exe](kinit.exe-1D16A2748895E35498E4E22F15EB5AC0.md) | 38
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\klist.exe](klist.exe-9371A9AC3DC11410EA50EA8C21C83C89.md) | 43
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\ktab.exe](ktab.exe-C6FB113B79364970E2246CCFB40878D0.md) | 36
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\rmic.exe](rmic.exe-BBCF27C5346C3075D09DF7355AEBB582.md) | 44
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\rmid.exe](rmid.exe-D98CF348139BB44E4EFCA15FEA955F7C.md) | 43
[C:\program files\AdoptOpenJDK\jre-11.0.8.10-hotspot\bin\jfr.exe](jfr.exe-065E5E752266CD2FA6F1CF2564249B21.md) | 46
[C:\program files\AdoptOpenJDK\jre-11.0.8.10-hotspot\bin\kinit.exe](kinit.exe-17561E8FCB677496BC34D76B2F9BE380.md) | 40
[C:\program files\AdoptOpenJDK\jre-11.0.8.10-hotspot\bin\klist.exe](klist.exe-7D151D16C96009205B92251019F782AF.md) | 46
[C:\program files\AdoptOpenJDK\jre-11.0.8.10-hotspot\bin\ktab.exe](ktab.exe-F45CED87218ADC894C655258D1FC5C10.md) | 38
[C:\program files\AdoptOpenJDK\jre-11.0.8.10-hotspot\bin\rmid.exe](rmid.exe-62D6E0918BC131ABDB5F5A98A66346EF.md) | 43
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\jar.exe](jar.exe-90E9FDEDBD307AAD814B9B310EF9EEF6.md) | 66
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\javap.exe](javap.exe-5FDBAB868D53F447324D0CEC119EADF4.md) | 58
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\jdeps.exe](jdeps.exe-93A0053100DB342311A5461DC158F9C5.md) | 55
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\jfr.exe](jfr.exe-B33A8A8C02F57743444E9F96936783DE.md) | 63
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\jimage.exe](jimage.exe-52585947B2B10A2C41E370B60D85A837.md) | 57
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\jmod.exe](jmod.exe-FD6825DE6B411FB98408250B4242E4CF.md) | 65
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\jps.exe](jps.exe-EAB3A072CA16676197FF86E06CBA9F13.md) | 65
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\jstat.exe](jstat.exe-94511EDBA5FC73EF516B66FF0BBFF032.md) | 60
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\jstatd.exe](jstatd.exe-5B818E750FE168F05BFF9A30354DEF83.md) | 60
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\kinit.exe](kinit.exe-2E9727621161826FE230D5C529D4D57A.md) | 60
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\klist.exe](klist.exe-0114F130B4E2B2C847324EF3EE2231B1.md) | 60
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\ktab.exe](ktab.exe-F3797AE1D338EAA8C55B716127B2FE64.md) | 61
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\rmic.exe](rmic.exe-B0BE3B0798C023F1A21C4E066BAE9527.md) | 68
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\rmid.exe](rmid.exe-1D81A7BE447A5B0CF10B76D15B1C69BC.md) | 65




MIT License. Copyright (c) 2020 Strontic.


