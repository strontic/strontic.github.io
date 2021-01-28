---
title: "CLSID EE832CE3-06CA-33EF-8F01-61C7C218BD7E | System.Globalization.HijriCalendar"
excerpt: What is COM-Object CLSID EE832CE3-06CA-33EF-8F01-61C7C218BD7E?
---

# {EE832CE3-06CA-33EF-8F01-61C7C218BD7E}

### `System.Globalization.HijriCalendar`

## Registry


### {62C8FE65-4EBB-45E7-B440-6E39B2CDBF29}


### InprocServer32

##### `C:\Windows\System32\mscoree.dll`
* Assembly: `mscorlib, Version=2.0.0.0, Culture=neutral, PublicKeyToken=b77a5c561934e089`
* Class: `System.Globalization.HijriCalendar`
* ThreadingModel: `Both`

### ProgId

##### `System.Globalization.HijriCalendar`

## Instance

* Type: `HijriCalendar`

### Methods

* get_MinSupportedDateTime: `datetime get_MinSupportedDateTime()`
* get_MaxSupportedDateTime: `datetime get_MaxSupportedDateTime()`
* get_AlgorithmType: `System.Globalization.CalendarAlgorithmType get_AlgorithmType()`
* get_HijriAdjustment: `int get_HijriAdjustment()`
* set_HijriAdjustment: `void set_HijriAdjustment(int value)`
* AddMonths: `datetime AddMonths(datetime time, int months)`
* AddYears: `datetime AddYears(datetime time, int years)`
* GetDayOfMonth: `int GetDayOfMonth(datetime time)`
* GetDayOfWeek: `System.DayOfWeek GetDayOfWeek(datetime time)`
* GetDayOfYear: `int GetDayOfYear(datetime time)`
* GetDaysInMonth: `int GetDaysInMonth(int year, int month, int era), int GetDaysInMonth(int year, int month)`
* GetDaysInYear: `int GetDaysInYear(int year, int era), int GetDaysInYear(int year)`
* GetEra: `int GetEra(datetime time)`
* get_Eras: `int[] get_Eras()`
* GetMonth: `int GetMonth(datetime time)`
* GetMonthsInYear: `int GetMonthsInYear(int year, int era), int GetMonthsInYear(int year)`
* GetYear: `int GetYear(datetime time)`
* IsLeapDay: `bool IsLeapDay(int year, int month, int day, int era), bool IsLeapDay(int year, int month, int day)`
* GetLeapMonth: `int GetLeapMonth(int year, int era), int GetLeapMonth(int year)`
* IsLeapMonth: `bool IsLeapMonth(int year, int month, int era), bool IsLeapMonth(int year, int month)`
* IsLeapYear: `bool IsLeapYear(int year, int era), bool IsLeapYear(int year)`
* ToDateTime: `datetime ToDateTime(int year, int month, int day, int hour, int minute, int second, int millisecond, int era), datetime ToDateTime(int year, int month, int day, int hour, int minute, int second, int millisecond)`
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
* GetWeekOfYear: `int GetWeekOfYear(datetime time, System.Globalization.CalendarWeekRule rule, System.DayOfWeek firstDayOfWeek)`

### Properties

* MinSupportedDateTime: `datetime MinSupportedDateTime {get;}`
* MaxSupportedDateTime: `datetime MaxSupportedDateTime {get;}`
* AlgorithmType: `System.Globalization.CalendarAlgorithmType AlgorithmType {get;}`
* HijriAdjustment: `int HijriAdjustment {get;set;}`
* Eras: `int[] Eras {get;}`
* TwoDigitYearMax: `int TwoDigitYearMax {get;set;}`
* IsReadOnly: `bool IsReadOnly {get;}`

MIT License. Copyright (c) 2021 Strontic.


