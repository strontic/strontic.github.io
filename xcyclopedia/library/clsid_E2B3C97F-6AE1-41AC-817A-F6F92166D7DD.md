---
title: "CLSID E2B3C97F-6AE1-41AC-817A-F6F92166D7DD | HNetCfg.FwPolicy2"
excerpt: What is COM-Object CLSID E2B3C97F-6AE1-41AC-817A-F6F92166D7DD?
---

# {E2B3C97F-6AE1-41AC-817A-F6F92166D7DD}

### `HNetCfg.FwPolicy2`
* AppID: `{E2B3C97F-6AE1-41AC-817A-F6F92166D7DD}`
* LocalizedString: `@C:\Windows\system32\FirewallControlPanel.dll,-12122`

## Registry


### Elevation

* Enabled: `1`
* IconReference: `@C:\Windows\System32\FirewallControlPanel.dll,-1`

### InprocServer32

##### `C:\Windows\System32\FirewallAPI.dll`
* ThreadingModel: `Both`

### ProgID

##### `HNetCfg.FwPolicy2`

## Instance

* Type: `ComObject`

### Methods

* EnableRuleGroup: `void EnableRuleGroup (int, string, bool)`
* IsRuleGroupEnabled: `bool IsRuleGroupEnabled (int, string)`
* RestoreLocalFirewallDefaults: `void RestoreLocalFirewallDefaults ()`

### Properties

* CurrentProfileTypes: `int CurrentProfileTypes () {get} `
* Rules: `INetFwRules Rules () {get} `
* ServiceRestriction: `INetFwServiceRestriction ServiceRestriction () {get} `
* LocalPolicyModifyState: `NET_FW_MODIFY_STATE_ LocalPolicyModifyState () {get} `

MIT License. Copyright (c) 2021 Strontic.


