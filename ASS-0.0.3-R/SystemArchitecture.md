


# TARGET :
- Change Files name with Pattern Customer.
- Example : "161 - 9A - ..." or " 61 - 6B ".

# ENCRYPTION :
* Encryption any files for protection Edited File.
* Extensions: .pyd, .dll, .sig, ...
* All Source code be done any files include encryption.

# BUILD AND INSTALLER [ EXE ].
- Used NSIS And NUNIKA.
- Software or System used free 3 Day.
- License Key : Activate Full License.

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

# INPUT :
- Audio Sound.

# OUTPUT :
- Change files name.

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
* PATH : ASS-0.0.3-R
1.- ASSConfigRegistry.json

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

3. ASSGuiWorker.py
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

6. ASSRuntime.py
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

7. ASSPayload.py
- - -
PURPOSE
- Create Analysis Payload
- Read / Write Payload
- Serialize Analysis Data
- Exchange Data Between Modules
BOUNDARY
- Payload Only
- No Analysis

8. ASSVerifiedPayload.py
- - -
PURPOSE
- Validate Payload
- Process Verified Analysis Data
- Ensure Payload Integrity
BOUNDARY
- Verified Payload Processing
- Validation Layer

9. ASSCacheFile.py
- - -
PURPOSE
- Cache Manager
- Read Cache
- Write Cache
- Cache Validation
BOUNDARY
- Cache Only
- No Analysis Logic

10. ASSReport.py
- - -
PURPOSE
- Generate Analysis Report
- Export Result
- Read / Write Report Files
BOUNDARY
- Report Generation
- File Output

11. ASSLogs.py
- - -
PURPOSE
- Logging System
- Read / Write Log Files
- Error Logging
- Debug Logging
BOUNDARY
- Logging Only
- No Business Logic



# PIPELINE STAGE :
- ASSApplication
- ↓
- ASSGui
- ↓
- ASSGuiWorker
- ↓
- ASSRuntime
- ↓
- ASSInspector
- ↓
- ASSAnalyze
- ↓
- ASSPayload
- ↓
- ASSVerifiedPayload
- ↓
- ASSCacheFile
- ↓
- ASSReport
- ↓
- ASSLogs
