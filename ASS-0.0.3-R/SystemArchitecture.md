


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
- - -
PURPOSE :
- Provider And Owner Line.
- Notifed "Line".
- Notified only per one day, Set Schedules time 00:00.
BOUNDARY :
- This group only Developer and Administrator.
- Notified Sumary for log and anything per one day.
- On Operating System Opening Service Automatically.

26.- ASSMetadata.py
- - -
PURPOSE :
- Read embedded metadata.
- Normalize metadata fields.
- Complete missing metadata.
- Merge metadata with analysis results.
- Write approved metadata back to audio files.

BOUNDARY :
- Metadata read/write only.
- No audio analysis.
- No GUI.
- No direct Registry file access.
- All persistence must pass ASSRegistry.py.

27.- ASSFileManager.py
- - -
PURPOSE :
- Manage physical file operations.
- Generate final destination paths.
- Rename audio files.
- Copy or move processed files.
- Detect duplicate file names.
- Prevent file overwrite.
- Perform atomic file operations.
- Roll back failed operations.
- Verify output file after operation.
BOUNDARY :
- File operations only.
- No audio analysis.
- No scoring or decision logic.
- No GUI.
- No direct Registry JSON access.
- Must use approved data from ASSVerifiedPayload.py.
- Must register final results through ASSRegistry.py.


28.- ASSNotificationProvider.py
- - -
PURPOSE :
- Define the standard notification provider contract.
- Provide a common interface for all notification services.
- Standardize message, progress, warning, error, and health-check operations.
- Allow ASSNotifiedManagement.py to use any provider without knowing provider-specific implementation.
- Support future providers such as Telegram, Discord, LINE, Email, Slack, or Microsoft Teams.
BOUNDARY :
- Provider interface and contract only.
- No direct notification delivery.
- No provider-specific API logic.
- No direct Registry JSON access.
- No GUI.
- No audio analysis.
- No business decision logic.
- Must not store API keys, tokens, or webhooks directly.
- Credentials must be provided through ASSConfig.py or secure environment configuration.
- Provider implementations must handle their own authentication, request formatting, and transport errors.
- Notification failure must not stop the main analysis process.

29.- ASSRuntimeCapability.py
- - -
PURPOSE :
- Define and report available runtime capabilities.
- Detect which Native libraries and Python modules are installed and ready.
- Record supported features provided by each Runtime component.
- Expose capability information to ASSRuntime.py, ASSAnalyze.py, and ASSApplication.py.
- Allow the system to enable, disable, or fall back from unavailable features.
- Provide a unified capability map for FFmpeg, AudioFlux, Essentia, ONNX Runtime, TagLib, libebur128, and other Runtime libraries.
- Report Runtime version, architecture, linkage type, and health status.
- Support capability checks before starting an analysis job.
BOUNDARY :
- Capability detection and reporting only.
- No direct audio analysis.
- No GUI rendering.
- No file rename, copy, or move operations.
- No direct Registry JSON access.
- No Native function binding; ASSNative.py owns DLL loading and function binding.
- No Runtime lifecycle management; ASSRuntime.py owns initialization and shutdown.
- No business decision or scoring logic.
- Must not assume a capability is available without verification.
- Must return explicit status such as Available, Unavailable, Degraded, or Unsupported.
- Must provide failure reasons and optional fallback capability.

30.- ASSTypes.py
- - -
PURPOSE :
- Define shared data types used across the ASS system.
- Provide common TypedDict, Dataclass, Enum, Protocol, and Type Alias definitions.
- Standardize data exchanged between Application, Runtime, Inspector, Analyze, Decision, Payload, Registry, Cache, Report, and Notification modules.
- Reduce duplicated type definitions across multiple files.
- Improve static type checking, IDE support, code completion, and refactoring safety.
- Define stable contracts for analysis results, metadata, file information, runtime status, session data, registry entries, and notification messages.
- Support schema versioning by separating data structure definitions from implementation logic.
BOUNDARY :
- Type definitions only.
- No business logic.
- No audio analysis.
- No file I/O.
- No Registry read or write.
- No Runtime initialization.
- No Native library loading.
- No GUI rendering.
- No network requests.
- No logging side effects.
- Must not mutate application state.
- Must not contain provider-specific implementation.
- Types must remain dependency-light and reusable by all modules.
- Runtime imports should be limited to Python standard-library typing, dataclasses, enum, pathlib, and datetime where required.

