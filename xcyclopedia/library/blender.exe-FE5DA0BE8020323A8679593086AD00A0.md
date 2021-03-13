---
title: blender.exe | Blender
excerpt: What is blender.exe?
---

# blender.exe 

* File Path: `C:\Program Files\Blender Foundation\Blender 2.90\blender.exe`
* Description: Blender

## Hashes

Type | Hash
-- | --
MD5 | `FE5DA0BE8020323A8679593086AD00A0`
SHA1 | `B4E36FAA7BB329F18E505F6255074CA4D3F3DEAE`
SHA256 | `EB230ABFCECDCD7C609629B50F10D4B95ABF41D01EF1C9B6CA7CE5CDF8E5E6CC`
SHA384 | `7CCAD7492268A1A26E4FCDC4918C0B17FAA3E2927AAAA1D7AB1BA3598362AD12575FAE911AE8A3F0C9C2D2B0DA8898C6`
SHA512 | `25C08F4811CF49C289A63056EE1B090CAB94CE0D6A6E3B59CCD15AF7F83F3C36085FAD344DFDF900B6D5FFAEEFB2E6DC2671EBDA31235858B491DA6C806D9A89`
SSDEEP | `3145728:bp0Gh8rKcFdV7H9e8Zmmu/u43DKwD76eHa97I6tDAyr4s6J2HLnKAPIFKvPT+iUk:6mmu/u43DKA9Ha97PBvEsoYKAXvr+iUk`
IMP | `84B3DD9830ED66135A777A9904931B9B`
PESHA1 | `7D39593380047AB80C5F8F227E4E2833849D4B49`
PE256 | `DA85A048C0C7281A6389E3915ED056285FF38EA6F2E90B4E9C1BF7D35B42F8D8`

## Runtime Data

