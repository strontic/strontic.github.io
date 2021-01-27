---
title: "CLSID 5520B6D3-6EC6-3CE7-958B-E69FAF6EFF99 | System.Runtime.Remoting.Contexts.SynchronizationAttribute"
excerpt: What is COM-Object CLSID 5520B6D3-6EC6-3CE7-958B-E69FAF6EFF99?
---

# {5520B6D3-6EC6-3CE7-958B-E69FAF6EFF99}

* (default): `System.Runtime.Remoting.Contexts.SynchronizationAttribute`

## Registry


### {62C8FE65-4EBB-45E7-B440-6E39B2CDBF29}


### InprocServer32

* (default): `C:\Windows\System32\mscoree.dll`
* Assembly: `mscorlib, Version=2.0.0.0, Culture=neutral, PublicKeyToken=b77a5c561934e089`
* Class: `System.Runtime.Remoting.Contexts.SynchronizationAttribute`
* ThreadingModel: `Both`

### ProgId

* (default): `System.Runtime.Remoting.Contexts.SynchronizationAttribute`

## Instance

* Type: `SynchronizationAttribute`

### Methods

* get_Locked: `bool get_Locked()`
* set_Locked: `void set_Locked(bool value)`
* get_IsReEntrant: `bool get_IsReEntrant()`
* IsContextOK: `bool IsContextOK(System.Runtime.Remoting.Contexts.Context ctx, System.Runtime.Remoting.Activation.IConstructionCallMessage msg), bool IContextAttribute.IsContextOK(System.Runtime.Remoting.Contexts.Context ctx, System.Runtime.Remoting.Activation.IConstructionCallMessage msg)`
* GetPropertiesForNewContext: `void GetPropertiesForNewContext(System.Runtime.Remoting.Activation.IConstructionCallMessage ctorMsg), void IContextAttribute.GetPropertiesForNewContext(System.Runtime.Remoting.Activation.IConstructionCallMessage msg)`
* GetServerContextSink: `System.Runtime.Remoting.Messaging.IMessageSink GetServerContextSink(System.Runtime.Remoting.Messaging.IMessageSink nextSink), System.Runtime.Remoting.Messaging.IMessageSink IContributeServerContextSink.GetServerContextSink(System.Runtime.Remoting.Messaging.IMessageSink nextSink)`
* GetClientContextSink: `System.Runtime.Remoting.Messaging.IMessageSink GetClientContextSink(System.Runtime.Remoting.Messaging.IMessageSink nextSink), System.Runtime.Remoting.Messaging.IMessageSink IContributeClientContextSink.GetClientContextSink(System.Runtime.Remoting.Messaging.IMessageSink nextSink)`
* get_Name: `string get_Name(), string IContextProperty.get_Name()`
* IsNewContextOK: `bool IsNewContextOK(System.Runtime.Remoting.Contexts.Context newCtx), bool IContextProperty.IsNewContextOK(System.Runtime.Remoting.Contexts.Context newCtx)`
* Freeze: `void Freeze(System.Runtime.Remoting.Contexts.Context newContext), void IContextProperty.Freeze(System.Runtime.Remoting.Contexts.Context newContext)`
* get_TypeId: `System.Object get_TypeId()`
* Match: `bool Match(System.Object obj)`
* IsDefaultAttribute: `bool IsDefaultAttribute()`
* GetTypeInfoCount: `void _Attribute.GetTypeInfoCount([ref] uint32 pcTInfo)`
* GetTypeInfo: `void _Attribute.GetTypeInfo(uint32 iTInfo, uint32 lcid, System.IntPtr ppTInfo)`
* GetIDsOfNames: `void _Attribute.GetIDsOfNames([ref] guid riid, System.IntPtr rgszNames, uint32 cNames, uint32 lcid, System.IntPtr rgDispId)`
* Invoke: `void _Attribute.Invoke(uint32 dispIdMember, [ref] guid riid, uint32 lcid, int16 wFlags, System.IntPtr pDispParams, System.IntPtr pVarResult, System.IntPtr pExcepInfo, System.IntPtr puArgErr)`

### Properties

* Locked: `bool Locked {get;set;}`
* IsReEntrant: `bool IsReEntrant {get;}`
* Name: `string Name {get;}`
* TypeId: `System.Object TypeId {get;}`

MIT License. Copyright (c) 2021 Strontic.