31.- ASSPayloadSchema.py
- - -
PURPOSE :
- Define the canonical payload structure.
- Define required and optional payload fields.
- Define field names, data types, default values, and validation rules.
- Define payload schema version.
- Standardize data exchanged between ASSAnalyze.py, ASSDecision.py,
  ASSMetadata.py, ASSPayload.py, ASSVerifiedPayload.py, ASSCacheFile.py,
  ASSRegistry.py, and ASSReport.py.
- Support backward compatibility and schema migration.
- Prevent inconsistent payload formats across modules.
BOUNDARY :
- Payload schema and validation rules only.
- No payload file read or write.
- No audio analysis.
- No business decision logic.
- No Registry access.
- No Cache access.
- No GUI.
- No Native Runtime loading.
- Must not modify source audio files.
- Must remain independent from provider-specific implementation.

32.- ASSDecisionSchema.py
- - -
PURPOSE :
- Define the canonical decision result structure.
- Define required and optional decision fields.
- Define score names, score ranges, confidence values, warnings, reasons,
  recommendations, and final decision status.
- Standardize decision data exchanged between ASSDecision.py,
  ASSPayload.py, ASSVerifiedPayload.py, ASSRegistry.py,
  ASSReport.py, and Project 2 modules.
- Define decision schema version.
- Support customer-specific scoring rules without changing the data contract.
- Support future migration when decision fields or scoring models change.
BOUNDARY :
- Decision schema and validation rules only.
- No score calculation.
- No recommendation generation.
- No audio analysis.
- No Registry read or write.
- No Payload serialization.
- No GUI.
- No Native Runtime loading.
- No customer rule execution.
- Must not modify application state.
- Must remain independent from a specific analyzer or notification provider.

33.- ASSCacheFile.py
- - -
PURPOSE :
- Manage analysis cache.
- Read cache data.
- Write cache data.
- Validate cache integrity.
- Detect cache hit or cache miss.
- Verify cache compatibility.
- Compare file fingerprint.
- Compare Runtime version.
- Compare Payload version.
- Compare Decision version.
- Manage cache lifetime.
- Remove invalid cache.
- Support incremental analysis.
BOUNDARY :
- Cache management only.
- No audio analysis.
- No business decision logic.
- No GUI.
- No Native Runtime loading.
- No direct Registry JSON access.
- Must use ASSRegistry.py for cache registration.
- Must use ASSPayloadSchema.py for payload validation.
- Cache format should support Parquet.
- Cache must be immutable after validation.

# PIPELINE STAGE :
============================================================
PIPELINE STAGE
============================================================

[ STAGE 01 ]
ASSApplication
------------------------------------------------------------
- Application Entry Point.
- Initialize System.
- Initialize ASSVersion.
- Initialize ASSException Handling.
- Initialize ASSConfig.
- Initialize ASSRegistry.
- Initialize ASSLicense.
- Initialize ASSContext.
- Initialize ASSSession.
- Initialize ASSState.
- Initialize ASSRuntime.
- Initialize Notification Provider Management.
- Launch GUI.

                │
                ▼

[ STAGE 02 ]
ASSConfig
------------------------------------------------------------
- Load Application Configuration.
- Load Environment Variables.
- Load Runtime Path.
- Load Registry Path.
- Load Payload Path.
- Load Cache Path.
- Load Logs Path.
- Load Output Path.
- Load Notification Configuration.
- Load License Configuration.
- Validate Required Configuration.

                │
                ▼

