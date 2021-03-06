﻿---
title: "CLSID EC3DAC94-DF80-3017-B381-B13DCED6C4D8 | System.Globalization.ThaiBuddhistCalendar"
excerpt: What is COM-Object CLSID EC3DAC94-DF80-3017-B381-B13DCED6C4D8?
---

# {EC3DAC94-DF80-3017-B381-B13DCED6C4D8}

### `System.Globalization.ThaiBuddhistCalendar`

## Registry


### {62C8FE65-4EBB-45E7-B440-6E39B2CDBF29}


### InprocServer32

##### `C:\Windows\System32\mscoree.dll`
* Assembly: `mscorlib, Version=2.0.0.0, Culture=neutral, PublicKeyToken=b77a5c561934e089`
* Class: `System.Globalization.ThaiBuddhistCalendar`
* ThreadingModel: `Both`

### ProgId

##### `System.Globalization.ThaiBuddhistCalendar`

## Instance

* Type: `ThaiBuddhistCalendar`

### Methods

* get_MinSupportedDateTime: `datetime get_MinSupportedDateTime()`
* get_MaxSupportedDateTime: `datetime get_MaxSupportedDateTime()`
* get_AlgorithmType: `System.Globalization.CalendarAlgorithmType get_AlgorithmType()`
* AddMonths: `datetime AddMonths(datetime time, int months)`
* AddYears: `datetime AddYears(datetime time, int years)`
* GetDaysInMonth: `int GetDaysInMonth(int year, int month, int era), int GetDaysInMonth(int year, int month)`
* GetDaysInYear: `int GetDaysInYear(int year, int era), int GetDaysInYear(int year)`
* GetDayOfMonth: `int GetDayOfMonth(datetime time)`
* GetDayOfWeek: `System.DayOfWeek GetDayOfWeek(datetime time)`
* GetDayOfYear: `int GetDayOfYear(datetime time)`
* GetMonthsInYear: `int GetMonthsInYear(int year, int era), int GetMonthsInYear(int year)`
* GetWeekOfYear: `int GetWeekOfYear(datetime time, System.Globalization.CalendarWeekRule rule, System.DayOfWeek firstDayOfWeek)`
* GetEra: `int GetEra(datetime time)`
* GetMonth: `int GetMonth(datetime time)`
* GetYear: `int GetYear(datetime time)`
* IsLeapDay: `bool IsLeapDay(int year, int month, int day, int era), bool IsLeapDay(int year, int month, int day)`
* IsLeapYear: `bool IsLeapYear(int year, int era), bool IsLeapYear(int year)`
* GetLeapMonth: `int GetLeapMonth(int year, int era), int GetLeapMonth(int year)`
* IsLeapMonth: `bool IsLeapMonth(int year, int month, int era), bool IsLeapMonth(int year, int month)`
* ToDateTime: `datetime ToDateTime(int year, int month, int day, int hour, int minute, int second, int millisecond, int era), datetime ToDateTime(int year, int month, int day, int hour, int minute, int second, int millisecond)`
* get_Eras: `int[] get_Eras()`
* get_TwoDigitYearMax: `int get_TwoDigitYearMax()`
* set_TwoDigitYearMax: `void set_TwoDigitYearMax(int value)`
* ToFourDigitYear: `int ToFourDigitYear(int year)`
* get_IsReadOnly: `bool get_IsReadOnly()`
* Clone: `System.Object Clone(), System.Object ICloneable.Clone()`
* AddMilliseconds: `datetime AddMilliseconds(datetime time, double milliseconds)`
* AddDays: `datetime AddDays(datetime time, int days)`
* AddHours: `datetime AddHours(datetime time, int hours)`
* AddMinutes: `datetime AddMinutes(datetime time, int minutes)`
* AddSeconds: `datetime AddSeconds(datetime time, int seconds)`
* AddWeeks: `datetime AddWeeks(datetime time, int weeks)`
* GetHour: `int GetHour(datetime time)`
* GetMilliseconds: `double GetMilliseconds(datetime time)`
* GetMinute: `int GetMinute(datetime time)`
* GetSecond: `int GetSecond(datetime time)`

### Properties

* MinSupportedDateTime: `datetime MinSupportedDateTime {get;}`
* MaxSupportedDateTime: `datetime MaxSupportedDateTime {get;}`
* AlgorithmType: `System.Globalization.CalendarAlgorithmType AlgorithmType {get;}`
* Eras: `int[] Eras {get;}`
* TwoDigitYearMax: `int TwoDigitYearMax {get;set;}`
* IsReadOnly: `bool IsReadOnly {get;}`

MIT License. Copyright (c) 2021 Strontic.


