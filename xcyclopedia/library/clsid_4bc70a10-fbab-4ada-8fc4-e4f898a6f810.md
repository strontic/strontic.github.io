---
title: "CLSID 4bc70a10-fbab-4ada-8fc4-e4f898a6f810 | CImagePropertiesProxy"
excerpt: What is COM-Object CLSID 4bc70a10-fbab-4ada-8fc4-e4f898a6f810?
---

# {4bc70a10-fbab-4ada-8fc4-e4f898a6f810}

* `CImagePropertiesProxy`

## Registry


### InProcServer32

* `C:\Windows\system32\windows.storage.dll`
* ThreadingModel: `Both`

## Instance

* Type: `ImageProperties`

### Methods

* get_Rating: `uint32 get_Rating()`
* put_Rating: `void put_Rating(uint32 value)`
* get_Keywords: `System.Collections.Generic.IList[string] get_Keywords()`
* get_DateTaken: `System.DateTimeOffset get_DateTaken()`
* put_DateTaken: `void put_DateTaken(System.DateTimeOffset value)`
* get_Width: `uint32 get_Width()`
* get_Height: `uint32 get_Height()`
* get_Title: `string get_Title()`
* put_Title: `void put_Title(string value)`
* get_Latitude: `System.Nullable[double] get_Latitude()`
* get_Longitude: `System.Nullable[double] get_Longitude()`
* get_CameraManufacturer: `string get_CameraManufacturer()`
* put_CameraManufacturer: `void put_CameraManufacturer(string value)`
* get_CameraModel: `string get_CameraModel()`
* put_CameraModel: `void put_CameraModel(string value)`
* get_Orientation: `Windows.Storage.FileProperties.PhotoOrientation get_Orientation()`
* get_PeopleNames: `System.Collections.Generic.IReadOnlyList[string] get_PeopleNames()`
* RetrievePropertiesAsync: `Windows.Foundation.IAsyncOperation[System.Collections.Generic.IDictionary[string,System.Object]] RetrievePropertiesAsync(System.Collections.Generic.IEnumerable[string] propertiesToRetrieve), Windows.Foundation.IAsyncOperation[System.Collections.Generic.IDictionary[string,System.Object]] IStorageItemExtraProperties.RetrievePropertiesAsync(System.Collections.Generic.IEnumerable[string] propertiesToRetrieve)`
* SavePropertiesAsync: `Windows.Foundation.IAsyncAction SavePropertiesAsync(System.Collections.Generic.IEnumerable[System.Collections.Generic.KeyValuePair[string,System.Object]] propertiesToSave), Windows.Foundation.IAsyncAction SavePropertiesAsync(), Windows.Foundation.IAsyncAction IStorageItemExtraProperties.SavePropertiesAsync(System.Collections.Generic.IEnumerable[System.Collections.Generic.KeyValuePair[string,System.Object]] propertiesToSave), Windows.Foundation.IAsyncAction IStorageItemExtraProperties.SavePropertiesAsync()`

### Properties

* Title: `string Title {get;set;}`
* Rating: `uint32 Rating {get;set;}`
* DateTaken: `System.DateTimeOffset DateTaken {get;set;}`
* CameraModel: `string CameraModel {get;set;}`
* CameraManufacturer: `string CameraManufacturer {get;set;}`
* Height: `uint32 Height {get;}`
* Keywords: `System.Collections.Generic.IList[string] Keywords {get;}`
* Latitude: `System.Nullable[double] Latitude {get;}`
* Longitude: `System.Nullable[double] Longitude {get;}`
* Orientation: `Windows.Storage.FileProperties.PhotoOrientation Orientation {get;}`
* PeopleNames: `System.Collections.Generic.IReadOnlyList[string] PeopleNames {get;}`
* Width: `uint32 Width {get;}`

MIT License. Copyright (c) 2021 Strontic.