[ STAGE 03 ]
ASSRegistry
------------------------------------------------------------
- Initialize Registry Gateway.
- Verify Registry Files.
- Load Registry Index.
- Load Payload Registry.
- Load Decision Registry.
- Load License Registry.
- Verify Registry Schema Version.
- Registry is the Single Source of Truth.
- No Module Accesses Registry JSON Directly.

                │
                ▼

[ STAGE 04 ]
ASSLicense
------------------------------------------------------------
- Validate Trial License.
- Validate Full License.
- Check Expiration Date.
- Verify Activation Hash Key.
- Verify License Registry.
- Allow Full Mode, Trial Mode, or Restricted Mode.
- Reject Analyze Job When License Permission Is Invalid.

                │
                ▼

[ STAGE 05 ]
ASSContext
------------------------------------------------------------
- Create Global Application Context.
- Load Current Configuration.
- Load Current User Context.
- Load Runtime Context.
- Load Registry Context.
- Load Notification Context.
- Provide Shared Read-Only Context to System Modules.

                │
                ▼

[ STAGE 06 ]
ASSSession
------------------------------------------------------------
- Create Application Session.
- Create Session ID.
- Create Job ID.
- Record Session Start Time.
- Record Current User.
- Record Source Path.
- Record Destination Path.
- Record Current Analyze Profile.
- Track Current File.
- Track Current Payload.
- Track Current Report.
- Track Session Lifetime.

                │
                ▼

[ STAGE 07 ]
ASSState
------------------------------------------------------------
STATE FLOW :

Idle
  ↓
Preparing
  ↓
Ready
  ↓
Running
  ↓
Pausing / Paused
  ↓
Resuming
  ↓
Completed

ALTERNATIVE STATE :

Running
  ├── Cancel Requested
  │       ↓
  │   Cancelled
  │
  └── Error
          ↓
      Failed

- Control Application State.
- Control Job State.
- Prevent Invalid State Transitions.
- Notify GUI When State Changes.

                │
                ▼

[ STAGE 08 ]
ASSRuntime
------------------------------------------------------------
- Initialize Runtime Environment.
- Verify Runtime Folder.
- Verify Runtime Architecture.
- Verify Runtime Version.
- Verify Runtime Dependencies.
- Perform Runtime Health Check.
- Initialize Runtime Services.
- Manage Runtime Lifecycle.
- Prepare Runtime for Native Loading.

                │
                ▼

[ STAGE 09 ]
ASSNative
------------------------------------------------------------
- Discover Native Libraries from "\Runtime\...".
- Load Native DLL or PYD Files.
- Verify Native File Integrity.
- Bind Native Functions.
- Validate Native ABI Compatibility.
- Register Native Handles.
- Prepare Native API for Runtime Services.
- Unload Native Libraries During Shutdown.

                │
                ▼

[ STAGE 10 ]
ASSRuntimeCapability
------------------------------------------------------------
- Detect Available Runtime Capabilities.
- Detect Available Python Modules.
- Detect Available Native Libraries.
- Detect Supported Audio Formats.
- Detect Supported Codec Operations.
- Detect Available Analyzer Features.
- Detect Available Metadata Features.
- Detect ONNX Runtime Providers.
- Detect CPU or Optional Hardware Capability.
- Return Capability Status :

  Available
  Unavailable
  Degraded
  Unsupported

- Provide Fallback Information.
- Prevent Analyze Job When Required Capability Is Missing.

                │
                ▼

[ STAGE 11 ]
ASSNotifiedManagement
------------------------------------------------------------
- Initialize Notification Management.
- Load Enabled Notification Providers.
- Validate Provider Configuration.
- Register Telegram Provider.
- Register Discord Provider.
- Register LINE Provider.
- Disable Invalid or Unavailable Providers.
- Notification Failure Must Not Stop Main Processing.

                │
                ▼

