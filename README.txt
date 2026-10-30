PULSE 16 — iPad Groovebox
========================

WHAT'S INCLUDED
- 16 independent parts/tracks
- Up to 64 steps per part, shown as four switchable 16-step pages
- Four pattern slots (A1–A4)
- Tempo and swing controls
- Synth sound design: waveform, pitch, filter cutoff/resonance and level
- Envelope controls: attack, decay, sustain, release, gate, pan and velocity
- Per-part reverb and delay sends
- Audio sample import into the selected part (up to 30 MB per file)
- 16 live trigger pads; synth parts play a C-minor note layout
- Independent last-step length for each part
- Autosave in IndexedDB on the current device
- Project import/export (.pulse16, including uploaded samples)
- Four-bar WAV render export (includes supported imported sample formats)
- Installable offline PWA shell

RUN LOCALLY
1. Unzip this folder onto a computer.
2. Start a local web server in this folder, for example:
   python3 -m http.server 8000
3. Open http://localhost:8000 in a modern browser.

INSTALL ON IPAD (RECOMMENDED)
1. Put the contents of this folder on any HTTPS static host (for example GitHub Pages).
2. Open the HTTPS address in Safari on the iPad.
3. Tap Share → Add to Home Screen.
4. Launch PULSE 16 from the Home Screen. Tap Play once to start/unlock the audio engine.

NOTES
- This is a browser-based app/PWA, not a native App Store download.
- No account or backend is required. Projects and samples are stored locally in the browser unless exported.
- The browser must support Web Audio API, IndexedDB and AudioContext.decodeAudioData.
- Some audio formats may not be decodable in Safari; WAV, MP3 and AAC/M4A are generally the safest choices.
- The project is an original groovebox inspired by hardware step-sequencer workflows, not a Korg product or an exact reproduction.
