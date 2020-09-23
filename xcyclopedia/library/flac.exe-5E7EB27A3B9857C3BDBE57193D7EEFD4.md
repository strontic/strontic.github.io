---
title: flac.exe | 
excerpt: What is flac.exe?
---

# flac.exe 

* File Path: `C:\program files (x86)\MusicBee\Codec\flac.exe`

## Hashes

Type | Hash
-- | --
MD5 | `5E7EB27A3B9857C3BDBE57193D7EEFD4`
SHA1 | `C84472A15355C149320830EEF80D64B86F081BFE`
SHA256 | `BC40922B374126B65F4B82F2FC83685421C7FCF409BD1598892DF26A45E17075`
SHA384 | `516588C87E6C9A30961A6E73B5E49F8272E83DE0E4B70765D6DD799191B8F528F5959F4F0BFDE197169A2707E8A05BF1`
SHA512 | `1748B4ACFF6A2BC72DFA89CBAAE7B1F7AB5C32532D5601D56936C7CBCA1FB87F4B5E4A01D7C240F737105B9E9B6CF18258E4BBD396C4E38928215334E7519B2A`
SSDEEP | `12288:TY6Yi7JdO9+yC7GnFhSkn7nW6D8YMHIdF:iil49+yC7CFUkn7nWa8YyIdF`

## Runtime Data