[ STAGE 12 ]
ASSGui
------------------------------------------------------------
- Launch Main User Interface.
- Display Application Status.
- Display Runtime Capability.
- Display License Status.
- Drag and Drop Source Folder.
- Select Source Folder.
- Select Output Folder.
- Select Rename Pattern.
- Display Supported Audio Formats.
- Display Queue.
- Display Progress.
- Display Analysis Result.
- Send User Request to ASSGuiWorker.

                │
                ▼

[ STAGE 13 ]
ASSGuiWorker
------------------------------------------------------------
- Receive Analyze Request from GUI.
- Revalidate Current State.
- Revalidate License Permission.
- Create Analyze Job.
- Run Job Outside GUI Thread.
- Support Background Thread or Process.
- Send Progress Callback.
- Support Pause.
- Support Resume.
- Support Cancel.
- Forward Controlled Exceptions.
- Update ASSSession.
- Update ASSState.

                │
                ▼

[ STAGE 14 ]
ASSInspector
------------------------------------------------------------
- Scan Source Folder.
- Discover Supported Audio Files.
- Reject Unsupported Files.
- Validate File Path.
- Validate File Extension.
- Validate File Read Permission.
- Validate File Size.
- Detect Corrupted or Unreadable Files.
- Read Container Information.
- Read Codec Information.
- Read Bitrate.
- Read Sample Rate.
- Read Bit Depth.
- Read Channels.
- Read Channel Layout.
- Read Duration.
- Read Embedded Metadata.
- Generate Inspection Result.

                │
                ▼

[ STAGE 15 ]
FILE FINGERPRINT
------------------------------------------------------------
- Generate File Fingerprint.
- Use File Path Information.
- Use File Size.
- Use Modified Time.
- Use XXHash or Approved Hash Method.
- Record Application Version.
- Record Runtime Version.
- Record Payload Schema Version.
- Record Decision Schema Version.
- Use Fingerprint for Cache Lookup and Registry Identity.

                │
                ▼

[ STAGE 16 ]
ASSCacheFile : LOOKUP
------------------------------------------------------------
- Search Existing Cache Entry.
- Verify File Fingerprint.
- Verify Cache Integrity.
- Verify Runtime Version.
- Verify Payload Version.
- Verify Decision Version.
- Verify Analyzer Profile.
- Detect Cache Hit or Cache Miss.

                │
        ┌───────┴────────┐
        ▼                ▼

   CACHE HIT         CACHE MISS
        │                │
        │                ▼
        │          [ STAGE 17 ]
        │          ASSAnalyze
        │          ----------------------------------------
        │          - Decode Audio.
        │          - Normalize Audio Buffer.
        │          - Extract Audio Features.
        │          - Analyze BPM.
        │          - Analyze Key.
        │          - Analyze Genre Estimation.
        │          - Analyze Rhythm.
        │          - Analyze Energy.
        │          - Analyze Loudness.
        │          - Analyze Spectral Features.
        │          - Analyze Harmonic Features.
        │          - Analyze Onset and Beat Information.
        │          - Collect Confidence Values.
        │          - Coordinate Runtime Analyzer Modules.
        │          - Generate Analysis Result.
        │
        │                │
        │                ▼
        │
        │          [ STAGE 18 ]
        │          ASSMetadata
        │          ----------------------------------------
        │          - Read Embedded Metadata.
        │          - Normalize Metadata Fields.
        │          - Complete Missing Metadata.
        │          - Merge Metadata with Analysis Result.
        │          - Validate Metadata Values.
        │          - Prepare Approved Metadata Changes.
        │          - Do Not Write Metadata Before Approval.
        │
        │                │
        │                ▼
        │
        │          [ STAGE 19 ]
        │          ASSDecision
        │          ----------------------------------------
        │          - Load Customer Requirements.
        │          - Apply Rename Pattern Rule.
        │          - Apply Metadata Decision Rule.
        │          - Evaluate Analysis Result.
        │          - Evaluate Confidence.
        │          - Evaluate Required Fields.
        │          - Generate Score.
        │          - Generate Recommendation.
        │          - Generate Warning.
        │          - Generate Final Decision.
        │          - Use ASSDecisionSchema Contract.
        │
        │                │
        │                ▼
        │
        │          [ STAGE 20 ]
        │          ASSPayload
        │          ----------------------------------------
        │          - Build Canonical Payload.
        │          - Use ASSPayloadSchema.
        │          - Include Payload ID.
        │          - Include Session ID.
        │          - Include Job ID.
        │          - Include File Fingerprint.
        │          - Include Inspection Result.
        │          - Include Analysis Result.
        │          - Include Metadata Result.
        │          - Include Decision Result.
        │          - Include Runtime Version.
        │          - Include Application Version.
        │          - Include Created Time.
        │          - Serialize Payload.
        │          - Prepare Parquet Payload File.
        │
        │                │
        │                ▼
        │
        │          [ STAGE 21 ]
        │          ASSVerifiedPayload
        │          ----------------------------------------
        │          - Validate Payload Schema.
        │          - Validate Required Fields.
        │          - Validate Data Types.
        │          - Validate Value Ranges.
        │          - Validate Payload Integrity.
        │          - Validate File Fingerprint.
        │          - Validate Runtime Compatibility.
        │          - Validate Decision Result.
        │          - Validate Metadata Changes.
        │          - Reject Invalid Payload.
        │          - Produce Verified Payload.
        │
        │                │
        │                ▼
        │
        │          [ STAGE 22 ]
        │          ASSCacheFile : WRITE
        │          ----------------------------------------
        │          - Write Verified Payload to Cache.
        │          - Write Cache as Parquet.
        │          - Register Cache Version.
        │          - Register File Fingerprint.
        │          - Register Runtime Version.
        │          - Register Payload Version.
        │          - Perform Atomic Cache Write.
        │          - Prevent Partial Cache Files.
        │          - Mark Cache Immutable After Validation.
        │
        └────────────────┘
                │
                ▼

