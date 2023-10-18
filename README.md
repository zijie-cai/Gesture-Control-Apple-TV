# Gesture Control Apple TV 🍎📺

## Overview
This project lets you control your Apple TV with simple hand gestures. Designed to be intuitive and user-friendly, it walks you through the implementation steps using a detailed Jupyter Notebook guide.

## 📽️ Video Demonstration
For a quick glimpse of what this project can do, check out the [video demo](https://github.com/zijie-cai/Gesture-Control-Apple-TV/assets/74931355/aed56bc2-e850-4b5f-af31-afad62d0eff9).

## 📚 Technologies Used
- Python
- OpenCV
- [mediapipe](https://developers.google.com/mediapipe): Google's open-source framework, used for media processing. For this poject, it is used for hand tracking.  
- [pyatv](https://pyatv.dev/): a client library for Apple TV and AirPlay devices.
- WebCam
- Apple TV

## 🛠 Installation and Setup
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

**Note:** To run the code successfully, you **must** complete the installation and setup steps.

## 🏃‍♂️ How to Run
Simply clone or download the repository and open the `GestureControlAppleTV.ipynb` Jupyter Notebook and follow the instructions from there.

## 🌟 Features
- Power On/Off
- Scroll Up/Down/Right/Left
- Play/Pause
- Back/Exit
- Control Center
- Volume Control (Coming soon)

## 🚀 Future Updates
Due to the most recent tvOS 16 update, I plan on migrating this project to the tvOS platform for seamless integration. This will include utilizing tvOS APIs for more accurate control mappings and coming up with even better gestures for a more user-friendly experience.

## 👏 Contributions
Open to contributions! If you have suggestions or improvements, feel free to fork the repo and create a pull request.

## 📜 License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
