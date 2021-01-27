---
title: "CLSID D74D613D-F27F-311B-A9A3-27EBC63A1A5D | System.Threading.Mutex"
excerpt: What is COM-Object CLSID D74D613D-F27F-311B-A9A3-27EBC63A1A5D?
---

# {D74D613D-F27F-311B-A9A3-27EBC63A1A5D}

* (default): `System.Threading.Mutex`

## Registry


### {62C8FE65-4EBB-45E7-B440-6E39B2CDBF29}


### InprocServer32

* (default): `C:\Windows\System32\mscoree.dll`
* Assembly: `mscorlib, Version=2.0.0.0, Culture=neutral, PublicKeyToken=b77a5c561934e089`
* Class: `System.Threading.Mutex`
* ThreadingModel: `Both`

### ProgId

* (default): `System.Threading.Mutex`

## Instance

* Type: `Mutex`

### Methods

* ReleaseMutex: `void ReleaseMutex()`
* GetAccessControl: `System.Security.AccessControl.MutexSecurity GetAccessControl()`
* SetAccessControl: `void SetAccessControl(System.Security.AccessControl.MutexSecurity mutexSecurity)`
* get_Handle: `System.IntPtr get_Handle()`
* set_Handle: `void set_Handle(System.IntPtr value)`
* get_SafeWaitHandle: `Microsoft.Win32.SafeHandles.SafeWaitHandle get_SafeWaitHandle()`
* set_SafeWaitHandle: `void set_SafeWaitHandle(Microsoft.Win32.SafeHandles.SafeWaitHandle value)`
* WaitOne: `bool WaitOne(int millisecondsTimeout, bool exitContext), bool WaitOne(timespan timeout, bool exitContext), bool WaitOne(), bool WaitOne(int millisecondsTimeout), bool WaitOne(timespan timeout)`
* Close: `void Close()`
* Dispose: `void Dispose(), void IDisposable.Dispose()`

### Properties

* Handle: `System.IntPtr Handle {get;set;}`
* SafeWaitHandle: `Microsoft.Win32.SafeHandles.SafeWaitHandle SafeWaitHandle {get;set;}`

MIT License. Copyright (c) 2021 Strontic.


