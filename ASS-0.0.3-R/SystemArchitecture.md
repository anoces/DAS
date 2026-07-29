


# TARGET :
- Change Files name.
- Encryption any files for protection Edited File.

# INPUT :
- Audio Sound.

# OUTPUT :
- Change files name.

# ANALYZE INCLUDE :
- BPM, KEY, GENRE, BITRATE, SAMPLE RATE, CODEC

# FILES :
- ASSGui.py
* Boundary : Gui appear Interface Input for user.
- ASSGuiWorker.py
- ASSInspector.py
* Boundary : Inspector data, Metadata, ...
- ASSAnalyze.py
* Boundary : Orchestrated Analyze Only.
- ASSPayload.py
- ASSVerifiedPayload.py
* Boundary : Process Analyzer With Payload.
- ASSCacheFile.py
- ASSReport.py
* Boundary : Create "Write/Read" files cache.
- ASSLogs.py
* Boundary : Create "Weite/Read" files log.

# PIPELINE STAGE :
- ASSGui.py
- ↓
- ASSGuiWorker.py
- ↓
- ASSInpector.py
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