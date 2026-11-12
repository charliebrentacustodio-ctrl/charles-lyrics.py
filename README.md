## ⚙️ Setup and Installation Guide

Follow these steps to set up and run the project on your computer.

### 1. Install Python

Download and install Python from the official website:

https://www.python.org/downloads/

Make sure to check **"Add Python to PATH"** during installation.

### 2. Clone the Repository

Open your terminal or Command Prompt and run:

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
```

Alternatively, click **Code → Download ZIP** on GitHub and extract the downloaded folder.

### 3. Choose a Branch

If you want to use a specific visualizer version, switch to its branch:

```bash
git branch -a
```

To switch branches:

```bash
git switch branch-name
```

Replace `branch-name` with your chosen branch.

### 4. Install Dependencies

Open the project folder in your terminal and install Pygame:

```bash
pip install pygame
```

### 5. Check Your Project Files

Make sure the required files for your selected branch are present, including:

- Python source files (`.py`)
- Audio file (`.mp3`)
- Lyrics file (`.lrc`)
- Additional assets, if required

Keep files in the expected folder locations.

### 6. Run the Program

Execute the main Python script:

```bash
python main.py
```

The actual filename may vary depending on the selected branch.

### 7. Enjoy the Visualizer!

The visualizer should open and start playing the audio with synchronized lyrics and animations.

Use the keyboard controls provided by your selected version to interact with or exit the program.

---

## 📝 Troubleshooting

**Pygame is not installed**

```bash
pip install pygame
```

**Python is not recognized**

Make sure Python is installed and added to your system PATH.

**Audio file not found**

Check that the MP3 filename and file location match the paths defined in the script.

**Lyrics are not displaying**

Make sure the `.lrc` file exists and follows the correct timestamp format.

**Wrong visualizer version**

Check your current Git branch:

```bash
git branch
```

Switch to the desired branch using `git switch branch-name`.
