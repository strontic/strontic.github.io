---
title: "CLSID CA0AC604-8EF2-448A-AE97-62A2C2CC3C46 | SpDMOAudioIn Class"
excerpt: What is COM-Object CLSID CA0AC604-8EF2-448A-AE97-62A2C2CC3C46?
---

# {CA0AC604-8EF2-448A-AE97-62A2C2CC3C46}

* (default): `SpDMOAudioIn Class`

## Registry


### InprocServer32

* (default): `C:\Windows\System32\Speech\Common\sapi.dll`
* ThreadingModel: `Both`

## Instance

* Type: `__ComObject`

### Methods

* Read: `int Read (Variant, int)`
* Write: `int Write (Variant)`
* Seek: `Variant Seek (Variant, SpeechStreamSeekPositionType)`
* SetState: `void SetState (SpeechAudioState)`

### Properties

* Format: `ISpeechAudioFormat Format () {get} {set by ref}`
* Status: `ISpeechAudioStatus Status () {get} `
* BufferInfo: `ISpeechAudioBufferInfo BufferInfo () {get} `
* DefaultFormat: `ISpeechAudioFormat DefaultFormat () {get} `
* Volume: `int Volume () {get} {set} `
* BufferNotifySize: `int BufferNotifySize () {get} {set} `
* EventHandle: `int EventHandle () {get} `
* DeviceId: `int DeviceId () {get} {set} `
* LineId: `int LineId () {get} {set} `
* MMHandle: `int MMHandle () {get} `

MIT License. Copyright (c) 2021 Strontic.


