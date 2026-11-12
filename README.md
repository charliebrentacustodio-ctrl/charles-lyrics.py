# 🌧️ Ako ang Bagyo | Animated Lyrics Visualizer

An animated, storm-themed lyrics visualizer for **"Ako ang Bagyo" by SHEAN**, developed using Python.

Experience the song through a dramatic visual presentation featuring rain, lightning, dark clouds, strong winds, flying debris, and synchronized lyrics.

## 🎬 Features

- 🌧️ Animated rain effects
- ⚡ Lightning and storm effects
- ☁️ Moving dark clouds
- 💨 Animated wind streaks
- 🏚️ Flying debris and yero effects
- 💔 Animated broken hearts
- 🎵 Synchronized lyrics using LRC timestamps
- 🔊 Automatic MP3 playback
- 🖥️ Full-screen visualizer
- ⌨️ ESC key to exit the visualizer
- 📁 Universal file paths for easy sharing

## 🛠️ Built With

- **Python** – Main programming language
- **Tkinter** – Graphical interface and animation window
- **Pygame** – Audio playback
- **Math** – Animation calculations
- **Random** – Randomized weather and visual effects

## 📋 Requirements

Before running the project, make sure you have:

- Python 3.10 or newer
- Pygame

Install Pygame:

```bash
pip install pygame
```

Tkinter is included with most standard Python installations.

## 📂 Project Structure

Keep all required files inside the same folder:

```text
Ako Ang Bagyo By Charles/
│
├── ako_ang_bagyo.py
├── lyrics.lrc
└── ako ang bagyo - SHEAN.mp3
```

**Important:** Make sure the filenames match the ones used in the Python script.

## 🚀 Installation and Usage

1. Download or clone this repository.

```bash
git clone https://github.com/YOUR-USERNAME/ako-ang-bagyo-lyrics-visualizer.git
```

2. Open the project folder.

3. Install the required dependency.

```bash
pip install pygame
```

4. Make sure the MP3 and LRC files are in the same folder as the Python script.

5. Run the visualizer.

```bash
python ako_ang_bagyo.py
```

6. Press **ESC** to close the visualizer.

## 🎼 Lyrics Synchronization

The visualizer uses an `.lrc` file to display lyrics at specific timestamps.

Example:

```text
[00:00.00] First line of the song
[00:05.00] Second line of the song
[00:10.00] Third line of the song
```

You can adjust the timestamps in `lyrics.lrc` to synchronize the lyrics with the audio.

## 📁 Universal File Paths

This project uses Python's `pathlib` to automatically locate files in the project directory.

```python
SCRIPT_DIR = Path(__file__).resolve().parent

LYRICS_FILE = SCRIPT_DIR / "lyrics.lrc"
AUDIO_FILE = SCRIPT_DIR / "ako ang bagyo - SHEAN.mp3"
```

This makes the project easier to move and share without changing personal computer paths.

## ⚠️ Disclaimer

This project is created for educational and entertainment purposes. The song, audio, lyrics, and other third-party content belong to their respective owners. I do not claim ownership of any third-party content.

## 👨‍💻 Developer

**Charles**

Created with Python, creativity, and passion for music and programming.

---

*Where music meets the storm.* 🌩️
