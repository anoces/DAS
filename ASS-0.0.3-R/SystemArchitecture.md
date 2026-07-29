


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
- ASSVerifiedPayload.py
* Boundary : Process Analyzer With Payload.
- ASSReport.py
- ASSCacheFile.py
* Boundary : Create "Write/Read" files cache.
- ASSLogs.py
* Boundary : Create "Weite/Read" files log.

# PIPELINE STAGE :
- ASSGui.py
↓
- ASSGuiWorker.py
↓
- ASSInpector.py
↓
- ASSAnalyze.py
↓
- ASSVerifiedPayload.py