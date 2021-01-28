---
title: "CLSID 1CFC4CDA-1271-11D1-9BD4-00C04FB683FA | Encode Alternate Name Class"
excerpt: What is COM-Object CLSID 1CFC4CDA-1271-11D1-9BD4-00C04FB683FA?
---

# {1CFC4CDA-1271-11D1-9BD4-00C04FB683FA}

* `Encode Alternate Name Class`

## Registry


### InprocServer32

* `C:\Windows\system32\certenc.dll`
* ThreadingModel: `both`

### ProgID

* `CertificateAuthority.EncodeAltName.1`

### VersionIndependentProgID

* `CertificateAuthority.EncodeAltName`

## Instance

* Type: `__ComObject`

### Methods

* Decode: `void Decode (string)`
* GetNameCount: `int GetNameCount ()`
* GetNameChoice: `int GetNameChoice (int)`
* GetName: `string GetName (int)`
* Reset: `void Reset (int)`
* SetNameEntry: `void SetNameEntry (int, int, string)`
* Encode: `string Encode ()`
* DecodeBlob: `void DecodeBlob (string, EncodingType)`
* EncodeBlob: `string EncodeBlob (EncodingType)`
* GetNameBlob: `string GetNameBlob (int, EncodingType)`
* SetNameEntryBlob: `void SetNameEntryBlob (int, int, string, EncodingType)`

MIT License. Copyright (c) 2021 Strontic.