### Usage (stdout):
```cmhg
===============================================================================
flac - Command-line FLAC encoder/decoder version 1.3.2
Copyright (C) 2000-2009  Josh Coalson
Copyright (C) 2011-2016  Xiph.Org Foundation

This program is free software; you can redistribute it and/or
modify it under the terms of the GNU General Public License
as published by the Free Software Foundation; either version 2
of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License along
with this program; if not, write to the Free Software Foundation, Inc.,
51 Franklin Street, Fifth Floor, Boston, MA 02110-1301 USA.
===============================================================================
Usage:

 Encoding: flac [<general-options>] [<encoding/format-options>] [INPUTFILE [...]]
 Decoding: flac -d [<general-options>] [<format-options>] [FLACFILE [...]]
  Testing: flac -t [<general-options>] [FLACFILE [...]]
Analyzing: flac -a [<general-options>] [<analysis-options>] [FLACFILE [...]]

Be sure to read the list of known bugs at:
http://xiph.org/flac/documentation_bugs.html

general options:
  -v, --version                Show the flac version number
  -h, --help                   Show this screen
  -H, --explain                Show detailed explanation of usage and options
  -d, --decode                 Decode (the default behavior is to encode)
  -t, --test                   Same as -d except no decoded file is written
  -a, --analyze                Same as -d except an analysis file is written
  -c, --stdout                 Write output to stdout
  -s, --silent                 Do not write runtime encode/decode statistics
      --totally-silent         Do not print anything, including errors
      --no-utf8-convert        Do not convert tags from local charset to UTF-8
  -w, --warnings-as-errors     Treat all warnings as errors
  -f, --force                  Force overwriting of output files
  -o, --output-name=FILENAME   Force the output file name
      --output-prefix=STRING   Prepend STRING to output names
      --delete-input-file      Deletes after a successful encode/decode
      --preserve-modtime       Output files keep timestamp of input (default)
      --keep-foreign-metadata  Save/restore WAVE or AIFF non-audio chunks
      --skip={#|mm:ss.ss}      Skip the given initial samples for each input
      --until={#|[+|-]mm:ss.ss}  Stop at the given sample for each input file
      --ogg                    Use Ogg as transport layer
      --serial-number          Serial number to use for the FLAC stream
analysis options:
      --residual-text          Include residual signal in text output
      --residual-gnuplot       Generate gnuplot files of residual distribution
decoding options:
  -F, --decode-through-errors  Continue decoding through stream errors
      --cue=[#.#][-[#.#]]      Set the beginning and ending cuepoints to decode
encoding options:
  -V, --verify                 Verify a correct encoding
      --lax                    Allow encoder to generate non-Subset files
      --ignore-chunk-sizes     Ignore data chunk sizes in WAVE/AIFF files
      --sector-align (DEPRECATED) Align multiple files on sector boundaries
      --replay-gain            Calculate ReplayGain & store in FLAC tags
      --cuesheet=FILENAME      Import cuesheet and store in CUESHEET block
      --picture=SPECIFICATION  Import picture and store in PICTURE block
  -T, --tag=FIELD=VALUE        Add a FLAC tag; may appear multiple times
      --tag-from-file=FIELD=FILENAME   Like --tag but gets value from file
  -S, --seekpoint={#|X|#x|#s}  Add seek point(s)
  -P, --padding=#              Write a PADDING block of length #
  -0, --compression-level-0, --fast  Synonymous with -l 0 -b 1152 -r 3
  -1, --compression-level-1          Synonymous with -l 0 -b 1152 -M -r 3
  -2, --compression-level-2          Synonymous with -l 0 -b 1152 -m -r 3
  -3, --compression-level-3          Synonymous with -l 6 -b 4096 -r 4
  -4, --compression-level-4          Synonymous with -l 8 -b 4096 -M -r 4
  -5, --compression-level-5          Synonymous with -l 8 -b 4096 -m -r 5
  -6, --compression-level-6          Synonymous with -l 8 -b 4096 -m -r 6
                                        -A tukey(0.5) -A partial_tukey(2)
  -7, --compression-level-7          Synonymous with -l 12 -b 4096 -m -r 6
                                         -A tukey(0.5) -A partial_tukey(2)
  -8, --compression-level-8, --best  Synonymous with -l 12 -b 4096 -m -r 6
                    -A tukey(0.5) -A partial_tukey(2) -A punchout_tukey(3)
  -b, --blocksize=#                  Specify blocksize in samples
  -m, --mid-side                     Try mid-side coding for each frame
  -M, --adaptive-mid-side            Adaptive mid-side coding for all frames
  -e, --exhaustive-model-search      Do exhaustive model search (expensive!)
  -A, --apodization="function"       Window audio data with given the function
  -l, --max-lpc-order=#              Max LPC order; 0 => only fixed predictors
  -p, --qlp-coeff-precision-search   Exhaustively search LP coeff quantization
  -q, --qlp-coeff-precision=#        Specify precision in bits
  -r, --rice-partition-order=[#,]#   Set [min,]max residual partition order
format options:
      --force-raw-format       Treat input or output as raw samples
      --force-aiff-format      Force decoding to AIFF format
      --force-rf64-format      Force decoding to RF64 format
      --force-wave64-format    Force decoding to Wave64 format
raw format options:
      --endian={big|little}    Set byte order for samples
      --channels=#             Number of channels
      --bps=#                  Number of bits per sample
      --sample-rate=#          Sample rate in Hz
      --sign={signed|unsigned} Sign of samples
      --input-size=#           Size of the raw input in bytes
negative options:
      --no-adaptive-mid-side
      --no-cued-seekpoints
      --no-decode-through-errors
      --no-delete-input-file
      --no-error-on-compression-fail
      --no-preserve-modtime
      --no-keep-foreign-metadata
      --no-exhaustive-model-search
      --no-lax
      --no-mid-side
      --no-ogg
      --no-padding
      --no-qlp-coeff-prec-search
      --no-replay-gain
      --no-residual-gnuplot
      --no-residual-text
      --no-ignore-chunk-sizes
      --no-sector-align
      --no-seektable
      --no-silent
      --no-force
      --no-verify
      --no-warnings-as-errors

```

### Usage (stderr):
```cmhg

flac 1.3.2
Copyright (C) 2000-2009  Josh Coalson, 2011-2016  Xiph.Org Foundation
flac comes with ABSOLUTELY NO WARRANTY.  This is free software, and you are
welcome to redistribute it under certain conditions.  Type `flac' for details.

ERROR: can't open input file help: No such file or directory

```

### Loaded Modules:

Path |
-- |
C:\program files (x86)\MusicBee\Codec\flac.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: The file C:\program files (x86)\MusicBee\Codec\flac.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at https:/go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: 
* Product Name: 
* Company Name: 
* File Version: 
* Product Version: 
* Language: 
* Legal Copyright: 






MIT License. Copyright (c) 2020 Strontic.


