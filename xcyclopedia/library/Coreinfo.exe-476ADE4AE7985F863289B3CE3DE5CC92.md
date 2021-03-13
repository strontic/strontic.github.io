---
title: Coreinfo.exe | Dump information on system CPU and memory topology
excerpt: What is Coreinfo.exe?
---

# Coreinfo.exe 

* File Path: `C:\SysinternalsSuite\Coreinfo.exe`
* Description: Dump information on system CPU and memory topology

## Hashes

Type | Hash
-- | --
MD5 | `476ADE4AE7985F863289B3CE3DE5CC92`
SHA1 | `16EDC8C4A717EBBE074075A413E576610070DA92`
SHA256 | `D93E8067C68AC71928FB963FCBA332E91004CBAC8B85763E8C6CF19E2AB29895`
SHA384 | `40DBF9F5DBD4FBE94084077E395F3A489682D7A8A74E97AE15AF443408877853D62FCA44937079BB36CDE97F30F8E9B3`
SHA512 | `AF730294C9B6CF0D46F3EADED0B452934424193EA6804EEE1CF85BB7549E0C8C19CC421E9FDBAD8AA1957C0AFC4804349080D8C59765E0AD6804EDA8DB07F684`
SSDEEP | `12288:PYnTks8zVM/y/Rlgbz8YgXdG729dgWQqq:PoTZ4lgb4tdG729dgdq`
IMP | `7C78CBC09CC5E1EA3BD973E23E82523A`
PESHA1 | `CDA84A73B25B807669B8EC9FD0D4589AEF48184B`
PE256 | `924B573616EECF95CFCC83B93BB2146F2567767EAFDD26E9B61C01B9646D2551`

## Runtime Data

