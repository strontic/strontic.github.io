---
title: "CLSID 673DFE75-9F93-304F-ABA8-D2A86BA87D7C | System.Security.Cryptography.DSACryptoServiceProvider"
excerpt: What is COM-Object CLSID 673DFE75-9F93-304F-ABA8-D2A86BA87D7C?
---

# {673DFE75-9F93-304F-ABA8-D2A86BA87D7C}

* (default): `System.Security.Cryptography.DSACryptoServiceProvider`

## Registry


### {62C8FE65-4EBB-45E7-B440-6E39B2CDBF29}


### InprocServer32

* (default): `C:\Windows\System32\mscoree.dll`
* Assembly: `mscorlib, Version=2.0.0.0, Culture=neutral, PublicKeyToken=b77a5c561934e089`
* Class: `System.Security.Cryptography.DSACryptoServiceProvider`
* ThreadingModel: `Both`

### ProgId

* (default): `System.Security.Cryptography.DSACryptoServiceProvider`

## Instance

* Type: `DSACryptoServiceProvider`

### Methods

* get_PublicOnly: `bool get_PublicOnly()`
* get_CspKeyContainerInfo: `System.Security.Cryptography.CspKeyContainerInfo get_CspKeyContainerInfo(), System.Security.Cryptography.CspKeyContainerInfo ICspAsymmetricAlgorithm.get_CspKeyContainerInfo()`
* get_KeySize: `int get_KeySize()`
* get_KeyExchangeAlgorithm: `string get_KeyExchangeAlgorithm()`
* get_SignatureAlgorithm: `string get_SignatureAlgorithm()`
* get_PersistKeyInCsp: `bool get_PersistKeyInCsp()`
* set_PersistKeyInCsp: `void set_PersistKeyInCsp(bool value)`
* ExportParameters: `System.Security.Cryptography.DSAParameters ExportParameters(bool includePrivateParameters)`
* ExportCspBlob: `byte[] ExportCspBlob(bool includePrivateParameters), byte[] ICspAsymmetricAlgorithm.ExportCspBlob(bool includePrivateParameters)`
* ImportParameters: `void ImportParameters(System.Security.Cryptography.DSAParameters parameters)`
* ImportCspBlob: `void ImportCspBlob(byte[] keyBlob), void ICspAsymmetricAlgorithm.ImportCspBlob(byte[] rawData)`
* SignData: `byte[] SignData(System.IO.Stream inputStream), byte[] SignData(byte[] buffer), byte[] SignData(byte[] buffer, int offset, int count), byte[] SignData(byte[] data, System.Security.Cryptography.HashAlgorithmName hashAlgorithm), byte[] SignData(byte[] data, int offset, int count, System.Security.Cryptography.HashAlgorithmName hashAlgorithm), byte[] SignData(System.IO.Stream data, System.Security.Cryptography.HashAlgorithmName hashAlgorithm)`
* VerifyData: `bool VerifyData(byte[] rgbData, byte[] rgbSignature), bool VerifyData(byte[] data, byte[] signature, System.Security.Cryptography.HashAlgorithmName hashAlgorithm), bool VerifyData(byte[] data, int offset, int count, byte[] signature, System.Security.Cryptography.HashAlgorithmName hashAlgorithm), bool VerifyData(System.IO.Stream data, byte[] signature, System.Security.Cryptography.HashAlgorithmName hashAlgorithm)`
* CreateSignature: `byte[] CreateSignature(byte[] rgbHash)`
* VerifySignature: `bool VerifySignature(byte[] rgbHash, byte[] rgbSignature)`
* SignHash: `byte[] SignHash(byte[] rgbHash, string str)`
* VerifyHash: `bool VerifyHash(byte[] rgbHash, string str, byte[] rgbSignature)`
* FromXmlString: `void FromXmlString(string xmlString)`
* ToXmlString: `string ToXmlString(bool includePrivateParameters)`
* Dispose: `void Dispose(), void IDisposable.Dispose()`
* Clear: `void Clear()`
* set_KeySize: `void set_KeySize(int value)`
* get_LegalKeySizes: `System.Security.Cryptography.KeySizes[] get_LegalKeySizes()`

### Properties

* PublicOnly: `bool PublicOnly {get;}`
* CspKeyContainerInfo: `System.Security.Cryptography.CspKeyContainerInfo CspKeyContainerInfo {get;}`
* KeySize: `int KeySize {get;}`
* KeyExchangeAlgorithm: `string KeyExchangeAlgorithm {get;}`
* SignatureAlgorithm: `string SignatureAlgorithm {get;}`
* PersistKeyInCsp: `bool PersistKeyInCsp {get;set;}`
* LegalKeySizes: `System.Security.Cryptography.KeySizes[] LegalKeySizes {get;}`

MIT License. Copyright (c) 2021 Strontic.


