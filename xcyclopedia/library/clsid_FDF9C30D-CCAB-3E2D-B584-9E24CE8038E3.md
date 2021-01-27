---
title: "CLSID FDF9C30D-CCAB-3E2D-B584-9E24CE8038E3 | System.Security.Cryptography.SHA1Managed"
excerpt: What is COM-Object CLSID FDF9C30D-CCAB-3E2D-B584-9E24CE8038E3?
---

# {FDF9C30D-CCAB-3E2D-B584-9E24CE8038E3}

* (default): `System.Security.Cryptography.SHA1Managed`

## Registry


### {62C8FE65-4EBB-45E7-B440-6E39B2CDBF29}


### InprocServer32

* (default): `C:\Windows\System32\mscoree.dll`
* Assembly: `mscorlib, Version=2.0.0.0, Culture=neutral, PublicKeyToken=b77a5c561934e089`
* Class: `System.Security.Cryptography.SHA1Managed`
* ThreadingModel: `Both`

### ProgId

* (default): `System.Security.Cryptography.SHA1Managed`

## Instance

* Type: `SHA1Managed`

### Methods

* Initialize: `void Initialize()`
* get_HashSize: `int get_HashSize()`
* get_Hash: `byte[] get_Hash()`
* ComputeHash: `byte[] ComputeHash(System.IO.Stream inputStream), byte[] ComputeHash(byte[] buffer), byte[] ComputeHash(byte[] buffer, int offset, int count)`
* get_InputBlockSize: `int get_InputBlockSize(), int ICryptoTransform.get_InputBlockSize()`
* get_OutputBlockSize: `int get_OutputBlockSize(), int ICryptoTransform.get_OutputBlockSize()`
* get_CanTransformMultipleBlocks: `bool get_CanTransformMultipleBlocks(), bool ICryptoTransform.get_CanTransformMultipleBlocks()`
* get_CanReuseTransform: `bool get_CanReuseTransform(), bool ICryptoTransform.get_CanReuseTransform()`
* TransformBlock: `int TransformBlock(byte[] inputBuffer, int inputOffset, int inputCount, byte[] outputBuffer, int outputOffset), int ICryptoTransform.TransformBlock(byte[] inputBuffer, int inputOffset, int inputCount, byte[] outputBuffer, int outputOffset)`
* TransformFinalBlock: `byte[] TransformFinalBlock(byte[] inputBuffer, int inputOffset, int inputCount), byte[] ICryptoTransform.TransformFinalBlock(byte[] inputBuffer, int inputOffset, int inputCount)`
* Dispose: `void Dispose(), void IDisposable.Dispose()`
* Clear: `void Clear()`

### Properties

* HashSize: `int HashSize {get;}`
* Hash: `byte[] Hash {get;}`
* InputBlockSize: `int InputBlockSize {get;}`
* OutputBlockSize: `int OutputBlockSize {get;}`
* CanTransformMultipleBlocks: `bool CanTransformMultipleBlocks {get;}`
* CanReuseTransform: `bool CanReuseTransform {get;}`

MIT License. Copyright (c) 2021 Strontic.


