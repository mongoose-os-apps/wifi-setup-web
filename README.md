# Setup WiFi via Web UI

- Start [mos tool](https://mongoose-os.com/software.html),
  import this app, build it and flash it.


- Do not configure WiFi - leave the module in AP (Access Point mode).
- Mongoose OS starts a WiFi network called `Mongoose_XXXXXX` with password
`Mongoose`. Switch your workstation to that WiFi network
- Point your browser to http://192.168.4.1
- You'll see a simple form to configure WiFi network & password

![Screenshot](shot.png)