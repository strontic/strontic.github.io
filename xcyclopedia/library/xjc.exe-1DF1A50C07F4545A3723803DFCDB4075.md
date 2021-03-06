﻿---
title: xjc.exe | OpenJDK Platform binary
excerpt: What is xjc.exe?
---

# xjc.exe 

* File Path: `C:\Program Files\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\xjc.exe`
* Description: OpenJDK Platform binary

## Hashes

Type | Hash
-- | --
MD5 | `1DF1A50C07F4545A3723803DFCDB4075`
SHA1 | `E7B443DC158F4803E908743CFA5CD6A1F875674C`
SHA256 | `CC0E35C2487276CBF10E1BE336E2C8742AF97E6D5B377ABAA8F0DF44AEADEC94`
SHA384 | `CF1207D193EDE252D886D94AAFBA2BD72969C4576B3FE18F8A4CD01DD03094F07B5E61C7FC480EA64D2D7323572B8A84`
SHA512 | `C983C13AF510B27E719C5D6AC858ABB04B32C90A4E1FCFD53ABA009CD22AEC5FD665E7D6FFDA678C88CFAC2A43B9781DD54BE3FE443ED130E801ABC0D9F41C8B`
SSDEEP | `192:OaTgL1l+gp8NPs2c6FMCito3z8eEBnYe+PjPV9j7mMaDWpHXonDI:DTEl+NNE2bFRiGoeEBnYPLV9+MaDGXf`
IMP | `4CE08A7677042CDA6B3152B9229A7EF4`
PESHA1 | `0BCCBDE1D8913FC86EB2B35BA8DA1C77DC17887A`
PE256 | `058EE95B512E76B6E094D139E33183FD463A4F0EC4D4944C328A1573C7A38A4A`

## Runtime Data

### Usage (stdout):
```cmhg
"/?" is neither a file name nor a URL

Usage: xjc [-options ...] <schema file/URL/dir/jar> ... [-b <bindinfo>] ...
If dir is specified, all schema files in it will be compiled.
If jar is specified, /META-INF/sun-jaxb.episode binding file will be compiled.
Options:
  -nv                :  do not perform strict validation of the input schema(s)
  -extension         :  allow vendor extensions - do not strictly follow the
                        Compatibility Rules and App E.2 from the JAXB Spec
  -b <file/dir>      :  specify external bindings files (each <file> must have its own -b)
                        If a directory is given, **/*.xjb is searched
  -d <dir>           :  generated files will go into this directory
  -p <pkg>           :  specifies the target package
  -httpproxy <proxy> :  set HTTP/HTTPS proxy. Format is [user[:password]@]proxyHost:proxyPort
  -httpproxyfile <f> :  Works like -httpproxy but takes the argument in a file to protect password 
  -classpath <arg>   :  specify where to find user class files
  -catalog <file>    :  specify catalog files to resolve external entity references
                        support TR9401, XCatalog, and OASIS XML Catalog format.
  -readOnly          :  generated files will be in read-only mode
  -npa               :  suppress generation of package level annotations (**/package-info.java)
  -no-header         :  suppress generation of a file header with timestamp
  -target (2.0|2.1)  :  behave like XJC 2.0 or 2.1 and generate code that doesnt use any 2.2 features.
  -encoding <encoding> :  specify character encoding for generated source files
  -enableIntrospection :  enable correct generation of Boolean getters/setters to enable Bean Introspection apis 
  -disableXmlSecurity  :  disables XML security features when parsing XML documents 
  -contentForWildcard  :  generates content property for types with multiple xs:any derived elements 
  -xmlschema         :  treat input as W3C XML Schema (default)
  -relaxng           :  treat input as RELAX NG (experimental,unsupported)
  -relaxng-compact   :  treat input as RELAX NG compact syntax (experimental,unsupported)
  -dtd               :  treat input as XML DTD (experimental,unsupported)
  -wsdl              :  treat input as WSDL and compile schemas inside it (experimental,unsupported)
  -verbose           :  be extra verbose
  -quiet             :  suppress compiler output
  -help              :  display this help message
  -version           :  display version information
  -fullversion       :  display full version information


Extensions:
  -Xinject-code      :  inject specified Java code fragments into the generated code
  -Xlocator          :  enable source location support for generated code
  -Xsync-methods     :  generate accessor methods with the 'synchronized' keyword
  -mark-generated    :  mark the generated code as @javax.annotation.Generated
  -episode <FILE>    :  generate the episode file for separate compilation
  -Xpropertyaccessors :  Use XmlAccessType PROPERTY instead of FIELD for generated classes

```

