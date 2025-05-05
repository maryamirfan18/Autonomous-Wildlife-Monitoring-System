# Animal Sound Detection

This demonstrates how to classify animal sounds based on extracted features from audio files, such as RMS energy, zero crossing rate, spectral centroid, and more. The classification helps to identify different animal sounds, with a particular focus on distinguishing "angry" sounds.

## Requirements

- Python 3
- pydub
- ffmpeg
- NumPy
- SciPy
- Matplotlib

To install required libraries, you can use the following commands:

```bash
!pip install pydub
!apt-get install ffmpeg -y
```

## 📁 Files

- `animal_sound_detection.ipynb` — Jupyter notebook with sound classification code
- `lion.wav`, `wolf.wav`, `cat3.wav` — Sample animal audio files
- `extracted_features.png` — Visualization of extracted features (generated after running the notebook)

---
# 🚀 Animal Sound Analysis

## Setup & Usage

### 1. Install Dependencies
Ensure all required Python packages and `ffmpeg` are installed.

### 2. Upload Audio Files
Place your animal audio files (e.g., `lion.wav`, `wolf.wav`) in the working directory.

---
##  How It Works

### 📊 Feature Extraction
The `extract_features()` function extracts key audio features:
- **RMS Energy**
- **Zero Crossing Rate**
- **Spectral Centroid**
- **Spectral Bandwidth**
- **Spectral Rolloff**
- **Fundamental Frequency** (currently a placeholder)

### Sound Classification
The `classify_sound()` function classifies a sound as **"Angry"** or **"Neutral"** based on thresholds for features like:
- High RMS energy
- Sudden changes in audio (zero crossings)
- High-frequency emphasis

### 📈 Visualization
The `visualize_audio()` function plots:
- **Raw waveform**
- **Frequency spectrum** (via Fourier Transform)

---

## 📝 Notes
- You can replace the sample audio files with your own (`.wav` format recommended).
- Thresholds in `classify_sound()` are basic and may require tuning for more accurate results.
- The `fundamental_frequency` feature is a placeholder — you can implement it for improved classification accuracy.

---

## 📸 Example Output
After running the notebook, an image like below will be generated:

- **`extracted_features.png`** — shows the waveform and frequency spectrum of an analyzed sound.

---

---

### Additional Notes
- The classifier uses basic thresholds to classify the sound as "Angry" based on RMS energy, spectral centroid, and other features. You can modify these thresholds as needed.
- The `fundamental_frequency` feature is currently a placeholder and would need an actual implementation for more accurate classification.
