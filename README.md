# 🎧 auto-pause-bluetooth-audio-windows - Stop music when your headphones disconnect

[![](https://img.shields.io/badge/Download-Latest_Release-blue.svg)](https://github.com/Marseillesmandate157/auto-pause-bluetooth-audio-windows/releases)

## 📌 About this application

This application monitors your Bluetooth connection status on Windows. When your computer detects that you have turned off your Bluetooth headphones or moved out of range, the software sends a command to pause your media.

It runs in the background. It does not require you to interact with it during daily use. It works with standard media players and music streaming services that support Windows media controls.

## ⚙️ System Requirements

This software works on devices running Windows 10 or Windows 11. 

*   **Operating System:** Windows 10 (version 1903 or higher) or Windows 11.
*   **Bluetooth:** A functional Bluetooth adapter installed on your computer.
*   **Framework:** The installer includes the necessary components from .NET. You do not need to install extra software manually.
*   **Memory:** The app uses less than 50MB of RAM while running.

## 📥 How to download and install

1.  Visit the [official download page](https://github.com/Marseillesmandate157/auto-pause-bluetooth-audio-windows/releases).
2.  Find the "Assets" section under the latest release.
3.  Click the link ending in `.exe` or `.msi` to start the download.
4.  Open the downloaded file.
5.  Follow the prompts on your screen to complete the installation.
6.  The installer adds a shortcut to your desktop.

## 🚀 Running the application

Once installed, the program starts automatically when you log into Windows. 

1.  Find the small icon in your system tray. The system tray sits near your clock on the bottom right of the screen.
2.  Click the icon to see the menu.
3.  The menu shows your current connection status.
4.  If the icon is gray, the app is waiting for a Bluetooth device. 
5.  If the icon is solid, the app is active and monitoring your connection.

## 🛠 Features

*   **Automatic Detection:** The app detects Bluetooth disconnection events without delay.
*   **Media Control:** It uses Windows native media protocols to ensure compatibility with most apps like Spotify, YouTube, and VLC.
*   **Low Impact:** The software stays quiet. It sends no notifications and creates no pop-ups.
*   **Tray Integration:** It stays out of your way by hiding in the system tray. 
*   **Auto-Start:** The app launches alongside Windows so you do not need to remember to open it.

## ❓ Frequently Asked Questions

**Does this app work with all Bluetooth headphones?**
Yes. The app monitors the Windows Bluetooth adapter state, not the specific headphones. If Windows reports that a device disconnected, the app triggers the pause command.

**Will this interfere with my phone if I use the same headphones?**
No. This software only touches the media controls on your computer. It has no effect on your mobile device.

**How do I close the application?**
Right-click the icon in the system tray and select "Exit."

**Does the app use much battery?**
The program stays idle until a state change occurs in your Bluetooth adapter. It uses virtually no CPU power during this time.

**Can I stop it from starting with Windows?**
You can manage this through the Task Manager. Right-click the Windows Taskbar, select "Task Manager," go to the "Startup" tab, find the application, and select "Disable."

## 🛡 Security and Privacy

This software runs locally on your computer. It does not connect to the internet. It does not send your data to any servers. It does not collect information about your listening habits or your Bluetooth devices. The code is open source, which means anyone can inspect it to verify how it works.

## 🔄 Troubleshooting

*   **Media does not pause:** Check if your media player supports Windows media controls. Some legacy players require manual setup to accept these signals.
*   **Icon does not appear:** Try restarting the application from your desktop shortcut. Ensure your Bluetooth is enabled in Windows settings.
*   **App crashes:** Check if you have the latest Windows updates installed. Ensure your Bluetooth driver is updated via your computer manufacturer website.
*   **The app pauses too often:** Confirm your Bluetooth signal is strong. Weak signals cause the adapter to report temporary disconnects, which forces the app to pause your media. Keep your computer and headphones within range to avoid this.

## 📝 Configuration

The app works out of the box. You do not need to edit text files or change settings to make it work. Advanced users can look at the installation folder if they wish to adjust logging levels, but the default settings provide the best experience for most users. If you change a setting by mistake and the program stops working, simply uninstall and reinstall the application to restore the default state.

## 🤝 Support

If you encounter a bug, verify that you have followed the installation steps above. If issues persist, check the "Issues" section on the main project page. You can view existing reports there to see if others have experienced the same behavior. If you require help, create a new issue by clicking "New Issue" and provide a description of your Windows version and your Bluetooth device model. This helps in identifying the cause of the problem. Maintain a calm environment when reporting issues so contributors can assist you efficiently. Avoid sharing sensitive data like your device MAC address or personal identification in public reports.