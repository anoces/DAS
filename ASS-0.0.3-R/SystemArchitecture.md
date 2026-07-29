


# TARGET :
- Change Files name.

# ENCRYPTION :
* Encryption any files for protection Edited File.
* Extensions: .pyd, .dll, .sig, ...
* All Source code be done any files include encryption.

# BUILD AND INSTALLER [ EXE ].
- Used NSIS And NUNIKA.

# VENDOR [ LIBRARY ].
* Source code downloading library github and build
to DLL Native to another folder.
- Ffmpeg
- Essentia
- Taglib
- Eigen
- Fftw3

# INPUT :
- Audio Sound.

# OUTPUT :
- Change files name.

# ANALYZE INCLUDE :
- BPM, KEY, GENRE, BITRATE, SAMPLE RATE, CODEC, ...

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

# FILES :
- ASSGui.py
* Boundary : Gui appear Interface Input for user.
- ASSGuiWorker.py
- ASSInspector.py
* Boundary : Inspector data, Metadata, ...
- ASSAnalyze.py
* Boundary : Orchestrated Analyze Only.
- ASSPayload.py
* Boundary: Cearte "Write/Read" Paylode.
- ASSVerifiedPayload.py
* Boundary : Process Analyzer With Payload.
- ASSCacheFile.py
- ASSReport.py
* Boundary : Create "Write/Read" files cache.
- ASSLogs.py
* Boundary : Create "Write/Read" files log.

# PIPELINE STAGE :
- ASSGui.py
- ↓
- ASSGuiWorker.py
- ↓
- ASSInspector.py
- ↓
- ASSAnalyze.py
- ↓
- ASSPayload.py
- ↓
- ASSVerifiedPayload.py
- ↓
- ASSCacheFile.py
- ↓
- ASSReport.py