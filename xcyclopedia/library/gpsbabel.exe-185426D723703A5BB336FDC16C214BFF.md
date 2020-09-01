---
title: gpsbabel.exe | 
---

# gpsbabel.exe 

* File Path: `C:\program files (x86)\Google\Google Earth Pro\client\gpsbabel.exe`

## Hashes

Type | Hash
-- | --
MD5 | `185426D723703A5BB336FDC16C214BFF`
SHA1 | `9B5B2DB2E386E5F15ADDE4CF497EE1B7B817F1D2`
SHA256 | `404CD331D409A1D61B6FD3F656087C2C6DBDC6786D60C2C495CC999B3444ADB3`
SHA384 | `CEFA256E97FB2EEDCE7FFACE0A17D2B659AD2F408C817713BE33A2AB5E5862CDE67D90BEC063354EEF7219BADD6D59D7`
SHA512 | `CB15034645C154829E3ED4A76FBABDFBC844958A0934D041905AC039D9EEDB2A0A90948414A1BD3BF6A5E3572E1900C7AE6C807B5333E2DF2CB30C1934543FBD`
SSDEEP | `24576:Z4zLA+L1DPzS33GBTKz52IIDbOu0RKV7+7CVsCmj7:Z4zLA+L1bzcGBTWoIIXOu0RKmCQj7`

## Runtime Data

