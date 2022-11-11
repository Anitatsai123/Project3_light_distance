# 專案3
光線與距離感測器的監控視窗

[自動執行程式](https://learn.sparkfun.com/tutorials/how-to-run-a-raspberry-pi-program-on-startup/all#method-2-autostart)

啟動時自動執行應用程式

1 建立 .desktop File

mkdir /home/pi/.config/autostart
nano /home/pi/.config/autostart/clock.desktop

2 clock.desktop的內容為

[Desktop Entry]
Type=Application
Name=Clock
Exec=/usr/bin/python3 /home/pi/clock.py