### Usage (stdout):
```cmhg

Coreinfo v3.5 - Dump information on system CPU and memory topology
Copyright (C) 2008-2020 Mark Russinovich
Sysinternals - www.sysinternals.com


Intel(R) Core(TM) i7-4700MQ CPU @ 2.40GHz
Intel64 Family 6 Model 60 Stepping 3, GenuineIntel
Microcode signature: FFFFFFFF
HTT       	*	Hyperthreading enabled
HYPERVISOR	*	Hypervisor is present
VMX       	-	Supports Intel hardware-assisted virtualization
SVM       	-	Supports AMD hardware-assisted virtualization
X64       	*	Supports 64-bit mode

SMX       	-	Supports Intel trusted execution
SKINIT    	-	Supports AMD SKINIT

NX        	*	Supports no-execute page protection
SMEP      	*	Supports Supervisor Mode Execution Prevention
SMAP      	-	Supports Supervisor Mode Access Prevention
PAGE1GB   	*	Supports 1 GB large pages
PAE       	*	Supports > 32-bit physical addresses
PAT       	*	Supports Page Attribute Table
PSE       	*	Supports 4 MB pages
PSE36     	*	Supports > 32-bit address 4 MB pages
PGE       	*	Supports global bit in page tables
SS        	*	Supports bus snooping for cache operations
VME       	*	Supports Virtual-8086 mode
RDWRFSGSBASE	*	Supports direct GS/FS base access

FPU       	*	Implements i387 floating point instructions
MMX       	*	Supports MMX instruction set
MMXEXT    	-	Implements AMD MMX extensions
3DNOW     	-	Supports 3DNow! instructions
3DNOWEXT  	-	Supports 3DNow! extension instructions
SSE       	*	Supports Streaming SIMD Extensions
SSE2      	*	Supports Streaming SIMD Extensions 2
SSE3      	*	Supports Streaming SIMD Extensions 3
SSSE3     	*	Supports Supplemental SIMD Extensions 3
SSE4a     	-	Supports Streaming SIMDR Extensions 4a
SSE4.1    	*	Supports Streaming SIMD Extensions 4.1
SSE4.2    	*	Supports Streaming SIMD Extensions 4.2

AES       	*	Supports AES extensions
AVX       	*	Supports AVX instruction extensions
FMA       	*	Supports FMA extensions using YMM state
MSR       	*	Implements RDMSR/WRMSR instructions
MTRR      	*	Supports Memory Type Range Registers
XSAVE     	*	Supports XSAVE/XRSTOR instructions
OSXSAVE   	*	Supports XSETBV/XGETBV instructions
RDRAND    	*	Supports RDRAND instruction
RDSEED    	-	Supports RDSEED instruction

CMOV      	*	Supports CMOVcc instruction
CLFSH     	*	Supports CLFLUSH instruction
CX8       	*	Supports compare and exchange 8-byte instructions
CX16      	*	Supports CMPXCHG16B instruction
BMI1      	*	Supports bit manipulation extensions 1
BMI2      	*	Supports bit manipulation extensions 2
ADX       	-	Supports ADCX/ADOX instructions
DCA       	-	Supports prefetch from memory-mapped device
F16C      	*	Supports half-precision instruction
FXSR      	*	Supports FXSAVE/FXSTOR instructions
FFXSR     	-	Supports optimized FXSAVE/FSRSTOR instruction
MONITOR   	-	Supports MONITOR and MWAIT instructions
MOVBE     	*	Supports MOVBE instruction
ERMSB     	*	Supports Enhanced REP MOVSB/STOSB
PCLMULDQ  	*	Supports PCLMULDQ instruction
POPCNT    	*	Supports POPCNT instruction
LZCNT     	*	Supports LZCNT instruction
SEP       	*	Supports fast system call instructions
LAHF-SAHF 	*	Supports LAHF/SAHF instructions in 64-bit mode
HLE       	-	Supports Hardware Lock Elision instructions
RTM       	-	Supports Restricted Transactional Memory instructions

DE        	*	Supports I/O breakpoints including CR4.DE
DTES64    	-	Can write history of 64-bit branch addresses
DS        	-	Implements memory-resident debug buffer
DS-CPL    	-	Supports Debug Store feature with CPL
PCID      	*	Supports PCIDs and settable CR4.PCIDE
INVPCID   	*	Supports INVPCID instruction
PDCM      	*	Supports Performance Capabilities MSR
RDTSCP    	*	Supports RDTSCP instruction
TSC       	*	Supports RDTSC instruction
TSC-DEADLINE	-	Local APIC supports one-shot deadline timer
TSC-INVARIANT	-	TSC runs at constant rate
xTPR      	-	Supports disabling task priority messages

EIST      	-	Supports Enhanced Intel Speedstep
ACPI      	-	Implements MSR for power management
TM        	-	Implements thermal monitor circuitry
TM2       	-	Implements Thermal Monitor 2 control
APIC      	*	Implements software-accessible local APIC
x2APIC    	-	Supports x2APIC

CNXT-ID   	-	L1 data cache mode adaptive or BIOS

MCE       	*	Supports Machine Check, INT18 and CR4.MCE
MCA       	*	Implements Machine Check Architecture
PBE       	-	Supports use of FERR#/PBE# pin

PSN       	-	Implements 96-bit processor serial number

PREFETCHW 	*	Supports PREFETCHW instruction

Maximum implemented CPUID leaves: 0000000D (Basic), 80000008 (Extended).
Maximum implemented address width: 48 bits (virtual), 39 bits (physical).

Processor signature: 000306C3

Logical to Physical Processor Map:
**------  Physical Processor 0 (Hyperthreaded)
--**----  Physical Processor 1 (Hyperthreaded)
----**--  Physical Processor 2 (Hyperthreaded)
------**  Physical Processor 3 (Hyperthreaded)

Logical Processor to Socket Map:
********  Socket 0

Logical Processor to NUMA Node Map:
********  NUMA Node 0

No NUMA nodes.

Logical Processor to Cache Map:
**------  Data Cache          0, Level 1,   32 KB, Assoc   8, LineSize  64
**------  Instruction Cache   0, Level 1,   32 KB, Assoc   8, LineSize  64
**------  Unified Cache       0, Level 2,  256 KB, Assoc   8, LineSize  64
********  Unified Cache       1, Level 3,    6 MB, Assoc  12, LineSize  64
--**----  Data Cache          1, Level 1,   32 KB, Assoc   8, LineSize  64
--**----  Instruction Cache   1, Level 1,   32 KB, Assoc   8, LineSize  64
--**----  Unified Cache       2, Level 2,  256 KB, Assoc   8, LineSize  64
----**--  Data Cache          2, Level 1,   32 KB, Assoc   8, LineSize  64
----**--  Instruction Cache   2, Level 1,   32 KB, Assoc   8, LineSize  64
----**--  Unified Cache       3, Level 2,  256 KB, Assoc   8, LineSize  64
------**  Data Cache          3, Level 1,   32 KB, Assoc   8, LineSize  64
------**  Instruction Cache   3, Level 1,   32 KB, Assoc   8, LineSize  64
------**  Unified Cache       4, Level 2,  256 KB, Assoc   8, LineSize  64

Logical Processor to Group Map:
********  Group 0

```

### Loaded Modules:

Path |
-- |
C:\SysinternalsSuite\Coreinfo.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000187721772155940C709000000000187`
* Thumbprint: `2485A7AFA98E178CB8F30C9838346B514AEA4769`
* Issuer: CN=Microsoft Code Signing PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: coreinfo
* Product Name: coreinfo
* Company Name: Sysinternals - www.sysinternals.com
* File Version: 3.5
* Product Version: 3.5
* Language: English (United States)
* Legal Copyright: Copyright (C) 2008-2020 Mark Russinovich
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/d93e8067c68ac71928fb963fcba332e91004cbac8b85763e8c6cf19e2ab29895/detection/





MIT License. Copyright (c) 2020-2021 Strontic.