### Usage (stdout):
```cmhg
Blender 2.90.1
Usage: blender [args ...] [file] [args ...]

Render Options:
-b or --background 
	Run in background (often used for UI-less rendering).

-a or --render-anim 
	Render frames from start to end (inclusive).

-S or --scene <name>
	Set the active scene <name> for rendering.

-f or --render-frame <frame>
	Render frame <frame> and save it.

	* +<frame> start frame relative, -<frame> end frame relative.
	* A comma separated list of frames can also be used (no spaces).
	* A range of frames can be expressed using '..' separator between the first and last frames (inclusive).


-s or --frame-start <frame>
	Set start to frame <frame>, supports +/- for relative frames too.

-e or --frame-end <frame>
	Set end to frame <frame>, supports +/- for relative frames too.

-j or --frame-jump <frames>
	Set number of frames to step forward after each rendered frame.

-o or --render-output <path>
	Set the render path and file name.
	Use '//' at the start of the path to render relative to the blend-file.

	The '#' characters are replaced by the frame number, and used to define zero padding.

	* 'animation_##_test.png' becomes 'animation_01_test.png'
	* 'test-######.png' becomes 'test-000001.png'

	When the filename does not contain '#', The suffix '####' is added to the filename.

	The frame number will be added at the end of the filename, eg:
	# blender -b animation.blend -o //render_ -F PNG -x 1 -a
	'//render_' becomes '//render_####', writing frames as '//render_0001.png'

-E or --engine <engine>
	Specify the render engine.
	Use '-E' help to list available engines.

-t or --threads <threads>
	Use amount of <threads> for rendering and other operations
	[1-1024], 0 for systems processor count.


Format Options:
-F or --render-format <format>
	Set the render format.
	Valid options are:
	'TGA' 'RAWTGA' 'JPEG' 'IRIS' 'IRIZ' 'AVIRAW' 'AVIJPEG' 'PNG' 'BMP'

	Formats that can be compiled into Blender, not available on all systems:
	'HDR' 'TIFF' 'OPEN_EXR' 'OPEN_EXR_MULTILAYER' 'MPEG' 'CINEON' 'DPX' 'DDS' 'JP2'

-x or --use-extension <bool>
	Set option to add the file extension to the end of the file.


Animation Playback Options:
-a <options> <file(s)>
	Instead of showing Blender's user interface, this runs Blender as an animation player,
	to view movies and image sequences rendered in Blender (ignored if '-b' is set).

	Playback Arguments:

	-p <sx> <sy>
		Open with lower left corner at <sx>, <sy>.
	-m
		Read from disk (Do not buffer).
	-f <fps> <fps-base>
		Specify FPS to start with.
	-j <frame>
		Set frame step to <frame>.
	-s <frame>
		Play from <frame>.
	-e <frame>
		Play until <frame>.


Window Options:
-w or --window-border 
	Force opening with borders.

-W or --window-fullscreen 
	Force opening in fullscreen mode.

-p or --window-geometry <sx> <sy> <w> <h>
	Open with lower left corner at <sx>, <sy> and width and height as <w>, <h>.

-M or --window-maximized 
	Force opening maximized.

-con or --start-console 
	Start with the console window open (ignored if '-b' is set), (Windows only).

--no-native-pixels 
	Do not use native pixel size, for high resolution displays (MacBook 'Retina').

--no-window-focus 
	Open behind other windows and without taking focus.


Python Options:
-y or --enable-autoexec 
	Enable automatic Python script execution.

-Y or --disable-autoexec 
	Disable automatic Python script execution (pydrivers & startup scripts), (compiled as non-standard default).


-P or --python <filename>
	Run the given Python script file.

--python-text <name>
	Run the given Python script text block.

--python-expr <expression>
	Run the given expression as a Python script.

--python-console 
	Run Blender with an interactive console.

--python-exit-code <code>
	Set the exit-code in [0..255] to exit if a Python exception is raised
	(only for scripts executed from the command line), zero disables.

--python-use-system-env 
	Allow Python to use system environment variables such as 'PYTHONPATH' and the user site-packages directory.

--addons <addon(s)>
	Comma separated list of add-ons (no spaces).


Logging Options:
--log <match>
	Enable logging categories, taking a single comma separated argument.
	Multiple categories can be matched using a '.*' suffix,
	so '--log "wm.*"' logs every kind of window-manager message.
	Use "^" prefix to ignore, so '--log "*,^wm.operator.*"' logs all except for 'wm.operators.*'
	Use "*" to log everything.

--log-level <level>
	Set the logging verbosity level (higher for more details) defaults to 1,
	use -1 to log all levels.

--log-show-basename 
	Only show file name in output (not the leading path).

--log-show-backtrace 
	Show a back trace for each log message (debug builds only).

--log-show-timestamp 
	Show a timestamp for each log message in seconds since start.

--log-file <filename>
	Set a file to output the log to.


Debug Options:
-d or --debug 
	Turn debugging on.

	* Enables memory error detection
	* Disables mouse grab (to interact with a debugger in some cases)
	* Keeps Python's 'sys.stdin' rather than setting it to None

--debug-value <value>
	Set debug value of <value> on startup.


--debug-events 
	Enable debug messages for the event system.

--debug-ffmpeg 
	Enable debug messages from FFmpeg library.

--debug-handlers 
	Enable debug messages for event handling.

--debug-libmv 
	Enable debug messages from libmv library.

--debug-cycles 
	Enable debug messages from Cycles.

--debug-memory 
	Enable fully guarded memory allocation and debugging.

--debug-jobs 
	Enable time profiling for background jobs.

--debug-python 
	Enable debug messages for Python.

--debug-depsgraph 
	Enable all debug messages from dependency graph.

--debug-depsgraph-eval 
	Enable debug messages from dependency graph related on evaluation.

--debug-depsgraph-build 
	Enable debug messages from dependency graph related on graph construction.

--debug-depsgraph-tag 
	Enable debug messages from dependency graph related on tagging.

--debug-depsgraph-no-threads 
	Switch dependency graph to a single threaded evaluation.

--debug-depsgraph-time 
	Enable debug messages from dependency graph related on timing.

--debug-depsgraph-pretty 
	Enable colors for dependency graph debug messages.

--debug-gpu 
	Enable GPU debug context and information for OpenGL 4.3+.

--debug-gpumem 
	Enable GPU memory stats in status bar.

--debug-gpu-shaders 
	Enable GPU memory stats in status bar.

--debug-gpu-force-workarounds 
	Enable GPU memory stats in status bar.

--debug-wm 
	Enable debug messages for the window manager, shows all operators in search, shows keymap errors.

--debug-xr 
	Enable debug messages for virtual reality contexts.
	Enables the OpenXR API validation layer, (OpenXR) debug messages and general information prints.

--debug-xr-time 
	Enable debug messages for virtual reality frame rendering times.

--debug-all 
	Enable all debug messages.

--debug-io 
	Enable debug messages for I/O (Collada, ...).


--debug-fpe 
	Enable floating point exceptions.

--disable-crash-handler 
	Disable the crash handler.

--disable-abort-handler 
	Disable the abort handler.


Misc Options:
--app-template <template>
	Set the application template (matching the directory name), use 'default' for none.

--factory-startup 
	Skip reading the BLENDER_STARTUP_FILE in the users home directory.

--enable-event-simulate 
	Enable event simulation testing feature 'bpy.types.Window.event_simulate'.


--env-system-datafiles 
	Set the BLENDER_SYSTEM_DATAFILES environment variable.

--env-system-scripts 
	Set the BLENDER_SYSTEM_SCRIPTS environment variable.

--env-system-python 
	Set the BLENDER_SYSTEM_PYTHON environment variable.


-noaudio 
	Force sound system to None.

-setaudio 
	Force sound system to a specific device.
	'NULL' 'SDL' 'OPENAL' 'JACK'.


-h or --help 
	Print this help text and exit.

-R 
	Register blend-file extension, then exit (Windows only).

-r 
	Silently register blend-file extension, then exit (Windows only).

-v or --version 
	Print Blender version and exit.

-- 
	End option processing, following arguments passed unchanged. Access via Python's 'sys.argv'.


Other Options:
/? 
	Print this help text and exit (windows only).

--debug-freestyle 
	Enable debug messages for Freestyle.

--debug-ghost 
	Enable debug messages for event handling.

--debug-depsgraph-uuid 
	Enable debug messages from dependency graph related on graph construction.

--verbose <verbose>
	Set the logging verbosity level for debug messages that support it.


Argument Parsing:
	Arguments must be separated by white space, eg:
	# blender -ba test.blend
	...will exit since '-ba' is an unknown argument.
Argument Order:
	Arguments are executed in the order they are given. eg:
	# blender --background test.blend --render-frame 1 --render-output '/tmp'
	...will not render to '/tmp' because '--render-frame 1' renders before the output path is set.
	# blender --background --render-output /tmp test.blend --render-frame 1
	...will not render to '/tmp' because loading the blend-file overwrites the render output that was set.
	# blender --background test.blend --render-output /tmp --render-frame 1
	...works as expected.

Environment Variables:
  $BLENDER_USER_CONFIG      Directory for user configuration files.
  $BLENDER_USER_SCRIPTS     Directory for user scripts.
  $BLENDER_SYSTEM_SCRIPTS   Directory for system wide scripts.
  $BLENDER_USER_DATAFILES   Directory for user data files (icons, translations, ..).
  $BLENDER_SYSTEM_DATAFILES Directory for system wide data files.
  $BLENDER_SYSTEM_PYTHON    Directory for system Python libraries.
  $TEMP                     Store temporary files here.
  $SDL_AUDIODRIVER          LibSDL audio driver - alsa, esd, dma.
Error: Not freed memory blocks: 371, total unfreed memory 0.135872 MB

```

