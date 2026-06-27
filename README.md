# VoiceRecorder

A simple Python application that records audio from a microphone and saves it as WAV files.

## Features

* Record audio from your default microphone
* Configure recording duration
* Adjustable sampling frequency
* Save recordings as WAV files using:

  * `scipy.io.wavfile`
  * `wavio`

## Technologies Used

* Python 3.14
* NumPy
* SoundDevice
* SciPy
* Wavio

## Installation

1. Clone the repository:

```bash
git clone https://github.com/RosariaBowes/VoiceRecorder.git
cd VoiceRecorder
```

2. Create a virtual environment:

```bash
python -m venv myenv
```

3. Activate the virtual environment.

**Windows**

```bash
myenv\Scripts\activate
```

4. Install the required packages:

```bash
pip install sounddevice scipy wavio
```

## Usage

Run the program:

```bash
python VoiceRecorder.py
```

The application records audio for the specified duration and saves two WAV files:

* `recording0.wav` (created using SciPy)
* `recording1.wav` (created using Wavio)

## Project Structure

VoiceRecorder/
│── VoiceRecorder.py
│── README.md
│── .gitignore
└── myenv/ (not tracked by Git)

## Future Improvements

* Graphical user interface (GUI)
* Adjustable recording duration
* Device selection
* Audio playback
* MP3 export
* Pause and resume recording
* Recording level meter

## Author

Rosaria Bowes

