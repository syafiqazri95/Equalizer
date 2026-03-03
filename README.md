# Equalizer

## Requirements
- Python 3.9+
- pip install numpy scipy pyaudiowpatch customtkinter
- VB-Audio Virtual Cable (FREE) → https://vb-audio.com/Cable/

## Setup
1. Install VB-Cable → Restart PC
2. Set "CABLE Input" as Windows Default Playback Device
3. Run EQ Pro:
   - Capture  → "CABLE Output [Loopback]"
   - Output   → Your real Speakers or Headphones
4. Done ✅

## Why VB-Cable is Required
This app uses WASAPI loopback to capture system audio.
Without a virtual cable, capture and output share the
same physical device → feedback loop (loud pinging).
VB-Cable creates a virtual separation between them.
