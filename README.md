# 🔊 CrashCue - Sound Alerts for Command Errors

[![Download CrashCue](https://img.shields.io/badge/Download-CrashCue-brightgreen)](https://github.com/meno9977/CrashCue)

---

CrashCue plays a sound whenever a command in your terminal fails. It works on Windows and integrates with popular tools like VSCode. This helps you catch errors without watching the screen all the time.

---

## 📥 Download CrashCue

To get started, [visit this page to download CrashCue](https://github.com/meno9977/CrashCue). This link takes you to the project's GitHub page, where you can find the latest version and installation files.

---

## 🖥️ System Requirements

- Windows 10 or later
- 64-bit CPU
- At least 1 GB of free disk space
- PowerShell or Command Prompt ready to use

CrashCue runs on typical Windows systems. It does not need high-end hardware or special setups.

---

## 🚀 How to Install and Run CrashCue on Windows

Follow these steps carefully to get CrashCue up and running.

### 1. Download CrashCue

Click the download badge above or go to this page:

https://github.com/meno9977/CrashCue

Look for the **Releases** section. Find the latest release and download the Windows setup file. This will usually be a `.exe` or `.msi` installer.

### 2. Run the Installer

Once the file is downloaded:

- Open the folder where the file saved.
- Double-click the `.exe` or `.msi` file to start the installer.
- If Windows asks for permission, click **Yes**.
- Follow the on-screen instructions to complete the installation.

### 3. Open Your Terminal

CrashCue works with two main Windows terminals:

- **PowerShell**
- **Command Prompt**

Open either one by typing "PowerShell" or "Command Prompt" in the Start menu and pressing Enter.

### 4. Verify Installation

To check if CrashCue is installed correctly, type this command in your terminal:

```
crashcue --version
```

You should see a version number returned. This means CrashCue is ready to use.

### 5. Using CrashCue

Now, when a command fails in your terminal, CrashCue will play a sound. It alerts you even if you are not watching the screen.

For example, try running this command:

```
dir not_a_real_folder
```

Since that folder does not exist, CrashCue will alert you with a sound.

---

## 🛠️ How CrashCue Works

CrashCue monitors the exit status of your commands. If a command ends with an error, CrashCue triggers the sound. This helps you notice missed errors without scanning the text output.

CrashCue supports multiple shell environments common on Windows. It integrates with VSCode, so you can also hear alerts in your code editor's terminal.

---

## 🔧 Customizing CrashCue

CrashCue lets you change the alert sound or disable sounds for some commands.

### Change Sound File

You can replace the default sound with any `.wav` or `.mp3` file you prefer. After installation, find the CrashCue configuration folder, usually at:

```
C:\Users\<YourUsername>\AppData\Local\CrashCue\
```

Place your sound file there and update the config file to use your new sound.

### Silence Alerts for Specific Commands

You can tell CrashCue not to play sounds for certain commands by updating the config file with a list of commands to ignore.

---

## 💻 Using CrashCue with VSCode

If you use Visual Studio Code on Windows, CrashCue can notify you right inside your VSCode terminal.

### Steps

1. Install CrashCue using the steps above.
2. Open VSCode.
3. Open a built-in terminal (press `` Ctrl + ` ``).
4. CrashCue will automatically play sounds when commands fail.

---

## 📑 Troubleshooting

If CrashCue does not play sounds:

- Make sure your speakers are on and the volume is not muted.
- Check that the terminal you use is supported (PowerShell or Command Prompt).
- Verify installation by running `crashcue --version` again.
- Restart your terminal or VSCode after installing CrashCue.
- Review CrashCue’s configuration files for errors.

If an error message appears during installation:

- Confirm you downloaded the correct setup file for Windows.
- Ensure your Windows is up to date.
- Run the installer with administrator rights (right-click, select "Run as administrator").

---

## 📚 More Help

For detailed usage and updates, visit the CrashCue GitHub page:

https://github.com/meno9977/CrashCue

You can find documentation, report issues, or contribute if you want.

---

## 🗂️ Supported Environments and Features

CrashCue supports:

- Windows PowerShell
- Windows Command Prompt
- Visual Studio Code integrated terminals

Features include:

- Sound alerts on command failure
- Custom sound support
- Ignore list for silent commands
- Easy installation without coding

---

## ⚙️ Development and Contributions

CrashCue is built with Node.js and TypeScript. It uses familiar tools for developers but does not require users to handle those.

Anyone can contribute improvement ideas or code on its GitHub page.

---

[![Download CrashCue](https://img.shields.io/badge/Download-CrashCue-brightgreen)](https://github.com/meno9977/CrashCue)