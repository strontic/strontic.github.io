---
title: "CLSID A0F5F5DC-337B-38D7-B1A3-FB1B95666BBF | System.Text.UnicodeEncoding"
excerpt: What is COM-Object CLSID A0F5F5DC-337B-38D7-B1A3-FB1B95666BBF?
---

# {A0F5F5DC-337B-38D7-B1A3-FB1B95666BBF}

* (default): `System.Text.UnicodeEncoding`

## Registry


### {62C8FE65-4EBB-45E7-B440-6E39B2CDBF29}


### InprocServer32

* (default): `C:\Windows\System32\mscoree.dll`
* Assembly: `mscorlib, Version=2.0.0.0, Culture=neutral, PublicKeyToken=b77a5c561934e089`
* Class: `System.Text.UnicodeEncoding`
* ThreadingModel: `Both`

### ProgId

* (default): `System.Text.UnicodeEncoding`

## Instance

* Type: `UnicodeEncoding`

### Methods

* GetByteCount: `int GetByteCount(char[] chars, int index, int count), int GetByteCount(string s), int GetByteCount(System.Char*, mscorlib, Version=4.0.0.0, Culture=neutral, PublicKeyToken=b77a5c561934e089 chars, int count), int GetByteCount(char[] chars)`
* GetBytes: `int GetBytes(string s, int charIndex, int charCount, byte[] bytes, int byteIndex), int GetBytes(char[] chars, int charIndex, int charCount, byte[] bytes, int byteIndex), int GetBytes(System.Char*, mscorlib, Version=4.0.0.0, Culture=neutral, PublicKeyToken=b77a5c561934e089 chars, int charCount, System.Byte*, mscorlib, Version=4.0.0.0, Culture=neutral, PublicKeyToken=b77a5c561934e089 bytes, int byteCount), byte[] GetBytes(char[] chars), byte[] GetBytes(char[] chars, int index, int count), byte[] GetBytes(string s)`
* GetCharCount: `int GetCharCount(byte[] bytes, int index, int count), int GetCharCount(System.Byte*, mscorlib, Version=4.0.0.0, Culture=neutral, PublicKeyToken=b77a5c561934e089 bytes, int count), int GetCharCount(byte[] bytes)`
* GetChars: `int GetChars(byte[] bytes, int byteIndex, int byteCount, char[] chars, int charIndex), int GetChars(System.Byte*, mscorlib, Version=4.0.0.0, Culture=neutral, PublicKeyToken=b77a5c561934e089 bytes, int byteCount, System.Char*, mscorlib, Version=4.0.0.0, Culture=neutral, PublicKeyToken=b77a5c561934e089 chars, int charCount), char[] GetChars(byte[] bytes), char[] GetChars(byte[] bytes, int index, int count)`
* GetString: `string GetString(byte[] bytes, int index, int count), string GetString(System.Byte*, mscorlib, Version=4.0.0.0, Culture=neutral, PublicKeyToken=b77a5c561934e089 bytes, int byteCount), string GetString(byte[] bytes)`
* GetEncoder: `System.Text.Encoder GetEncoder()`
* GetDecoder: `System.Text.Decoder GetDecoder()`
* GetPreamble: `byte[] GetPreamble()`
* GetMaxByteCount: `int GetMaxByteCount(int charCount)`
* GetMaxCharCount: `int GetMaxCharCount(int byteCount)`
* get_BodyName: `string get_BodyName()`
* get_EncodingName: `string get_EncodingName()`
* get_HeaderName: `string get_HeaderName()`
* get_WebName: `string get_WebName()`
* get_WindowsCodePage: `int get_WindowsCodePage()`
* get_IsBrowserDisplay: `bool get_IsBrowserDisplay()`
* get_IsBrowserSave: `bool get_IsBrowserSave()`
* get_IsMailNewsDisplay: `bool get_IsMailNewsDisplay()`
* get_IsMailNewsSave: `bool get_IsMailNewsSave()`
* get_IsSingleByte: `bool get_IsSingleByte()`
* get_EncoderFallback: `System.Text.EncoderFallback get_EncoderFallback()`
* set_EncoderFallback: `void set_EncoderFallback(System.Text.EncoderFallback value)`
* get_DecoderFallback: `System.Text.DecoderFallback get_DecoderFallback()`
* set_DecoderFallback: `void set_DecoderFallback(System.Text.DecoderFallback value)`
* Clone: `System.Object Clone(), System.Object ICloneable.Clone()`
* get_IsReadOnly: `bool get_IsReadOnly()`
* get_CodePage: `int get_CodePage()`
* IsAlwaysNormalized: `bool IsAlwaysNormalized(), bool IsAlwaysNormalized(System.Text.NormalizationForm form)`

### Properties

* BodyName: `string BodyName {get;}`
* EncodingName: `string EncodingName {get;}`
* HeaderName: `string HeaderName {get;}`
* WebName: `string WebName {get;}`
* WindowsCodePage: `int WindowsCodePage {get;}`
* IsBrowserDisplay: `bool IsBrowserDisplay {get;}`
* IsBrowserSave: `bool IsBrowserSave {get;}`
* IsMailNewsDisplay: `bool IsMailNewsDisplay {get;}`
* IsMailNewsSave: `bool IsMailNewsSave {get;}`
* IsSingleByte: `bool IsSingleByte {get;}`
* EncoderFallback: `System.Text.EncoderFallback EncoderFallback {get;set;}`
* DecoderFallback: `System.Text.DecoderFallback DecoderFallback {get;set;}`
* IsReadOnly: `bool IsReadOnly {get;}`
* CodePage: `int CodePage {get;}`

MIT License. Copyright (c) 2021 Strontic.


