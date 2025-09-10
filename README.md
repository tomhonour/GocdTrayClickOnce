# GocdTrayClickOnce

[GocdTray](https://github.com/tomhonour/GocdTray) is a Microsoft Windows System Tray Application for monitoring [Go.cd](https://www.gocd.org/).

This project is a [ClickOnce](https://en.wikipedia.org/wiki/ClickOnce) installation of GocdTray.

To install GocdTray download and run [setup.exe](https://raw.githubusercontent.com/tomhonour/GocdTrayClickOnce/master/setup.exe).

Because I don't have a code signing certificate you will be presented with a scary warning from windows defender.

![Windows Defender](Images/windows-defender.png?raw=true "Windows Defender")

Click on the "More info" link, then the "Run" button.

You will now be presented with another slightly less scary warning

![Application Install](Images/application-install.png?raw=true "Application Install")

Click on "Install".

The application will install and start, though windows defender may bug you again.

## Make the icon appear in the system tray all the time

- Right click on Taskbar > Taskbar settings
- Choose "Select which icons appear in the taskbar"
- Switch on "GocdTray.App"
