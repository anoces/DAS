


# TARGET :
- Change Files name with Pattern Customer.
- Example : "161 - 9A - ..." or " 61 - 6B ".

# INPUT :
- Audio Sound.

# OUTPUT :
- Change files name.

# RULER :
- Pattern name report or anyfiles used :
"yyMMddhhmmss-Millisecond-Random" Example :
"260701135500-761-9A6X3E"
- Do not anyfiles pass without "ASSRegistry.py".
- Registry is the single source of truth.
- "\Logs\..." This path for logs files only.
- "\Payload\..." Analyze per one payload create payload
or create used pattern name per hash or per one analyzer,
Used "260701135500-761-9A6X3E.parquet".

# ENCRYPTION :
* Encryption any files for protection Edited File.
* Extensions: .pyd, .dll, .sig, ...
* All Source code be done any files include encryption.

# BUILD AND INSTALLER [ EXE ].
- Used NSIS And NUNIKA.
- Software or System used free 3 Day.
- License Key : Activate Full License.

# MODULE IMPORT :

1.- NumPy
2.- SciPy
3.- Numba
PURPOSE :
- Scientific Computing.
BOUNDARY :
- Matrix
- Vector
- DSP
- Signal
- Numerical

- - - 

4.- Polars
5.- PyArrow
PURPOSE :
- Data Engin.
BOUNDARY :
- DataFrame
- Search
- Sort
- Join
- Cache
- Parquet

- - - 

7.- Orjson
PURPOSE :
- Serialization
BOUNDARY :
- Payload
- Cache
- Config
- RuntimeData

- - -
8.- Platformdirs
9.- Psutil
PURPOSE :
- System
BOUNDARY :
- Cpu
- Memory
- Disk
- Config
- CachePath

- - -

10.- Tqdm
11.- Xxhash
12.- PythonDotenv
PURPOSE :
- Untility
BOUNDARY :
- Progress
- FileFingerPrint
- Configuration

# VENDOR [ LIBRARY ].
* Source code downloading library github and build
to DLL Native to another folder.
- Ffmpeg
- Essentia
- Taglib
- Eigen
- Fftw3
- Audioflux
- Basics
- Drlibs
- Dsp
- Jsondevelop (nlohmann/json)
- Kissfft
- Libebur128
- Libxtract
- Miniaudio
- Onnxruntime
- Pffft
- Signalsmithstretch
- Tinyxml2

# RUNTIME [ WARNING LICENSE ].
- Essentia
- Fftw3

# RUNTIME [ RUNTIME USED ].
- Ffmpeg
- Taglib
- Eigen
- Audioflux
- Basics
- Drlibs
- Dsp
- Jsondevelop (nlohmann/json)
- Kissfft
- Libebur128
- Libxtract
- Miniaudio
- Onnxruntime
- Pffft
- Signalsmithstretch
- Tinyxml2

# ANALYZE INCLUDE :
- BPM, KEY, GENRE, BITRATE, SAMPLE RATE, CODEC, ...
- Used Library "ESSENTIA" for analyze.

# WORKING STEP REQUIREMENT :
- Choose or Dragging Path Folder Entry Input source
include all aduio files supported.
- Choose output or destination source.
- Click or Processing Start Analyze.
- Waiting propress be done for analyze.
- Payload Data about Metadata, Decoder, ...
- Mapping Source Decision for Bpm, Key, Genre, ...
- Expand metadata.
- Changing files name with Pattern User Requirements.
- Output files or destination source.
- Recheck or validate just be done.
- Done.

# REGISTRY :
* PATH : ASS-0.0.3-R\Registry\...
1.- ASSRegistry.json
BOUNDARY :
- Index Files Registry.
2.- ASSDecisionRegistry.json
3.- ASSPayloadRegistry.json
4.- 

# FILES :
1.- ASSApplication.py
- - -
PURPOSE
- Application Entry Point
- Initialize Runtime
- Create Main Window
- Control Application Lifecycle
BOUNDARY
- Interface
- Startup / Shutdown
- Global Application Control

2.- ASSGui.py
- - -
PURPOSE
- Main User Interface
- Handle User Interaction
- Display Analysis Result
- Dispatch User Commands
BOUNDARY
- GUI Only
- No Business Logic
- No Audio Analysis

3.- ASSGuiWorker.py
- - -
PURPOSE
- Background Worker
- Execute Long Running Tasks
- Progress Reporting
- Thread Communication
BOUNDARY
- Background Process Only
- No Analysis Logic