### Usage (stdout):
```Batchfile
GPSBabel Version 1.6.0.  http://www.gpsbabel.org

Usage:
    C:\program files (x86)\Google\Google Earth Pro\client\gpsbabel.exe [options] -i INTYPE -f INFILE [filter] -o OUTTYPE -F OUTFILE
    C:\program files (x86)\Google\Google Earth Pro\client\gpsbabel.exe [options] -i INTYPE -o OUTTYPE INFILE [filter] OUTFILE

    Converts GPS route and waypoint data from one format type to another.
    The input type and filename are specified with the -i INTYPE
    and -f INFILE options. The output type and filename are specified
    with the -o OUTTYPE and -F OUTFILE options.
    If '-' is used for INFILE or OUTFILE, stdin or stdout will be used.

    In the second form of the command, INFILE and OUTFILE are the
    first and second positional (non-option) arguments.

    INTYPE and OUTTYPE must be one of the supported file types and
    may include options valid for that file type.  For example:
      'gpx', 'gpx,snlen=10' and 'ozi,snlen=10,snwhite=1'
    (without the quotes) are all valid file type specifications.

Options:
    -p               Preferences file (gpsbabel.ini)
    -s               Synthesize shortnames
    -r               Process route information
    -t               Process track information
    -T               Process realtime tracking information
    -w               Process waypoint information [default]
    -b               Process command file (batch mode)
    -x filtername    Invoke filter (placed between inputs and output) 
    -D level         Set debug level [0]
    -h, -?           Print detailed help and exit
    -V               Print GPSBabel version and exit

File Types (-i and -o options):
	gdb                   Garmin MapSource - gdb
	  cat                   Default category on output (1..16) 
	  bitscategory          Bitmap of categories 
	  ver                   Version of gdb file to generate (1..3) 
	  via                   (0/1) Drop route points that do not have an equivalent w 
	  roadbook              (0/1) Include major turn points (with description) from  
	mapsource             Garmin MapSource - mps
	  snlen                 Length of generated shortnames 
	  snwhite               (0/1) Allow whitespace synth. shortnames 
	  mpsverout             Version of mapsource file to generate (3,4,5) 
	  mpsmergeout           (0/1) Merge output with existing file 
	  mpsusedepth           (0/1) Use depth values on output (default is ignore) 
	  mpsuseprox            (0/1) Use proximity values on output (default is ignore) 
	pcx                   Garmin PCX5
	  deficon               Default icon name 
	  cartoexploreur        (0/1) Write tracks compatible with Carto Exploreur 
	garmin                Garmin serial/USB protocol
	  snlen                 Length of generated shortnames 
	  snwhite               (0/1) Allow whitespace synth. shortnames 
	  deficon               Default icon name 
	  get_posn              (0/1) Return current position as a waypoint 
	  power_off             (0/1) Command unit to power itself down 
	  erase_t               (0/1) Erase existing courses when writing new ones 
	  resettime             (0/1) Sync GPS time to computer time 
	  category              Category number to use for written waypoints 
	  bitscategory          Bitmap of categories 
	  baud                  Speed in bits per second of serial port (baud=9600 
	gtrnctr               Garmin Training Center (.tcx/.crs/.hst/.xml)
	  course                (0/1) Write course rather than history, default yes 
	  sport                 Sport: Biking (deflt), Running, MultiSport, Other 
	geo                   Geocaching.com .loc
	  deficon               Default icon name 
	  nuke_placer           (0/1) Omit Placer name 
	geojson               GeoJson
	  compact               (0/1) Compact Output. Default is off. 
	kml                   Google Earth (Keyhole) Markup Language
	  deficon               Default icon name 
	  lines                 (0/1) Export linestrings for tracks and routes 
	  points                (0/1) Export placemarks for tracks and routes 
	  line_width            Width of lines, in pixels 
	  line_color            Line color, specified in hex AABBGGRR 
	  floating              (0/1) Altitudes are absolute and not clamped to ground 
	  extrude               (0/1) Draw extrusion line from trackpoint to ground 
	  track                 (0/1) Write KML track (default = 0) 
	  trackdata             (0/1) Include extended data for trackpoints (default = 1 
	  trackdirection        (0/1) Indicate direction of travel in track icons (defau 
	  units                 Units used when writing comments ('s'tatute, 'm'et 
	  labels                (0/1) Display labels on track and routepoints  (default  
	  max_position_point    Retain at most this number of position points  (0  
	  rotate_colors         Rotate colors for tracks and routes (default autom 
	  prec                  Precision of coordinates, number of decimals 
	gpx                   GPX XML
	  snlen                 Length of generated shortnames 
	  suppresswhite         (0/1) No whitespace in generated shortnames 
	  logpoint              (0/1) Create waypoints from geocache log entries 
	  urlbase               Base URL for link tag in output 
	  gpxver                Target GPX version for output 
	  humminbirdextensio    (0/1) Add info (depth) as Humminbird extension 
	  garminextensions      (0/1) Add info (depth) as Garmin extension 
	  elevprec              Precision of elevations, number of decimals 
	mapsend               Magellan Mapsend
	  trkver                MapSend version TRK file to generate (3,4) 
	magellanx             Magellan SD files (as for eXplorist)
	  deficon               Default icon name 
	  maxcmts               Max number of comments to write (maxcmts=200) 
	magellan              Magellan SD files (as for Meridian)
	  deficon               Default icon name 
	  maxcmts               Max number of comments to write (maxcmts=200) 
	magellan              Magellan serial protocol
	  deficon               Default icon name 
	  maxcmts               Max number of comments to write (maxcmts=200) 
	  baud                  Numeric value of bitrate (baud=4800) 
	  noack                 (0/1) Suppress use of handshaking in name of speed 
	  nukewpt               (0/1) Delete all waypoints 
	nmea                  NMEA 0183 sentences
	  snlen                 Max length of waypoint name to write 
	  gprmc                 (0/1) Read/write GPRMC sentences 
	  gpgga                 (0/1) Read/write GPGGA sentences 
	  gpvtg                 (0/1) Read/write GPVTG sentences 
	  gpgsa                 (0/1) Read/write GPGSA sentences 
	  date                  Complete date-free tracks with given date (YYYYMMD 
	  get_posn              (0/1) Return current position as a waypoint 
	  pause                 Decimal seconds to pause between groups of strings 
	  append_positioning    (0/1) Append realtime positioning data to the output fil 
	  baud                  Speed in bits per second of serial port (baud=4800 
	  gisteq                (0/1) Write tracks for Gisteq Phototracker 
	  ignore_fix            (0/1) Accept position fixes in gpgga marked invalid 
	ozi                   OziExplorer
	  pack                  (0/1) Write all tracks into one file 
	  snlen                 Max synthesized shortname length 
	  snwhite               (0/1) Allow whitespace synth. shortnames 
	  snupper               (0/1) UPPERCASE synth. shortnames 
	  snunique              (0/1) Make synth. shortnames unique 
	  wptfgcolor            Waypoint foreground color 
	  wptbgcolor            Waypoint background color 
	  proximity             Proximity distance 
	  altunit               Unit used in altitude values 
	  proxunit              Unit used in proximity values 
	  codec                 codec to use for reading and writing strings (defa 
	wbt                   Wintec WBT-100/200 GPS Download
	  erase                 (0/1) Erase device data after download 

Supported data filters:
	track                 Manipulate track lists                            
	  move                  Correct trackpoint timestamps by a delta 
	  pack                  Pack all tracks into one 
	  split                 Split by date or time interval (see README) 
	  sdistance             Split by distance 
	  merge                 Merge multiple tracks for the same way 
	  name                  Use only track(s) where title matches given name 
	  start                 Use only track points after this timestamp 
	  stop                  Use only track points before this timestamp 
	  title                 Basic title for new track(s) 
	  fix                   Synthesize GPS fixes (PPS, DGPS, 3D, 2D, NONE) 
	  course                Synthesize course 
	  speed                 Synthesize speed 
	  seg2trk               Split track at segment boundaries into multiple tr 
	  trk2seg               Merge tracks inserting segment separators at bound 
	  segment               segment tracks with abnormally long gaps 
	  faketime              Add specified timestamp to each trackpoint 
	  discard               Discard track points without timestamps during mer 
	  minimum_points        Discard tracks with fewer than these points 

```

### Loaded Modules:

Path |
-- |
C:\program files (x86)\Google\Google Earth Pro\client\gpsbabel.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `0C15BE4A15BB0903C901B1D6C265302F`
* Thumbprint: `CB7E84887F3C6015FE7EDFB4F8F36DF7DC10590E`
* Issuer: CN=DigiCert SHA2 Assured ID Code Signing CA, OU=www.digicert.com, O=DigiCert Inc, C=US
* Subject: CN=Google LLC, O=Google LLC, L=Mountain View, S=ca, C=US

## File Metadata

* Original Filename: 
* Product Name: 
* Company Name: 
* File Version: 
* Product Version: 
* Language: 
* Legal Copyright: 





MIT License. Copyright (c) 2020 Strontic.


