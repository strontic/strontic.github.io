---
title: "CLSID 19eb3aee-148e-42fe-a569-a7dc9b25d658 | CMusicPropertiesProxy"
excerpt: What is COM-Object CLSID 19eb3aee-148e-42fe-a569-a7dc9b25d658?
---

# {19eb3aee-148e-42fe-a569-a7dc9b25d658}

### `CMusicPropertiesProxy`

## Registry


### InProcServer32

##### `C:\Windows\system32\windows.storage.dll`
* ThreadingModel: `Both`

## Instance

* Type: `MusicProperties`

### Methods

* get_Album: `string get_Album()`
* put_Album: `void put_Album(string value)`
* get_Artist: `string get_Artist()`
* put_Artist: `void put_Artist(string value)`
* get_Genre: `System.Collections.Generic.IList[string] get_Genre()`
* get_TrackNumber: `uint32 get_TrackNumber()`
* put_TrackNumber: `void put_TrackNumber(uint32 value)`
* get_Title: `string get_Title()`
* put_Title: `void put_Title(string value)`
* get_Rating: `uint32 get_Rating()`
* put_Rating: `void put_Rating(uint32 value)`
* get_Duration: `timespan get_Duration()`
* get_Bitrate: `uint32 get_Bitrate()`
* get_AlbumArtist: `string get_AlbumArtist()`
* put_AlbumArtist: `void put_AlbumArtist(string value)`
* get_Composers: `System.Collections.Generic.IList[string] get_Composers()`
* get_Conductors: `System.Collections.Generic.IList[string] get_Conductors()`
* get_Subtitle: `string get_Subtitle()`
* put_Subtitle: `void put_Subtitle(string value)`
* get_Producers: `System.Collections.Generic.IList[string] get_Producers()`
* get_Publisher: `string get_Publisher()`
* put_Publisher: `void put_Publisher(string value)`
* get_Writers: `System.Collections.Generic.IList[string] get_Writers()`
* get_Year: `uint32 get_Year()`
* put_Year: `void put_Year(uint32 value)`
* RetrievePropertiesAsync: `Windows.Foundation.IAsyncOperation[System.Collections.Generic.IDictionary[string,System.Object]] RetrievePropertiesAsync(System.Collections.Generic.IEnumerable[string] propertiesToRetrieve), Windows.Foundation.IAsyncOperation[System.Collections.Generic.IDictionary[string,System.Object]] IStorageItemExtraProperties.RetrievePropertiesAsync(System.Collections.Generic.IEnumerable[string] propertiesToRetrieve)`
* SavePropertiesAsync: `Windows.Foundation.IAsyncAction SavePropertiesAsync(System.Collections.Generic.IEnumerable[System.Collections.Generic.KeyValuePair[string,System.Object]] propertiesToSave), Windows.Foundation.IAsyncAction SavePropertiesAsync(), Windows.Foundation.IAsyncAction IStorageItemExtraProperties.SavePropertiesAsync(System.Collections.Generic.IEnumerable[System.Collections.Generic.KeyValuePair[string,System.Object]] propertiesToSave), Windows.Foundation.IAsyncAction IStorageItemExtraProperties.SavePropertiesAsync()`

### Properties

* Year: `uint32 Year {get;set;}`
* TrackNumber: `uint32 TrackNumber {get;set;}`
* Title: `string Title {get;set;}`
* Subtitle: `string Subtitle {get;set;}`
* Rating: `uint32 Rating {get;set;}`
* Publisher: `string Publisher {get;set;}`
* Artist: `string Artist {get;set;}`
* AlbumArtist: `string AlbumArtist {get;set;}`
* Album: `string Album {get;set;}`
* Bitrate: `uint32 Bitrate {get;}`
* Composers: `System.Collections.Generic.IList[string] Composers {get;}`
* Conductors: `System.Collections.Generic.IList[string] Conductors {get;}`
* Duration: `timespan Duration {get;}`
* Genre: `System.Collections.Generic.IList[string] Genre {get;}`
* Producers: `System.Collections.Generic.IList[string] Producers {get;}`
* Writers: `System.Collections.Generic.IList[string] Writers {get;}`

MIT License. Copyright (c) 2021 Strontic.