4. ASSInspector.py
- - -
PURPOSE
- Inspect Input Files
- Validate Audio Files
- Read Metadata
- Detect Audio Information
BOUNDARY
- Metadata
- File Inspection
- File Validation
- No Audio Analysis

5. ASSAnalyze.py
- - -
PURPOSE
- Central Analysis Orchestrator
- Execute Analysis Pipeline
- Manage Analysis Flow
- Coordinate Runtime Modules
BOUNDARY
- Orchestrated Analysis Only
- No GUI
- No File Storage

6.- ASSRuntime.py
- - -
PURPOSE
- Runtime Manager
- Load Native Libraries
- Manage Runtime Environment
- Provide Runtime Services
BOUNDARY
- Runtime Layer
- Native Library Access
- Environment Initialization

7.- ASSPayload.py
- - -
PURPOSE
- Create Analysis Payload
- Read / Write Payload
- Serialize Analysis Data
- Exchange Data Between Modules
BOUNDARY
- Payload Only
- No Analysis

8.- ASSVerifiedPayload.py
- - -
PURPOSE
- Validate Payload
- Process Verified Analysis Data
- Ensure Payload Integrity
BOUNDARY
- Verified Payload Processing
- Validation Layer

9.- ASSCacheFile.py
- - -
PURPOSE
- Cache Manager
- Read Cache
- Write Cache
- Cache Validation
BOUNDARY
- Cache Only
- No Analysis Logic

10.- ASSReport.py
- - -
PURPOSE
- Generate Analysis Report
- Export Result
- Read / Write Report Files
BOUNDARY
- Report Generation
- File Output

11.- ASSLogs.py
- - -
PURPOSE
- Logging System
- Read / Write Log Files
- Error Logging
- Debug Logging
BOUNDARY
- Logging Only
- No Business Logic

12.- ASSRegistry.py
- - -
PURPOSE :
- Central data "json".
- Do not process any file production or core process
to registry without pass ASSRegistry.py first.
BOUNDARY :
- Access "\Registry\...".
- Read Registry.
- Write Registry.
- Update Registry.

13.- ASSNative.py
- - - 
PURPOSE :
- Load Module or Library from "\Runtime\...".
BOUNDARY :
- Read core library runtime process.

14.- ASSConfig.py
- - - 
PURPOSE :
- Configuration Management.
- Environments.
- Runtime Path.
- Notification.
BOUNDARY :
- Configuration Only.
- No Runtime.

15.- ASSContext.py
- - -
PURPOSE :
- Core Context Process.
- Global Runtime Context.
- Current Session.
- Current Configuration.
- Current User.
BOUNDARY : 
- Context only.
- No Analysis.
- No Gui.
- No Files Access.

16.- ASSVersion.py
- - -
PURPOSE :
- Control Version System.
- Application Version.
- Payload Version.
- Runtime Version.
- Build Version.
- Inataller Vwraion.
BOUNDARY :

17.- ASSException.py

18.- ASSDecision.py
- - - 
PURPOSE : 
- Decision Management with Customer Requirements.
- Score decision with Customer only.
BOUNDARY :
- Read Decision.
- Evaluate, Score, Recommend.
- Update Desicion.

18.- ASSNotifiedManagement.py
- - - 
PURPOSE :
- Control And Management to Provider.
BOUNDARY :

20.- ASSSession.py
- - -
PURPOSE :
BOUNDARY :

21.- ASSState.py
- - -
PURPOSE :
- State.
- Idle.
- Running.
- Pause.
- Cancel.
- Complete.
- Error.
BOUNDARY :

22.- ASSLicense.py
PURPOSE :
- Requirement 3 Day Free trail license.
- Entry Hash Key for full license.
BOUNDARY :
- Read files ASSLicenseRegistry.json with ASSRegistry.py.
- Write for hash key.
- Validate License.
- Check Expire.
- Activate.

23.- ASSNotifiedTelegram.py
- - -
PURPOSE :
- Provider and Owner Telegram.
- Notified "Telegram"
- Notified any process or progress.
- Used "Api Key Token"
BOUNDARY :
BOT1 : Notified System / Development - Notifeid for
Development and include Record Files and Audio Files.
Developer And Administrators is this group.
BOT2 : Notified for User and Customer to this group.

24.- ASSNotifiedDiscord.py
- - -
PURPOSE :
- Provider And Owner Discord.
- Notified "Discord"
- Notified for open System or Program that first times.
- Used "Webhook"
BOUNDARY :
- Notified for get enviroment any thing.
- This group only for Developer and Administrators.

