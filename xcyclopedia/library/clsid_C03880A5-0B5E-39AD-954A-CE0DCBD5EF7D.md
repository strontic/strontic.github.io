---
title: "CLSID C03880A5-0B5E-39AD-954A-CE0DCBD5EF7D | System.AppDomainManager"
excerpt: What is COM-Object CLSID C03880A5-0B5E-39AD-954A-CE0DCBD5EF7D?
---

# {C03880A5-0B5E-39AD-954A-CE0DCBD5EF7D}

* (default): `System.AppDomainManager`

## Registry


### {62C8FE65-4EBB-45E7-B440-6E39B2CDBF29}


### InprocServer32

* (default): `C:\Windows\System32\mscoree.dll`
* Assembly: `mscorlib, Version=2.0.0.0, Culture=neutral, PublicKeyToken=b77a5c561934e089`
* Class: `System.AppDomainManager`
* ThreadingModel: `Both`

### ProgId

* (default): `System.AppDomainManager`

## Instance

* Type: `AppDomainManager`

### Methods

* CreateDomain: `System.AppDomain CreateDomain(string friendlyName, System.Security.Policy.Evidence securityInfo, System.AppDomainSetup appDomainInfo)`
* InitializeNewDomain: `void InitializeNewDomain(System.AppDomainSetup appDomainInfo)`
* get_InitializationFlags: `System.AppDomainManagerInitializationOptions get_InitializationFlags()`
* set_InitializationFlags: `void set_InitializationFlags(System.AppDomainManagerInitializationOptions value)`
* get_ApplicationActivator: `System.Runtime.Hosting.ApplicationActivator get_ApplicationActivator()`
* get_HostSecurityManager: `System.Security.HostSecurityManager get_HostSecurityManager()`
* get_HostExecutionContextManager: `System.Threading.HostExecutionContextManager get_HostExecutionContextManager()`
* get_EntryAssembly: `System.Reflection.Assembly get_EntryAssembly()`
* CheckSecuritySettings: `bool CheckSecuritySettings(System.Security.SecurityState state)`

### Properties

* InitializationFlags: `System.AppDomainManagerInitializationOptions InitializationFlags {get;set;}`
* ApplicationActivator: `System.Runtime.Hosting.ApplicationActivator ApplicationActivator {get;}`
* HostSecurityManager: `System.Security.HostSecurityManager HostSecurityManager {get;}`
* HostExecutionContextManager: `System.Threading.HostExecutionContextManager HostExecutionContextManager {get;}`
* EntryAssembly: `System.Reflection.Assembly EntryAssembly {get;}`

MIT License. Copyright (c) 2021 Strontic.


