---
title: date.exe | 
---

# date.exe 

* File Path: `C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\date.exe`

## Hashes

Type | Hash
-- | --
MD5 | `6DCB5C5CA565B5AB695F6E5662F3F5CC`
SHA1 | `983C78EEC261832AA8304871B76EBCEB458A9AEA`
SHA256 | `2D42B786FEE4D6A823A966E685FFA3197E48FD243210CC4C9BD774D79A96323B`
SHA384 | `848BF7A0B5B4BB063CAE77288C1E7CF43D8FDAB2DFDAF10FEFC7A0E1055B3658CAB952172E2053692A6A27CABBB7BEBB`
SHA512 | `7F89EC04073525CB1B13A392CF9A53C8692D90858DD485C3A3C132BA772D6F09DBACB193BAA04D56C57D7DDA96BB91971289A0092C4002ECC98E21DEC5CD058E`
SSDEEP | `3072:ccYzDbpwNbLGkC8pNs4e9xTV6666666666666666666666666666666666t6666q:OvbpkbLO8bs4KTtQsJkF`

## Runtime Data

### Usage (stdout):
```cmhg
Usage: /usr/bin/date [OPTION]... [+FORMAT]
  or:  /usr/bin/date [-u|--utc|--universal] [MMDDhhmm[[CC]YY][.ss]]
Display the current time in the given FORMAT, or set the system date.

Mandatory arguments to long options are mandatory for short options too.
  -d, --date=STRING          display time described by STRING, not 'now'
      --debug                annotate the parsed date,
                              and warn about questionable usage to stderr
  -f, --file=DATEFILE        like --date; once for each line of DATEFILE
  -I[FMT], --iso-8601[=FMT]  output date/time in ISO 8601 format.
                               FMT='date' for date only (the default),
                               'hours', 'minutes', 'seconds', or 'ns'
                               for date and time to the indicated precision.
                               Example: 2006-08-14T02:34:56-06:00
  -R, --rfc-email            output date and time in RFC 5322 format.
                               Example: Mon, 14 Aug 2006 02:34:56 -0600
      --rfc-3339=FMT         output date/time in RFC 3339 format.
                               FMT='date', 'seconds', or 'ns'
                               for date and time to the indicated precision.
                               Example: 2006-08-14 02:34:56-06:00
  -r, --reference=FILE       display the last modification time of FILE
  -s, --set=STRING           set time described by STRING
  -u, --utc, --universal     print or set Coordinated Universal Time (UTC)
      --help     display this help and exit
      --version  output version information and exit

FORMAT controls the output.  Interpreted sequences are:

  %%   a literal %
  %a   locale's abbreviated weekday name (e.g., Sun)
  %A   locale's full weekday name (e.g., Sunday)
  %b   locale's abbreviated month name (e.g., Jan)
  %B   locale's full month name (e.g., January)
  %c   locale's date and time (e.g., Thu Mar  3 23:05:25 2005)
  %C   century; like %Y, except omit last two digits (e.g., 20)
  %d   day of month (e.g., 01)
  %D   date; same as %m/%d/%y
  %e   day of month, space padded; same as %_d
  %F   full date; like %+4Y-%m-%d
  %g   last two digits of year of ISO week number (see %G)
  %G   year of ISO week number (see %V); normally useful only with %V
  %h   same as %b
  %H   hour (00..23)
  %I   hour (01..12)
  %j   day of year (001..366)
  %k   hour, space padded ( 0..23); same as %_H
  %l   hour, space padded ( 1..12); same as %_I
  %m   month (01..12)
  %M   minute (00..59)
  %n   a newline
  %N   nanoseconds (000000000..999999999)
  %p   locale's equivalent of either AM or PM; blank if not known
  %P   like %p, but lower case
  %q   quarter of year (1..4)
  %r   locale's 12-hour clock time (e.g., 11:11:04 PM)
  %R   24-hour hour and minute; same as %H:%M
  %s   seconds since 1970-01-01 00:00:00 UTC
  %S   second (00..60)
  %t   a tab
  %T   time; same as %H:%M:%S
  %u   day of week (1..7); 1 is Monday
  %U   week number of year, with Sunday as first day of week (00..53)
  %V   ISO week number, with Monday as first day of week (01..53)
  %w   day of week (0..6); 0 is Sunday
  %W   week number of year, with Monday as first day of week (00..53)
  %x   locale's date representation (e.g., 12/31/99)
  %X   locale's time representation (e.g., 23:13:48)
  %y   last two digits of year (00..99)
  %Y   year
  %z   +hhmm numeric time zone (e.g., -0400)
  %:z  +hh:mm numeric time zone (e.g., -04:00)
  %::z  +hh:mm:ss numeric time zone (e.g., -04:00:00)
  %:::z  numeric time zone with : to necessary precision (e.g., -04, +05:30)
  %Z   alphabetic time zone abbreviation (e.g., EDT)

By default, date pads numeric fields with zeroes.
The following optional flags may follow '%':

  -  (hyphen) do not pad the field
  _  (underscore) pad with spaces
  0  (zero) pad with zeros
  +  pad with zeros, and put '+' before future years with >4 digits
  ^  use upper case if possible
  #  use opposite case if possible

After any flags comes an optional field width, as a decimal number;
then an optional modifier, which is either
E to use the locale's alternate representations if available, or
O to use the locale's alternate numeric symbols if available.

Examples:
Convert seconds since the epoch (1970-01-01 UTC) to a date
  $ date --date='@2147483647'

Show the time on the west coast of the US (use tzselect(1) to find TZ)
  $ TZ='America/Los_Angeles' date

Show the local time for 9AM next Friday on the west coast of the US
  $ date --date='TZ="America/Los_Angeles" 09:00 next Fri'

GNU coreutils online help: <https://www.gnu.org/software/coreutils/>
Report any translation bugs to <https://translationproject.org/team/>
Full documentation <https://www.gnu.org/software/coreutils/date>
or available locally via: info '(coreutils) date invocation'

```