### Loaded Modules:

Path |
-- |
C:\Program Files\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\xjc.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `0F8CE162B26B70AE59D17A0B2A93AB3A`
* Thumbprint: `0180ED75D6615415E4D6C6C217613B4134F5745E`
* Issuer: CN=DigiCert SHA2 Assured ID Code Signing CA, OU=www.digicert.com, O=DigiCert Inc, C=US
* Subject: CN=London Jamocha Community CIC, O=London Jamocha Community CIC, L=London, C=GB

## File Metadata

* Original Filename: xjc.exe
* Product Name: OpenJDK Platform 8
* Company Name: AdoptOpenJDK
* File Version: 8.0.2650.1
* Product Version: 8.0.2650.1
* Language: Language Neutral
* Legal Copyright: Copyright  2020
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/cc0e35c2487276cbf10e1be336e2c8742af97e6d5b377abaa8f0df44aeadec94/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\program files (x86)\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\appletviewer.exe](appletviewer.exe-8B2AFBDF3801AF0800E2213AFC0DD3B2.md) | 46
[C:\program files (x86)\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\clhsdb.exe](clhsdb.exe-4462B22CBE4A3803DD68C3A559323BC8.md) | 47
[C:\program files (x86)\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\extcheck.exe](extcheck.exe-5B7CA96A112EC9393CF89B56BBFD4E10.md) | 46
[C:\program files (x86)\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\hsdb.exe](hsdb.exe-4A74D675BEBE12FFD07710D82878419A.md) | 46
[C:\program files (x86)\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\idlj.exe](idlj.exe-E541AAF75F9E5451E8E829C29028DEB2.md) | 49
[C:\program files (x86)\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\jar.exe](jar.exe-1ACA97C82BF21B32FC7F4A6FE6FAD804.md) | 47
[C:\program files (x86)\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\jarsigner.exe](jarsigner.exe-25DD8A98E86D003C76964E4FA180365D.md) | 47
[C:\program files (x86)\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\javac.exe](javac.exe-7ED9A465CE3ACE25CBFE7C1615F803E1.md) | 52
[C:\program files (x86)\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\javadoc.exe](javadoc.exe-FACB1C3F2F62B47F222992B36E97CAB6.md) | 50
[C:\program files (x86)\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\javah.exe](javah.exe-E2537DE1E52367640DE271759D1A3861.md) | 44
[C:\program files (x86)\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\javap.exe](javap.exe-9740243E1147E477EC8D20AD9116E04B.md) | 47
[C:\program files (x86)\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\java-rmi.exe](java-rmi.exe-A18AD9CF6E16E2EF7EAE37590DB95C35.md) | 47
[C:\program files (x86)\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\jcmd.exe](jcmd.exe-F78A5A7BAA25F56BADF6143DE746AC65.md) | 44
[C:\program files (x86)\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\jconsole.exe](jconsole.exe-369D7DE3BFB2BD85DD38C02D2B4AF189.md) | 55
[C:\program files (x86)\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\jdb.exe](jdb.exe-E59EE33622E60D6D0399C1A5816D289B.md) | 46
[C:\program files (x86)\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\jdeps.exe](jdeps.exe-C7FF656D1425A90376E6DE61FF51639D.md) | 47
[C:\program files (x86)\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\jfr.exe](jfr.exe-A4171515206972591F7E52424ACD3FB2.md) | 50
[C:\program files (x86)\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\jhat.exe](jhat.exe-379A337468B3B4A237FD77D76E6E8265.md) | 50
[C:\program files (x86)\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\jinfo.exe](jinfo.exe-8C907C49036D743DE51AEA04C48C69B1.md) | 41
[C:\program files (x86)\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\jjs.exe](jjs.exe-DF182B4B0E6C014AF35651B416126D94.md) | 44
[C:\program files (x86)\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\jmap.exe](jmap.exe-E3F84DF4BC91A528DD066ED684FD9969.md) | 44
[C:\program files (x86)\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\jps.exe](jps.exe-C0157310EEB7ACAB423E88BBB344946A.md) | 44
[C:\program files (x86)\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\jrunscript.exe](jrunscript.exe-314714D44C1552096A1AC5ABA8886BBD.md) | 43
[C:\program files (x86)\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\jsadebugd.exe](jsadebugd.exe-CF1C67FD7FDD07D906DACAE8FB861E70.md) | 47
[C:\program files (x86)\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\jstack.exe](jstack.exe-2093F5A2EC2B70F3973B12A22C6650B5.md) | 41
[C:\program files (x86)\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\jstat.exe](jstat.exe-448204E94CCFA655F17627C17DB30441.md) | 50
[C:\program files (x86)\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\jstatd.exe](jstatd.exe-61E2DF17AD3D11EE19A9466766BEC8F8.md) | 50
[C:\program files (x86)\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\keytool.exe](keytool.exe-09A99ABD22E692AEB2BB70A25EDAB980.md) | 44
[C:\program files (x86)\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\kinit.exe](kinit.exe-4D3EC4689DEE85AFBDBCD73F47C7F756.md) | 47
[C:\program files (x86)\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\klist.exe](klist.exe-0633AD2E27EA23748B3FF28B6B4F6840.md) | 49
[C:\program files (x86)\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\ktab.exe](ktab.exe-23491140F6114DD8C6DACA0AA29C8810.md) | 47
[C:\program files (x86)\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\native2ascii.exe](native2ascii.exe-66C9929371D91CB4ACA6C50D27AA1990.md) | 44
[C:\program files (x86)\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\orbd.exe](orbd.exe-CBC3DA3B0096E825DEA84FDAAE887650.md) | 44
[C:\program files (x86)\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\pack200.exe](pack200.exe-B883C39E732F2B1D6CCF303D1D9D186C.md) | 44
[C:\program files (x86)\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\policytool.exe](policytool.exe-B91882B30EA0A941913929ECD4E38DE6.md) | 49
[C:\program files (x86)\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\rmic.exe](rmic.exe-04A10ADC2D42F9B4163EC33A2436006A.md) | 44
[C:\program files (x86)\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\rmid.exe](rmid.exe-F827A11AC4698373A334914643F225E8.md) | 43
[C:\program files (x86)\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\rmiregistry.exe](rmiregistry.exe-60848F859ACC409A9F6122AD8D66787A.md) | 43
[C:\program files (x86)\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\schemagen.exe](schemagen.exe-B2BCF4F17094C431C3F32B416AAB28ED.md) | 47
[C:\program files (x86)\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\serialver.exe](serialver.exe-3A8E2FA5AB97E04E189CBAA9A80C4F27.md) | 44
[C:\program files (x86)\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\servertool.exe](servertool.exe-C99BDB68E24464838D5284F83249B356.md) | 47
[C:\program files (x86)\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\tnameserv.exe](tnameserv.exe-07043B6FDEF4E414FC93761BED3C6F02.md) | 41
[C:\program files (x86)\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\wsgen.exe](wsgen.exe-E61554ABB0B8E4942AD15FCE1B91A1CF.md) | 44
[C:\program files (x86)\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\wsimport.exe](wsimport.exe-C77714E3C5847DCE2E98738B83887DF9.md) | 50
[C:\program files (x86)\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\xjc.exe](xjc.exe-3FE983CB98200D1C15E85335D325E259.md) | 49
[C:\program files (x86)\AdoptOpenJDK\jdk-8.0.265.01-hotspot\jre\bin\java-rmi.exe](java-rmi.exe-6498A0415245011162A09AC292DCD8C0.md) | 47
[C:\program files (x86)\AdoptOpenJDK\jdk-8.0.265.01-hotspot\jre\bin\jjs.exe](jjs.exe-C69442017558A554CA8495B9463641C0.md) | 43
[C:\program files (x86)\AdoptOpenJDK\jdk-8.0.265.01-hotspot\jre\bin\keytool.exe](keytool.exe-C6EEF657D7BAE4DE81A982C2029F7B43.md) | 44
[C:\program files (x86)\AdoptOpenJDK\jdk-8.0.265.01-hotspot\jre\bin\kinit.exe](kinit.exe-71F6472A7F750B7B88A75CA3BD50350D.md) | 49
[C:\program files (x86)\AdoptOpenJDK\jdk-8.0.265.01-hotspot\jre\bin\klist.exe](klist.exe-A8A806B8486794E666EDB9257367D021.md) | 50
[C:\program files (x86)\AdoptOpenJDK\jdk-8.0.265.01-hotspot\jre\bin\ktab.exe](ktab.exe-521C838680C8680CF8541E9FDD55DCDA.md) | 47
[C:\program files (x86)\AdoptOpenJDK\jdk-8.0.265.01-hotspot\jre\bin\orbd.exe](orbd.exe-A670F331A88E7B98CAB021CAFDD9C696.md) | 44
[C:\program files (x86)\AdoptOpenJDK\jdk-8.0.265.01-hotspot\jre\bin\pack200.exe](pack200.exe-685340AEF03FCAD6CEE33F962EB8FC21.md) | 44
[C:\program files (x86)\AdoptOpenJDK\jdk-8.0.265.01-hotspot\jre\bin\policytool.exe](policytool.exe-1939A33F4CBA4A36A1CA13C14E7E321A.md) | 49
[C:\program files (x86)\AdoptOpenJDK\jdk-8.0.265.01-hotspot\jre\bin\rmid.exe](rmid.exe-5AEFED999CB9433AE1CAE2EDDB382CC4.md) | 43
[C:\program files (x86)\AdoptOpenJDK\jdk-8.0.265.01-hotspot\jre\bin\rmiregistry.exe](rmiregistry.exe-6F59700C2D393AD001AECFD9863EE29D.md) | 43
[C:\program files (x86)\AdoptOpenJDK\jdk-8.0.265.01-hotspot\jre\bin\servertool.exe](servertool.exe-5DBC1B6B14A838CB395AACE5B53336A3.md) | 47
[C:\program files (x86)\AdoptOpenJDK\jdk-8.0.265.01-hotspot\jre\bin\tnameserv.exe](tnameserv.exe-8120F40061AE2820D2AB58F5DF99BFDE.md) | 43
[C:\program files (x86)\AdoptOpenJDK\jre-8.0.265.01-hotspot\bin\java-rmi.exe](java-rmi.exe-014D61FA66D2D75CCC29766E775F56D5.md) | 50
[C:\program files (x86)\AdoptOpenJDK\jre-8.0.265.01-hotspot\bin\jjs.exe](jjs.exe-5EA290DAF79791093BB64E96F388EF9E.md) | 44
[C:\program files (x86)\AdoptOpenJDK\jre-8.0.265.01-hotspot\bin\keytool.exe](keytool.exe-F8C82712D4F8BDDF6EEFA394670E9BBD.md) | 44
[C:\program files (x86)\AdoptOpenJDK\jre-8.0.265.01-hotspot\bin\kinit.exe](kinit.exe-FE61BA407D0C300C6384ED2B7183607D.md) | 47
[C:\program files (x86)\AdoptOpenJDK\jre-8.0.265.01-hotspot\bin\klist.exe](klist.exe-BB6FF1A2A4E8379B74AAF7439A795E71.md) | 49
[C:\program files (x86)\AdoptOpenJDK\jre-8.0.265.01-hotspot\bin\ktab.exe](ktab.exe-723F60653A333342871CC77AC379A313.md) | 47
[C:\program files (x86)\AdoptOpenJDK\jre-8.0.265.01-hotspot\bin\orbd.exe](orbd.exe-1438ACCCDA9E33E59B2F9EEBFA7F4FAE.md) | 44
[C:\program files (x86)\AdoptOpenJDK\jre-8.0.265.01-hotspot\bin\pack200.exe](pack200.exe-BA072EAF1B1D7FF9469B78D21A290F60.md) | 44
[C:\program files (x86)\AdoptOpenJDK\jre-8.0.265.01-hotspot\bin\policytool.exe](policytool.exe-26835215DCD280D2FC45B51CCC0E89C3.md) | 47
[C:\program files (x86)\AdoptOpenJDK\jre-8.0.265.01-hotspot\bin\rmid.exe](rmid.exe-6DC74358605BF9D04DD8345A9630651E.md) | 43
[C:\program files (x86)\AdoptOpenJDK\jre-8.0.265.01-hotspot\bin\rmiregistry.exe](rmiregistry.exe-C80D5CABB52A12F93C1EF0B711BDD767.md) | 46
[C:\program files (x86)\AdoptOpenJDK\jre-8.0.265.01-hotspot\bin\servertool.exe](servertool.exe-550437F1F282DF05DBF7A59C65D937E9.md) | 46
[C:\program files (x86)\AdoptOpenJDK\jre-8.0.265.01-hotspot\bin\tnameserv.exe](tnameserv.exe-DB78E88209743CC938B665DFA0401A25.md) | 43
[C:\Program Files (x86)\GRETECH\GomPlayer\KillGom.exe](KillGom.exe-37B7D35855260B524B68AF4F748448BE.md) | 25
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jaotc.exe](jaotc.exe-96EA8F503210EF7E3A39EEF68AE137D0.md) | 47
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jar.exe](jar.exe-B39F84FB8C26E73075627CF8A3E30B00.md) | 43
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jarsigner.exe](jarsigner.exe-3545DF7A746A46163EA98D79A3CFAA65.md) | 47
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\javac.exe](javac.exe-3AF21D2F89F7E5A7409CF655538E4908.md) | 47
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\javadoc.exe](javadoc.exe-EF717EE4EF966F1CB64154D5B53FB537.md) | 49
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\javap.exe](javap.exe-E53972D2FEB5711E552CE72695BF2572.md) | 44
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jcmd.exe](jcmd.exe-B264E0660D3BF070AAD25F2F033B9436.md) | 44
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jconsole.exe](jconsole.exe-9E7A7D56EC8DF94D80191E5F031863E0.md) | 43
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jdb.exe](jdb.exe-B66DF0DC0BDF18F4A14DFC6A58F23BAB.md) | 49
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jdeprscan.exe](jdeprscan.exe-F63BEA1831254EB65EEA19012774C7B9.md) | 44
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jdeps.exe](jdeps.exe-A2D8568F6868C17A7A8C88B625FDB100.md) | 41
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jfr.exe](jfr.exe-08F03ABD9FF453E929D3232120C51BD7.md) | 47
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jhsdb.exe](jhsdb.exe-61D7659F3C8D10C62224634404D1A91F.md) | 44
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jimage.exe](jimage.exe-D25C31744405D6ACAA96E47DE6F8D837.md) | 44
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jinfo.exe](jinfo.exe-01D9976C008E5BEB543FF8CC974580F9.md) | 47
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jjs.exe](jjs.exe-769519D4B82D6F7FF7C779C74BCA82CF.md) | 38
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jlink.exe](jlink.exe-15C86A7D8376EC476DD2AE27EAEE31D1.md) | 47
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jmap.exe](jmap.exe-04C49823E33A3ABCF73C414C8329F37A.md) | 46
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jmod.exe](jmod.exe-66A78959DA40CE102F7BB09A8C73395A.md) | 46
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jps.exe](jps.exe-8B98A486BF91B0F184B1C587BB2B680F.md) | 47
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jrunscript.exe](jrunscript.exe-B8C457CC6E8878FC4E78DF87FE69A04F.md) | 44
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jshell.exe](jshell.exe-7102DE0DBB816DFE04784CDDDF0EABC9.md) | 47
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jstack.exe](jstack.exe-71672EE296B2EA44D74B3B592D70F29B.md) | 47
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jstat.exe](jstat.exe-92DD217A9387CDFD9D0F65CACD5DE308.md) | 43
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jstatd.exe](jstatd.exe-F51B29210060B0377FB4EA13AFD3FD9D.md) | 44
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\keytool.exe](keytool.exe-F859E5BDEA1498C82945E824021AB601.md) | 44
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\kinit.exe](kinit.exe-1D16A2748895E35498E4E22F15EB5AC0.md) | 46
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\klist.exe](klist.exe-9371A9AC3DC11410EA50EA8C21C83C89.md) | 50
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\ktab.exe](ktab.exe-C6FB113B79364970E2246CCFB40878D0.md) | 44
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\pack200.exe](pack200.exe-DC5AA7BCD19D6CE293F14AE57C3082EC.md) | 46
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\rmic.exe](rmic.exe-BBCF27C5346C3075D09DF7355AEBB582.md) | 46
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\rmid.exe](rmid.exe-D98CF348139BB44E4EFCA15FEA955F7C.md) | 44
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\rmiregistry.exe](rmiregistry.exe-6240D6F87038D7B1F32E590D20B6EB45.md) | 43
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\serialver.exe](serialver.exe-8C875F970BA9AFB45B48DF121220D535.md) | 46
[C:\Program Files\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\appletviewer.exe](appletviewer.exe-452F617B43E0052B9AB66B7FFA9E10C1.md) | 60
[C:\Program Files\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\clhsdb.exe](clhsdb.exe-AAB473B7D1752B5FA110A197326D097E.md) | 60
[C:\Program Files\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\extcheck.exe](extcheck.exe-00E9757CA12E6048C880E1712B20072A.md) | 57
[C:\Program Files\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\hsdb.exe](hsdb.exe-74ACF1B01D760B7945569B318212CB77.md) | 60
[C:\Program Files\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\idlj.exe](idlj.exe-3B8B42E602DFDB525CC42F5A91659369.md) | 71
[C:\Program Files\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\jar.exe](jar.exe-C4EF2186F19802E43BC972CAB954846D.md) | 69
[C:\Program Files\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\jarsigner.exe](jarsigner.exe-A51098C1FEDE268905DA223733564F0E.md) | 75
[C:\Program Files\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\javac.exe](javac.exe-516BEE30A2C5F0EB81CB68CAF8CA1D1F.md) | 54
[C:\Program Files\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\javadoc.exe](javadoc.exe-44EC7B2CBD3D5C34D89D0955BAD6DE42.md) | 55
[C:\Program Files\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\javah.exe](javah.exe-37112E80D331E4AC2EFD2B6A7F9CC666.md) | 60
[C:\Program Files\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\javap.exe](javap.exe-CDD3D45E98CF83A3A04189791D9D53A8.md) | 50
[C:\Program Files\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\java-rmi.exe](java-rmi.exe-9B53C80BB45BB9B5EDF8A691DBBBBA59.md) | 60
[C:\Program Files\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\jcmd.exe](jcmd.exe-EED2291F53953A6CCD07727A82D38F6E.md) | 71
[C:\Program Files\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\jconsole.exe](jconsole.exe-AEE0E28C80DD48C728D3E04B63AD0DBB.md) | 57
[C:\Program Files\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\jdb.exe](jdb.exe-A59677E5E21E2F8D6DD457214F5383B1.md) | 57
[C:\Program Files\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\jdeps.exe](jdeps.exe-1FA81F74862BE01CE96CD8BB0BC8EFB0.md) | 55
[C:\Program Files\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\jfr.exe](jfr.exe-2086CD29FB600A1205F335CBC25081E4.md) | 66
[C:\Program Files\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\jhat.exe](jhat.exe-0E8A7F5E3DFBC6CFA3318DC81C2E662F.md) | 72
[C:\Program Files\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\jinfo.exe](jinfo.exe-2F310FF2B5631AF61631BCE97024E9EC.md) | 55
[C:\Program Files\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\jjs.exe](jjs.exe-9B47057EB9B5E0598F3AA87DFAB689E9.md) | 68
[C:\Program Files\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\jmap.exe](jmap.exe-9F8853E65C86243BF3EAF7F74C85B434.md) | 57
[C:\Program Files\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\jps.exe](jps.exe-54E27CAE3F9F744B8EBD207F9AE926EC.md) | 68
[C:\Program Files\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\jrunscript.exe](jrunscript.exe-DA8FB2490CCF57F9D2E15D41371A66EF.md) | 71
[C:\Program Files\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\jsadebugd.exe](jsadebugd.exe-D611C5E607F83CBCB7318A1620F17264.md) | 57
[C:\Program Files\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\jstack.exe](jstack.exe-BFE52EE05423B954BEB4AB4C53CE9A2C.md) | 55
[C:\Program Files\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\jstat.exe](jstat.exe-4CF32887C994D0BCDEDBEA8FA7224EB3.md) | 68
[C:\Program Files\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\jstatd.exe](jstatd.exe-DBE9EE30728ACA2053D828452F425DF1.md) | 63
[C:\Program Files\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\keytool.exe](keytool.exe-E2A0D9DAA4262F3CEF19CA8F99971993.md) | 66
[C:\Program Files\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\kinit.exe](kinit.exe-C96A8BA772B27E5425A09E1DD29810FB.md) | 66
[C:\Program Files\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\klist.exe](klist.exe-DEDBEDA995C571246734195BF0D5FF03.md) | 74
[C:\Program Files\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\ktab.exe](ktab.exe-732B4FD2433212EAEED20C130D34B9A4.md) | 77
[C:\Program Files\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\native2ascii.exe](native2ascii.exe-147576C8F8C1C2974FCB477CD0DDF0BD.md) | 69
[C:\Program Files\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\orbd.exe](orbd.exe-6E3AE4A3C0076DDB935DBCFDE6F23D08.md) | 57
[C:\Program Files\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\pack200.exe](pack200.exe-8438084723AFA7F34D28B141363503ED.md) | 77
[C:\Program Files\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\policytool.exe](policytool.exe-3AE610E3F18185F0363DDA2CBCAC88B4.md) | 71
[C:\Program Files\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\rmic.exe](rmic.exe-4BDC105AB47CBA6ADA728FB799DD92F5.md) | 60
[C:\Program Files\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\rmid.exe](rmid.exe-E5F3CBA5F6C8D0ED462379DA5CB87AE6.md) | 71
[C:\Program Files\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\rmiregistry.exe](rmiregistry.exe-411160E594F717D03B278992D287E919.md) | 69
[C:\Program Files\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\schemagen.exe](schemagen.exe-66A0089BE433BFE8C870742EFA0A7F72.md) | 72
[C:\Program Files\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\serialver.exe](serialver.exe-347EFCDEEF9D847085D0D2BCD3EBBF90.md) | 71
[C:\Program Files\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\servertool.exe](servertool.exe-9A71B71C85E6E109A8948FC96781385A.md) | 57
[C:\Program Files\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\tnameserv.exe](tnameserv.exe-4B14989D92B608AE2032C1AC6731E948.md) | 63
[C:\Program Files\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\wsgen.exe](wsgen.exe-AE956BB3C06F9822C4D3E92DF000D019.md) | 69
[C:\Program Files\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\wsimport.exe](wsimport.exe-EAC7415E31BA88DDCEBF4BD79206A5F5.md) | 75
[C:\Program Files\AdoptOpenJDK\jdk-8.0.265.01-hotspot\jre\bin\java-rmi.exe](java-rmi.exe-5599CA2F91315E30C2EDDB12FCDEA6D8.md) | 58
[C:\Program Files\AdoptOpenJDK\jdk-8.0.265.01-hotspot\jre\bin\jjs.exe](jjs.exe-F5BAAB25BB78D8C989DE4C25805EF750.md) | 69
[C:\Program Files\AdoptOpenJDK\jdk-8.0.265.01-hotspot\jre\bin\keytool.exe](keytool.exe-DB2C6EE1ABB141E832C69A6941C00624.md) | 57
[C:\Program Files\AdoptOpenJDK\jdk-8.0.265.01-hotspot\jre\bin\kinit.exe](kinit.exe-8642901DFEC6892CC169786E8E7C133A.md) | 77
[C:\Program Files\AdoptOpenJDK\jdk-8.0.265.01-hotspot\jre\bin\klist.exe](klist.exe-558FAD6023A99926C599A2EC768DEF45.md) | 77
[C:\Program Files\AdoptOpenJDK\jdk-8.0.265.01-hotspot\jre\bin\ktab.exe](ktab.exe-C6AB70C482BB08FCD9F0BF5CA27DAF03.md) | 69
[C:\Program Files\AdoptOpenJDK\jdk-8.0.265.01-hotspot\jre\bin\orbd.exe](orbd.exe-E81B78B77B095BCA838444D61069E057.md) | 60
[C:\Program Files\AdoptOpenJDK\jdk-8.0.265.01-hotspot\jre\bin\pack200.exe](pack200.exe-5D8DA453A34C247B2C72694D2AB17FE1.md) | 79
[C:\Program Files\AdoptOpenJDK\jdk-8.0.265.01-hotspot\jre\bin\policytool.exe](policytool.exe-BE2B28FFF82B71CE4C7311352DE2CE9F.md) | 72
[C:\Program Files\AdoptOpenJDK\jdk-8.0.265.01-hotspot\jre\bin\rmid.exe](rmid.exe-0D6C8AB547A0BC0F22D3EA5648ABC933.md) | 72
[C:\Program Files\AdoptOpenJDK\jdk-8.0.265.01-hotspot\jre\bin\rmiregistry.exe](rmiregistry.exe-BDA2442FBC8F89510F832D802B6D31DF.md) | 68
[C:\Program Files\AdoptOpenJDK\jdk-8.0.265.01-hotspot\jre\bin\servertool.exe](servertool.exe-FEC5BD7AEEC4F9CD039C7E7CF8C1FDC2.md) | 71
[C:\Program Files\AdoptOpenJDK\jdk-8.0.265.01-hotspot\jre\bin\tnameserv.exe](tnameserv.exe-E82A70E69F1961614B58C5D57CF6D69C.md) | 63
[C:\program files\AdoptOpenJDK\jre-11.0.8.10-hotspot\bin\jaotc.exe](jaotc.exe-FA423CD06BE535088F629C821F437452.md) | 47
[C:\program files\AdoptOpenJDK\jre-11.0.8.10-hotspot\bin\jfr.exe](jfr.exe-065E5E752266CD2FA6F1CF2564249B21.md) | 47
[C:\program files\AdoptOpenJDK\jre-11.0.8.10-hotspot\bin\jjs.exe](jjs.exe-4BBAAAD09CA86598C402F02D56D521A7.md) | 41
[C:\program files\AdoptOpenJDK\jre-11.0.8.10-hotspot\bin\jrunscript.exe](jrunscript.exe-7C4A5CAEF06DF2591580E764C20610EB.md) | 44
[C:\program files\AdoptOpenJDK\jre-11.0.8.10-hotspot\bin\keytool.exe](keytool.exe-0EA9E813BC45594BC7B505FD193D233D.md) | 44
[C:\program files\AdoptOpenJDK\jre-11.0.8.10-hotspot\bin\kinit.exe](kinit.exe-17561E8FCB677496BC34D76B2F9BE380.md) | 46
[C:\program files\AdoptOpenJDK\jre-11.0.8.10-hotspot\bin\klist.exe](klist.exe-7D151D16C96009205B92251019F782AF.md) | 50
[C:\program files\AdoptOpenJDK\jre-11.0.8.10-hotspot\bin\ktab.exe](ktab.exe-F45CED87218ADC894C655258D1FC5C10.md) | 44
[C:\program files\AdoptOpenJDK\jre-11.0.8.10-hotspot\bin\pack200.exe](pack200.exe-D8F4EAC78AB739846BD1D5BBD256DBC3.md) | 47
[C:\program files\AdoptOpenJDK\jre-11.0.8.10-hotspot\bin\rmid.exe](rmid.exe-62D6E0918BC131ABDB5F5A98A66346EF.md) | 44
[C:\program files\AdoptOpenJDK\jre-11.0.8.10-hotspot\bin\rmiregistry.exe](rmiregistry.exe-37B63F925D45FD055BA4A604F7E5F891.md) | 43
[C:\Program Files\AdoptOpenJDK\jre-8.0.265.01-hotspot\bin\java-rmi.exe](java-rmi.exe-94D5085F3D92FE0F4C09D84522076474.md) | 60
[C:\Program Files\AdoptOpenJDK\jre-8.0.265.01-hotspot\bin\jjs.exe](jjs.exe-E8F2F0963FE4BC13C4C8FE26B01FAD45.md) | 69
[C:\Program Files\AdoptOpenJDK\jre-8.0.265.01-hotspot\bin\keytool.exe](keytool.exe-0BD92FF2056898CFF0F623DF73455036.md) | 68
[C:\Program Files\AdoptOpenJDK\jre-8.0.265.01-hotspot\bin\kinit.exe](kinit.exe-13B98A07A136F0B5B1DC66842FBD4029.md) | 77
[C:\Program Files\AdoptOpenJDK\jre-8.0.265.01-hotspot\bin\klist.exe](klist.exe-0D568C427EC1BF20752D10A0EECFA706.md) | 75
[C:\Program Files\AdoptOpenJDK\jre-8.0.265.01-hotspot\bin\ktab.exe](ktab.exe-C99C2C19C464F768ADC67B88FB83EAA8.md) | 66
[C:\Program Files\AdoptOpenJDK\jre-8.0.265.01-hotspot\bin\orbd.exe](orbd.exe-A54184901C0B1CD198F7217ED40B0072.md) | 58
[C:\Program Files\AdoptOpenJDK\jre-8.0.265.01-hotspot\bin\pack200.exe](pack200.exe-DBA39D8D09C4821F0A4AC3AAB4AA2E80.md) | 77
[C:\Program Files\AdoptOpenJDK\jre-8.0.265.01-hotspot\bin\policytool.exe](policytool.exe-365F11C75165E4647C9B46B5C3382AE4.md) | 57
[C:\Program Files\AdoptOpenJDK\jre-8.0.265.01-hotspot\bin\rmid.exe](rmid.exe-65A00A5E7129B6FFAA015A814E438F40.md) | 71
[C:\Program Files\AdoptOpenJDK\jre-8.0.265.01-hotspot\bin\rmiregistry.exe](rmiregistry.exe-A46A476D2961404E0DD3F2652CFA4B23.md) | 57
[C:\Program Files\AdoptOpenJDK\jre-8.0.265.01-hotspot\bin\servertool.exe](servertool.exe-FF6FAFFF307A92D012ABBF84FC5DE132.md) | 69
[C:\Program Files\AdoptOpenJDK\jre-8.0.265.01-hotspot\bin\tnameserv.exe](tnameserv.exe-F41937DA12ADFBBE9E92AD99F8039A9F.md) | 63




MIT License. Copyright (c) 2020-2021 Strontic.


