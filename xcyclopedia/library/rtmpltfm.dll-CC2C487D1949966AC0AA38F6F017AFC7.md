---
title: rtmpltfm.dll | Microsoft Real Time Media Stack
excerpt: What is rtmpltfm.dll?
---

# rtmpltfm.dll 

* File Path: `C:\Windows\system32\rtmpltfm.dll`
* Description: Microsoft Real Time Media Stack

## Hashes

Type | Hash
-- | --
MD5 | `CC2C487D1949966AC0AA38F6F017AFC7`
SHA1 | `FB36E2B1A0DAD185F126E1E0D64C160C0DE6C4B1`
SHA256 | `4A0A4593E1F67D56FB0D3E76870D59857976FC30D1F6BD9BD2E9DEB08ED1D955`
SHA384 | `E49F5BF2B2B07471C3934F58ABAE5E7648EA33F3A22B5229D079339CD4AC534C5F647451C25652E8F6AF5ADBC81EF4A3`
SHA512 | `F9D4B505C1FA35114BB669E67942D8F73F17B37F1BBE87C4B2AEF097C8C538BF18BA2DB720BF33067D5A0CCF9A01D1D14CF366EE7776A63DC450D24083654F99`
SSDEEP | `49152:1t0zc1YmnYhGJ0OxJzclFgyixeqiqSKixb4JOTbrcPV//UnTLgbnq99CIlCCYBFA:7qAyiBOXrcFnqGLryQM4mp5`
IMP | `E74CE553AD6E540050DE22C665DFEE4B`
PESHA1 | `9E18B97E9A54493550CB4A107319AD9DE91FA998`
PE256 | `82CC776C221FF86D5645C5EED36AAFD1CFDC485BCB1DBEEA974C10E5C776F37F`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`CreatePlatformInterface` | 1 (0x1) | Exported Function | 0x0000000180083410 | 0x00083410
`opus_multistream_packet_pad` | 24 (0x18) | Exported Function | 0x00000001801974e0 | 0x001974e0
`opus_multistream_packet_unpad` | 25 (0x19) | Exported Function | 0x00000001801975b0 | 0x001975b0
`opus_packet_get_bandwidth` | 26 (0x1a) | Exported Function | 0x0000000180191590 | 0x00191590
`opus_packet_get_nb_channels` | 27 (0x1b) | Exported Function | 0x00000001801915e0 | 0x001915e0
`opus_packet_get_nb_frames` | 28 (0x1c) | Exported Function | 0x00000001801915f0 | 0x001915f0
`opus_packet_get_nb_samples` | 29 (0x1d) | Exported Function | 0x0000000180191630 | 0x00191630
`opus_packet_get_samples_per_frame` | 30 (0x1e) | Exported Function | 0x0000000180191680 | 0x00191680
`opus_packet_pad` | 31 (0x1f) | Exported Function | 0x00000001801976f0 | 0x001976f0
`opus_get_version_string` | 23 (0x17) | Exported Function | 0x000000018019d550 | 0x0019d550
`opus_packet_parse` | 32 (0x20) | Exported Function | 0x000000018019b900 | 0x0019b900
`opus_pcm_soft_clip` | 34 (0x22) | Exported Function | 0x000000018019bd00 | 0x0019bd00
`opus_repacketizer_cat` | 35 (0x23) | Exported Function | 0x0000000180197840 | 0x00197840
`opus_repacketizer_create` | 36 (0x24) | Exported Function | 0x0000000180197920 | 0x00197920
`opus_repacketizer_destroy` | 37 (0x25) | Exported Function | 0x0000000180088840 | 0x00088840
`opus_repacketizer_get_nb_frames` | 38 (0x26) | Exported Function | 0x0000000180197940 | 0x00197940
`opus_repacketizer_get_size` | 39 (0x27) | Exported Function | 0x0000000180197950 | 0x00197950
`opus_repacketizer_init` | 40 (0x28) | Exported Function | 0x0000000180197960 | 0x00197960
`opus_repacketizer_out` | 41 (0x29) | Exported Function | 0x0000000180197970 | 0x00197970
`opus_packet_unpad` | 33 (0x21) | Exported Function | 0x00000001801977b0 | 0x001977b0
`opus_repacketizer_out_range` | 42 (0x2a) | Exported Function | 0x00000001801979a0 | 0x001979a0
`opus_encoder_init` | 22 (0x16) | Exported Function | 0x000000018018fa00 | 0x0018fa00
`opus_encoder_destroy` | 20 (0x14) | Exported Function | 0x0000000180088840 | 0x00088840
`CreatePlatformInterfaceEx` | 2 (0x2) | Exported Function | 0x0000000180083440 | 0x00083440
`CreatePlatformInterfaceEx2` | 3 (0x3) | Exported Function | 0x0000000180083470 | 0x00083470
`CreatePlatformInterfaceEx3` | 4 (0x4) | Exported Function | 0x00000001800834a0 | 0x000834a0
`CreatePlatformInterfaceEx4` | 5 (0x5) | Exported Function | 0x00000001800834d0 | 0x000834d0
`CreateVideoTranscoderInterface` | 6 (0x6) | Exported Function | 0x00000001801e2b90 | 0x001e2b90
`CreateVideoTranscoderInterfaceEx` | 7 (0x7) | Exported Function | 0x00000001801e2b90 | 0x001e2b90
`opus_decode` | 8 (0x8) | Exported Function | 0x00000001801901f0 | 0x001901f0
`opus_decode_float` | 9 (0x9) | Exported Function | 0x0000000180190310 | 0x00190310
`opus_encoder_get_size` | 21 (0x15) | Exported Function | 0x000000018018f9b0 | 0x0018f9b0
`opus_decoder_create` | 10 (0xa) | Exported Function | 0x00000001801911f0 | 0x001911f0
`opus_decoder_destroy` | 12 (0xc) | Exported Function | 0x0000000180088840 | 0x00088840
`opus_decoder_get_nb_samples` | 13 (0xd) | Exported Function | 0x0000000180191410 | 0x00191410
`opus_decoder_get_size` | 14 (0xe) | Exported Function | 0x0000000180191430 | 0x00191430
`opus_decoder_init` | 15 (0xf) | Exported Function | 0x0000000180191480 | 0x00191480
`opus_encode` | 16 (0x10) | Exported Function | 0x000000018018cf30 | 0x0018cf30
`opus_encode_float` | 17 (0x11) | Exported Function | 0x000000018018d0a0 | 0x0018d0a0
`opus_encoder_create` | 18 (0x12) | Exported Function | 0x000000018018f260 | 0x0018f260
`opus_encoder_ctl` | 19 (0x13) | Exported Function | 0x000000018018f340 | 0x0018f340
`opus_decoder_ctl` | 11 (0xb) | Exported Function | 0x00000001801912b0 | 0x001912b0
`opus_strerror` | 43 (0x2b) | Exported Function | 0x000000018019d560 | 0x0019d560


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: RTMPLTFM.dll
* Product Name: Microsoft Skype Media Stack
* Company Name: Microsoft Corporation
* File Version: 2018.6.1.57:releases/CL2018.R06:489934d3427ba175f96a716e69f1346e123a6779:(BuildId:25316617:release)
* Product Version: 2018.6.1.57
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/4a0a4593e1f67d56fb0d3e76870d59857976fc30d1f6bd9bd2e9deb08ed1d955/detection/





MIT License. Copyright (c) 2020 Strontic.


