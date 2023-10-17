# Gesture Control Apple TV 🍎📺

## Overview
This project lets you control your Apple TV with simple hand gestures. Designed to be intuitive and user-friendly, it walks you through the implementation steps using a detailed Jupyter Notebook guide.

## 📽️ Video Demonstration
For a quick glimpse of what this project can do, check out the [video demo](https://github.com/zijie-cai/Gesture-Control-Apple-TV/assets/74931355/aed56bc2-e850-4b5f-af31-afad62d0eff9).

## 📚 Technologies Used
- Python
- OpenCV
- mediapipe
- pyatv
- WebCam
- Apple TV

## 🛠 Installation and Setup
### 1. Set Up Environment and Install Dependencies
- Create and activate a Python virtual environment (venv/conda):
    ```bash
    python3 -m venv env 
    source env/bin/activate # Unix/MacOS
    ./env/Scripts/activate # Windows
    ```
    Alternatively: 
    ```bash
    conda env create -f environment.yml
    conda activate env
    ```

- Upgrade pip and install required libraries (skip if using conda):
    ```bash
    python3 -m pip install --upgrade pip
    pip install -r requirements.txt
    ```

**Note:** The main libraries are 'opencv-python' and 'mediapipe' for hand tracking and 'pyatv' for interacting with Apple TV.

## 🏃‍♂️ How to Run
Simply open the `GestureControlAppleTV.ipynb` Jupyter Notebook and follow the instructions there.

## 🌟 Features
- Power On/Off
- Scroll Up/Down/Right/Left
- Play/Pause
- Back/Exit
- Control Center
- Volume Control (Coming soon)

## 👏 Contributions
Open to contributions! If you have suggestions or improvements, feel free to fork the repo and create a pull request.

## 📜 License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