### Usage (stderr):
```cmhg
Warning! Using result of ChoosePixelFormat.
Warning! Using result of ChoosePixelFormat.
Warning! Using result of ChoosePixelFormat.
Warning! Using result of ChoosePixelFormat.
Warning! Using result of ChoosePixelFormat.
Warning! Using result of ChoosePixelFormat.
Warning! Using result of ChoosePixelFormat.
Warning! Using result of ChoosePixelFormat.
Warning! Using result of ChoosePixelFormat.
Warning! Using result of ChoosePixelFormat.
Warning! Using result of ChoosePixelFormat.
Warning! Using result of ChoosePixelFormat.
Warning! Using result of ChoosePixelFormat.
Warning! Using result of ChoosePixelFormat.
Win32 Error# (0): The operation completed successfully.

```

### Child Processes:
conhost.exe

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Windows\Fonts\StaticCache.dat | File
(R-D)   C:\Windows\System32\en-US\avicap32.dll.mui | File
(R-D)   C:\Windows\System32\en-US\KernelBase.dll.mui | File
(R-D)   C:\Windows\System32\en-US\msvfw32.dll.mui | File
(R-D)   C:\Windows\SystemResources\imageres.dll.mun | File
(RW-)   C:\Program Files\Blender Foundation\Blender 2.90\2.90\datafiles\fonts\bmonofont-i18n.ttf | File
(RW-)   C:\Program Files\Blender Foundation\Blender 2.90\2.90\datafiles\fonts\droidsans.ttf | File
(RW-)   C:\Program Files\Blender Foundation\Blender 2.90\blender.crt | File
(RW-)   C:\Windows\WinSxS\amd64_microsoft.windows.common-controls_6595b64144ccf1df_6.0.19041.488_none_ca04af081b815d21 | File
(RW-)   C:\xCyclopedia | File
\BaseNamedObjects\__ComCatalogCache__ | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\Sessions\1\BaseNamedObjects\1ebcHWNDInterface:b010a | Section
\Sessions\1\BaseNamedObjects\windows_shell_global_counters | Section
\Sessions\1\Windows\Theme2547664911 | Section
\Windows\Theme3854699184 | Section


### Loaded Modules:

Path |
-- |
C:\Program Files\Blender Foundation\Blender 2.90\blender.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `0FC2CFDD6D5AD878EA6A7AFB6D7A5CD2`
* Thumbprint: `18A976606F95649BB479D1934F21F2AC37D642A8`
* Issuer: CN=SSL.com Code Signing Intermediate CA RSA R1, O=SSL Corp, L=Houston, S=Texas, C=US
* Subject: CN=Stichting Blender Foundation, O=Stichting Blender Foundation, L=Amsterdam, S=Noord-Holland, C=NL

## File Metadata

* Original Filename: blender.exe
* Product Name: Blender
* Company Name: Blender Foundation
* File Version: 2.90
* Product Version: 2.90
* Language: English (United States)
* Legal Copyright: GPLv3 (Blender Foundation)
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/66
* VirusTotal Link: https://www.virustotal.com/gui/file/eb230abfcecdcd7c609629b50f10d4b95abf41d01ef1c9b6ca7ce5cdf8e5e6cc/detection/





MIT License. Copyright (c) 2020-2021 Strontic.