### Usage (stderr):
```cmhg
date: unknown option -- h
Try '/usr/bin/date --help' for more information.

```

### Loaded Modules:

Path |
-- |
C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\date.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `045D8F14A82147641722D4FAFC66BC80`
* Thumbprint: `FB713A60A7FA79DFC03CB301CA05D4E8C1BDD431`
* Issuer: CN=DigiCert SHA2 Assured ID Code Signing CA, OU=www.digicert.com, O=DigiCert Inc, C=US
* Subject: CN="GitHub, Inc.", O="GitHub, Inc.", L=San Francisco, S=California, C=US

## File Metadata

* Original Filename: 
* Product Name: 
* Company Name: 
* File Version: 
* Product Version: 
* Language: 
* Legal Copyright: 

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Users\WDAGUtilityAccount\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\date.exe](date.exe-6DCB5C5CA565B5AB695F6E5662F3F5CC.md) | 100


## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## date

Displays or sets the system date. If used without parameters, **date** displays the current system date setting and prompts you to enter a new date.

>[!IMPORTANT]
> You must be an administrator to use this command.

### Syntax

```
date [/t | <month-day-year>]
```

#### Parameters

| Parameter | Description |
| --------- | ----------- |
| `<month-day-year>` | Sets the date specified, where *month* is the month (one or two digits, including values 1 through 12), *day* is the day (one or two digits, including values 1 through 31), and *year* is the year (two or four digits, including the values 00 through 99 or 1980 through 2099). You must separate values for *month*, *day*, and *year* with periods (.), hyphens (-), or slash marks (/).<p>**Note:** Be aware that if you use 2 digits to represent the year, the values 80-99 correspond to 1980 through 1999. |
| /t | Displays the current date without prompting you for a new date. |
| /? | Displays help at the command prompt. |

### Examples

If command extensions are enabled, to display the current system date, type:

```
date /t
```

To change the current system date to August 3, 2007, you can type any of the following:

```
date 08.03.2007
date 08-03-07
date 8/3/07
```

To display the current system date, followed by a prompt to enter a new date, type:

```
The current date is: Mon 04/02/2007
Enter the new date: (mm-dd-yyyy)
```

To keep the current date and return to the command prompt, press **ENTER**. To change the current date, type the new date and then press **ENTER**.

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020 Strontic.


