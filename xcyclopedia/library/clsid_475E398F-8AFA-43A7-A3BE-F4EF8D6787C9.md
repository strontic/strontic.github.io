---
title: "CLSID 475E398F-8AFA-43A7-A3BE-F4EF8D6787C9 | System.Runtime.InteropServices.RegistrationServices"
excerpt: What is COM-Object CLSID 475E398F-8AFA-43A7-A3BE-F4EF8D6787C9?
---

# {475E398F-8AFA-43A7-A3BE-F4EF8D6787C9}

* (default): `System.Runtime.InteropServices.RegistrationServices`

## Registry


### {62C8FE65-4EBB-45E7-B440-6E39B2CDBF29}


### InprocServer32

* (default): `C:\Windows\System32\mscoree.dll`
* Assembly: `mscorlib, Version=2.0.0.0, Culture=neutral, PublicKeyToken=b77a5c561934e089`
* Class: `System.Runtime.InteropServices.RegistrationServices`
* ThreadingModel: `Both`

### ProgId

* (default): `System.Runtime.InteropServices.RegistrationServices`

## Instance

* Type: `RegistrationServices`

### Methods

* RegisterAssembly: `bool RegisterAssembly(System.Reflection.Assembly assembly, System.Runtime.InteropServices.AssemblyRegistrationFlags flags), bool IRegistrationServices.RegisterAssembly(System.Reflection.Assembly assembly, System.Runtime.InteropServices.AssemblyRegistrationFlags flags)`
* UnregisterAssembly: `bool UnregisterAssembly(System.Reflection.Assembly assembly), bool IRegistrationServices.UnregisterAssembly(System.Reflection.Assembly assembly)`
* GetRegistrableTypesInAssembly: `type[] GetRegistrableTypesInAssembly(System.Reflection.Assembly assembly), type[] IRegistrationServices.GetRegistrableTypesInAssembly(System.Reflection.Assembly assembly)`
* GetProgIdForType: `string GetProgIdForType(type type), string IRegistrationServices.GetProgIdForType(type type)`
* RegisterTypeForComClients: `void RegisterTypeForComClients(type type, [ref] guid g), int RegisterTypeForComClients(type type, System.Runtime.InteropServices.RegistrationClassContext classContext, System.Runtime.InteropServices.RegistrationConnectionType flags), void IRegistrationServices.RegisterTypeForComClients(type type, [ref] guid g)`
* GetManagedCategoryGuid: `guid GetManagedCategoryGuid(), guid IRegistrationServices.GetManagedCategoryGuid()`
* TypeRequiresRegistration: `bool TypeRequiresRegistration(type type), bool IRegistrationServices.TypeRequiresRegistration(type type)`
* TypeRepresentsComType: `bool TypeRepresentsComType(type type), bool IRegistrationServices.TypeRepresentsComType(type type)`
* UnregisterTypeForComClients: `void UnregisterTypeForComClients(int cookie)`

MIT License. Copyright (c) 2021 Strontic.


