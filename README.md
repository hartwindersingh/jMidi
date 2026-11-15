# jMidi 1.0.0

**A practical MIDI workspace for musicians.**

jMidi brings MIDI file editing and live MIDI connectivity into one focused Windows desktop application. Clean up performances, shape timing, work with controllers and keep an eye on the MIDI messages moving through your setup.

## MIDI In / Out monitor

The MIDI In / Out screen gives you a clear view of your connected MIDI setup:

- View available MIDI input and output devices.
- See the selected device and its connection state.
- Monitor incoming and outgoing MIDI activity as it happens.
- Track message counts and the time of the latest activity.
- Read message details in separate MIDI IN and MIDI OUT event logs.
- Check queue depth and dropped-message diagnostics when troubleshooting a setup.

## Made for everyday MIDI work

- MIDI file editing and performance cleanup
- Quantization, groove shaping and humanization
- Note and controller inspection and editing
- MIDI health checks and repair tools
- Live MIDI input and output monitoring

## Getting started

1. Install Python 3.11 or newer.
2. Create and activate a virtual environment.
3. Install the project dependencies.
4. Connect your MIDI interface or device, then launch jMidi.

```powershell
python -m venv .venv
.venv\\Scripts\\activate
python -m pip install -r requirements.txt
python main.py
```

## Your MIDI setup

Connect your MIDI keyboard, controller, synthesizer or MIDI interface before opening the device selectors. The available ports depend on the devices, drivers and MIDI software installed on your Windows computer. Select the input that sends performance data to jMidi and the output that should receive MIDI from the application.

## Development

Install development dependencies and run the test suite:

```powershell
python -m pip install -r requirements-dev.txt
python -m pytest -q
```

For a Windows application build, run `build_windows.bat` from a Windows command prompt after installing the required dependencies.

## Credits

Developed by **Hartwinder Singh**.