[ STAGE 23 ]
VERIFIED PAYLOAD READY
------------------------------------------------------------
- Use Cached Verified Payload
  or
- Use Newly Generated Verified Payload.
- Confirm Payload Is Approved for File Operation.

                │
                ▼

[ STAGE 24 ]
ASSFileManager
------------------------------------------------------------
- Read Approved Rename Decision.
- Generate Destination File Name.
- Apply Customer Rename Pattern.
- Generate Destination Path.
- Detect Duplicate File Name.
- Prevent Existing File Overwrite.
- Generate Safe Alternative Name When Required.
- Prepare Atomic Rename, Copy, or Move Operation.
- Execute File Operation.
- Verify Destination File.
- Preserve Original File Until Verification Is Complete.
- Roll Back Operation When Verification Fails.
- Return File Operation Result.

                │
                ▼

[ STAGE 25 ]
ASSMetadata : WRITE APPROVED METADATA
------------------------------------------------------------
- Apply Approved Metadata Changes.
- Write BPM When Allowed.
- Write Key or Camelot Key When Allowed.
- Write Genre When Approved.
- Write Additional ASS Metadata When Allowed.
- Preserve Original Metadata When Required.
- Verify Metadata After Write.
- Roll Back or Report Failure When Metadata Write Is Invalid.

                │
                ▼

[ STAGE 26 ]
ASSRegistry : COMMIT
------------------------------------------------------------
- Register Job.
- Register Session.
- Register Source File.
- Register Destination File.
- Register File Fingerprint.
- Register Payload.
- Register Decision.
- Register Cache.
- Register Metadata Result.
- Register File Operation Result.
- Register Report Reference.
- Update Registry State.
- Verify Registry Consistency.
- Perform Atomic Registry Update.
- Prevent Direct JSON Access from Other Modules.

                │
                ▼

