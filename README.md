# jMidi 1.0.0

A Windows desktop MIDI studio for musicians who want practical tools for live MIDI routing, MIDI file editing, timing, arrangement, accompaniment and performance cleanup.

## MIDI In / Out monitor
The 1.0.0 source includes a dedicated MIDI In / Out screen with:
- Selected input and output port names and connection state
- Live received and successfully transmitted message counts
- Last-message timestamps and MIDI message summaries
- Separate MIDI IN and MIDI OUT event logs
- Input/output queue depth and dropped-event diagnostics

## Project
- Python 3.11+
- PySide6 desktop interface
- Mido / python-rtmidi for MIDI device access
- pytest for automated tests

## Run from source
```powershell
python -m venv .venv
.venv\\Scripts\\activate
python -m pip install -r requirements.txt
python main.py
```

## Test
```powershell
python -m pip install -r requirements-dev.txt
python -m pytest -q
```

## Windows build
Run `build_windows.bat` on Windows after installing dependencies.

## Validation status
Local automated tests: 67 passed. Python compilation and source archive integrity checks passed. PySide6 GUI runtime, Windows executable build and physical MIDI hardware acceptance have not been verified in the current Linux environment.

## Credits
Developed by Hartwinder Singh.
