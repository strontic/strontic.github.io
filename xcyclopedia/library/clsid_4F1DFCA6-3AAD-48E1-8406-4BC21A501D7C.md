---
title: "CLSID 4F1DFCA6-3AAD-48E1-8406-4BC21A501D7C | Workspace Class"
excerpt: What is COM-Object CLSID 4F1DFCA6-3AAD-48E1-8406-4BC21A501D7C?
---

# {4F1DFCA6-3AAD-48E1-8406-4BC21A501D7C}

* (default): `Workspace Class`
* AppID: `{4FCDA643-B15B-41C6-84F8-5E447F6F6D25}`

## Registry


### LocalServer32

* (default): `C:\Windows\system32\wksprt.exe`

### ProgID

* (default): `WorkspaceRuntime.Workspace.1`

### TypeLib

* (default): `{1B8D8AE1-A595-4687-A7AD-9E3828E09B79}`

### VersionIndependentProgID

* (default): `WorkspaceRuntime.Workspace`

## Instance

* Type: `__ComObject`

### Methods

* DisconnectWorkspace: `void DisconnectWorkspace (string)`
* StartWorkspace: `void StartWorkspace (string, string, string, string, int, int)`
* IsWorkspaceCredentialSpecified: `bool IsWorkspaceCredentialSpecified (string, bool)`
* IsWorkspaceSSOEnabled: `bool IsWorkspaceSSOEnabled ()`
* ClearWorkspaceCredential: `void ClearWorkspaceCredential (string)`
* OnAuthenticated: `void OnAuthenticated (string, string)`
* DisconnectWorkspaceByFriendlyName: `void DisconnectWorkspaceByFriendlyName (string)`
* StartWorkspaceEx: `void StartWorkspaceEx (string, string, string, string, string, string, string, int, int)`
* ResourceDismissed: `void ResourceDismissed (string, string)`
* StartWorkspaceEx2: `void StartWorkspaceEx2 (string, string, string, string, string, string, string, int, int, string, GUID)`

MIT License. Copyright (c) 2021 Strontic.