25.- ASSNotifiedLine.py
PURPOSE :
- Provider And Owner Line.
- Notifed "Line".
- Notified only per one day, Set Schedules time 00:00.
BOUNDARY :
- This group only Developer and Administrator.
- Notified Sumary for log and anything per one day.
- On Operating System Opening Service Automatically.

# PIPELINE STAGE :
============================================================
PIPELINE STAGE
============================================================

[ STAGE 01 ]
ASSApplication
------------------------------------------------------------
- Application Entry Point
- Initialize System
- Initialize Configuration
- Initialize Registry
- Initialize Runtime
- Initialize Notification Provider
- Create Application Context
- Create Session
- Launch GUI

                │
                ▼

[ STAGE 02 ]
ASSGui
------------------------------------------------------------
- User Interface
- User Interaction
- Drag & Drop Folder
- Select Output Folder
- Select Pattern
- Display Status
- Display Progress
- Send Request to Worker

                │
                ▼

[ STAGE 03 ]
ASSGuiWorker
------------------------------------------------------------
- Create Analyze Job
- Background Thread
- Progress Callback
- Cancellation Support
- Exception Forwarding

                │
                ▼

[ STAGE 04 ]
ASSContext
------------------------------------------------------------
- Create Runtime Context
- Load Current Configuration
- Load User Context
- Create Analyze Context

                │
                ▼

[ STAGE 05 ]
ASSSession
------------------------------------------------------------
- Create Session
- Create Job ID
- Create Session ID
- Session Lifetime
- Session Status

                │
                ▼

[ STAGE 06 ]
ASSState
------------------------------------------------------------
State

Idle
↓

Preparing
↓

Running
↓

Completed

or

Error

or

Cancelled

                │
                ▼

[ STAGE 07 ]
ASSRuntime
------------------------------------------------------------
- Runtime Initialization
- Runtime Validation
- Runtime Health Check
- Runtime Capability
- Runtime Ready

                │
                ▼

[ STAGE 08 ]
ASSNative
------------------------------------------------------------
- Load Native Library
- Verify Native Library
- Bind Native Function
- Runtime API Ready

                │
                ▼

[ STAGE 09 ]
ASSInspector
------------------------------------------------------------
- Scan Folder
- Discover Audio Files
- Validate File
- Read Metadata
- Read Audio Information
- Verify Supported Format

                │
                ▼

[ STAGE 10 ]
ASSAnalyze
------------------------------------------------------------
- Decode Audio
- Extract Features
- BPM
- Key
- Genre
- Bitrate
- Codec
- Sample Rate
- Metadata
- Feature Extraction

                │
                ▼

[ STAGE 11 ]
ASSDecision
------------------------------------------------------------
- Customer Rule
- Pattern Rule
- Rename Rule
- Score
- Decision
- Recommendation

                │
                ▼

[ STAGE 12 ]
ASSPayload
------------------------------------------------------------
- Build Payload
- Serialize Data
- Payload Version
- Runtime Version
- Feature Package

                │
                ▼

[ STAGE 13 ]
ASSVerifiedPayload
------------------------------------------------------------
- Payload Validation
- Payload Integrity
- Verify Runtime
- Verify Analysis Result
- Verify Required Fields

                │
                ▼

[ STAGE 14 ]
ASSRegistry
------------------------------------------------------------
- Register Job
- Register Payload
- Register Decision
- Register Report
- Update Registry
- Registry Verification

                │
                ▼

[ STAGE 15 ]
ASSCacheFile
------------------------------------------------------------
- Cache Lookup
- Cache Validation
- Write Cache
- Read Cache

                │
                ▼

[ STAGE 16 ]
ASSReport
------------------------------------------------------------
- Generate Report
- Generate Summary
- Export Report
- Export Result

                │
                ▼

[ STAGE 17 ]
ASSLicense
------------------------------------------------------------
- Validate Trial
- Validate License
- Check Expire
- Activate License

                │
                ▼

[ STAGE 18 ]
ASSNotifiedManagement
------------------------------------------------------------
- Select Provider
- Route Notification
- Dispatch Notification

                │
      ┌─────────┼─────────┐
      ▼         ▼         ▼

Telegram     Discord     Line

                │
                ▼

[ STAGE 19 ]
ASSLogs
------------------------------------------------------------
- Runtime Log
- Analyze Log
- Error Log
- Debug Log
- Session Log

                │
                ▼

============================================================
PROCESS COMPLETED
============================================================