[ STAGE 27 ]
ASSReport
------------------------------------------------------------
- Generate Analysis Report.
- Generate Processing Summary.
- Generate Rename Result.
- Generate Metadata Result.
- Generate Cache Result.
- Generate Warning Summary.
- Generate Error Summary.
- Generate Human-Readable Report.
- Generate Machine-Readable Report.
- Export JSON, CSV, XML, TXT, or Parquet When Required.
- Register Report through ASSRegistry.

                │
                ▼

[ STAGE 28 ]
ASSNotifiedManagement : OPTIONAL
------------------------------------------------------------
- Select Enabled Provider.
- Route Notification.
- Dispatch Completion Message.
- Dispatch Progress Message.
- Dispatch Warning Message.
- Dispatch Error Message.
- Dispatch Daily Summary When Scheduled.
- Notification Failure Is Non-Blocking.

                │
      ┌─────────┼─────────┐
      ▼         ▼         ▼

ASSNotifiedTelegram
- Telegram Bot Provider.
- Development and Administrator Notification.
- Customer Notification When Enabled.

ASSNotifiedDiscord
- Discord Webhook Provider.
- Development and Administrator Environment Notification.

ASSNotifiedLine
- LINE Provider.
- Scheduled Daily Summary.
- Development and Administrator Notification.

                │
                ▼

[ STAGE 29 ]
ASSLogs
------------------------------------------------------------
- Write Application Log.
- Write Runtime Log.
- Write Native Library Log.
- Write Inspector Log.
- Write Analyze Log.
- Write Metadata Log.
- Write Decision Log.
- Write Payload Log.
- Write Cache Log.
- Write Registry Log.
- Write File Operation Log.
- Write Report Log.
- Write Notification Log.
- Write Warning Log.
- Write Error Log.
- Write Debug Log.
- Write Session Log.
- Remove or Mask Secrets.
- Flush Log Buffer.

NOTE :
- ASSLogs Is Available to Every Stage.
- Logging Is Not Only the Final Stage.
- "\Logs\..." Is Used for Log Files Only.

                │
                ▼

[ STAGE 30 ]
FINALIZE SESSION
------------------------------------------------------------
- Update Final Job State.
- Update Final Session State.
- Record Completed Time.
- Record Failed Time When Required.
- Record Cancelled Time When Required.
- Release Temporary Resources.
- Close File Handles.
- Close Payload Handles.
- Flush Registry.
- Flush Cache.
- Flush Reports.
- Flush Logs.

                │
                ▼

[ STAGE 31 ]
ASSState : FINAL
------------------------------------------------------------
- Completed
or
- Failed
or
- Cancelled

                │
                ▼

[ STAGE 32 ]
ASSRuntime : SHUTDOWN
------------------------------------------------------------
- Release Runtime Services.
- Unload Native Libraries.
- Release Native Handles.
- Stop Background Workers.
- Stop Notification Workers.
- Verify Clean Shutdown.
- Return System to Idle State.

                │
                ▼

============================================================
PROCESS COMPLETED
============================================================

# FAILURE AND ROLLBACK FLOW :
============================================================

ANY STAGE ERROR
        │
        ▼
ASSException
------------------------------------------------------------
- Normalize Exception.
- Add Error Code.
- Add Stage Name.
- Add Session ID.
- Add Job ID.
- Remove Sensitive Data.

        │
        ▼
ASSLogs
------------------------------------------------------------
- Write Error Log.
- Write Debug Context.
- Flush Log.

        │
        ▼
ASSFileManager
------------------------------------------------------------
- Roll Back Incomplete File Operation When Required.
- Restore Original File When Possible.

        │
        ▼
ASSRegistry
------------------------------------------------------------
- Register Failure State.
- Register Error Reference.
- Preserve Previous Valid Registry State.

        │
        ▼
ASSNotifiedManagement : OPTIONAL
------------------------------------------------------------
- Send Failure Notification.
- Notification Failure Must Not Replace Original Error.

        │
        ▼
ASSState
------------------------------------------------------------
- Set Failed or Cancelled State.

        │
        ▼
FINALIZE SESSION
============================================================
