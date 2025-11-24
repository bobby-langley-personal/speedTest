Tizen Kiosk Speed Test App

This is a minimal Samsung Tizen Web App designed for kiosk environments.
Its only purpose is to launch a common network speed test inside an iframe.
One loaded, tap "Run" and wait for the diagnostics to appear.

The app is intentionally simple — making it ideal for kiosks or digital signage that need a quick connectivity check via an L1 support team.

🚀 Features

Small 

Installs and loads on Tizen kiosk

Displays a hosted speed test website inside an <iframe>


Notes: 
As libraries evolve and stop playing well with the chromium 56 node 4.4.3 versions running on the kiosk, other URL's may have to be used. 


To run it:
Open URL installer on tizen kiosk and then input the speedtest zip file url from it's hosted location (previously an old S3 bucket)
Wait for install, load, init. 
Tap on "Run"
