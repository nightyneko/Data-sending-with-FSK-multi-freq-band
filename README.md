# Data Sending with FSK (Multi-Frequency Bands)

Send short data payloads over audio (or RF/IF) using **Frequency-Shift Keying** with **multiple carrier bands**.  
This repo provides Jupyter notebooks to **generate**, **modulate**, **save/play**, and **analyze/demodulate** FSK signals across several frequency bands for better robustness and throughput.

> Files: `main.ipynb`, `signal_generator.ipynb`, `test.ipynb`  
> Language: Jupyter Notebook  
> Quick start: open **`main.ipynb`** and run all cells.

---

## ✨ Features

- **Multi-band FSK**: choose multiple carrier frequencies and map bits/bytes to symbols per band.
- **Flexible symbol design**: set sample rate, symbol rate, mark/space deviation, and pulse shaping.
- **Wave export / playback**: save to WAV/NumPy; optionally loop back via sound card.
- **Spectral analysis**: spectrograms/PSDs to inspect band occupancy and SNR.
- **Simple decoders**: bandpass+envelope or Goertzel-style detectors to recover symbols.

