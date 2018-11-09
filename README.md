# linux-web-server
This project demonstrates my ability to set up a Linux server, configured with good security settings, complete with a deployed a web-app.

## Overview
I've chosen to use an Amazon Lightsail virtual machine, running Ubuntu 16.04. I am using Nginx as the web server, with gunicorn acting as medium to serve my Flask app to the server. For a database to serve the app, I'm using SQLite. I've also installed git and configured Supervisor to simplify the process of restarting the server between code changes.

## Libraries
Within the Python app itself, I'm leveraging the following libraries:
- Flask
- sqlachemy
- oauth2client
- httplib2
- json
- requests

## Server Conofigurations
- Server access requires key-based SSH Authentication
- Server IP: 3.16.80.200
- SSH Port changed to 2200
- NTP enabled on port 123

## Accessing the App:
- Server IP Address: 3.16.80.200
- Web-app URL: http://3.16.80.200.xip.io
