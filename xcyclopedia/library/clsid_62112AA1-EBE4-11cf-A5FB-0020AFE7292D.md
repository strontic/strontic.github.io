---
title: "CLSID 62112AA1-EBE4-11cf-A5FB-0020AFE7292D | Shell Automation Folder View"
excerpt: What is COM-Object CLSID 62112AA1-EBE4-11cf-A5FB-0020AFE7292D?
---

# {62112AA1-EBE4-11cf-A5FB-0020AFE7292D}

### `Shell Automation Folder View`

## Registry


### InProcServer32

##### `C:\Windows\system32\shell32.dll`
* ThreadingModel: `Apartment`

## Instance

* Type: `ComObject`

### Methods

* SelectedItems: `FolderItems SelectedItems ()`
* SelectItem: `void SelectItem (Variant, int)`
* PopupItemMenu: `string PopupItemMenu (FolderItem, Variant, Variant)`
* SelectItemRelative: `void SelectItemRelative (int)`
* FilterView: `void FilterView (string)`

### Properties

* Application: `IDispatch Application () {get} `
* Parent: `IDispatch Parent () {get} `
* Folder: `Folder Folder () {get} `
* FocusedItem: `FolderItem FocusedItem () {get} `
* Script: `IDispatch Script () {get} `
* ViewOptions: `int ViewOptions () {get} `
* CurrentViewMode: `uint CurrentViewMode () {get} {set} `
* GroupBy: `string GroupBy () {get} {set} `
* FolderFlags: `uint FolderFlags () {get} {set} `
* SortColumns: `string SortColumns () {get} {set} `
* IconSize: `int IconSize () {get} {set} `

MIT License. Copyright (c) 2021 Strontic.


