# Accessing Images and Audio from the Visonic Next CAM K9 PG2 via PowerLink and FTP

The **Visonic Next CAM K9 PG2** is a PIR motion detector with a built-in camera and microphone.  
When paired with the **PowerLink3.1 module**, you can capture, store, and access both **images** and **audio recordings** via **FTP**.

## Requirements

- Visonic PowerMaster panel  
- PowerLink3.1 module  
- Next CAM K9 PG2 sensor
- FTP Client

## Tested On
- PowerMaster 10

## Details
- The panel splits the captured media into:
  - **Images**: Captured when motion is detected.
  - **Audio Clip**: Short recording accompanying the images.
- This captures only 5 seconds of audio per event.
- The files are stored with the name: `<SensorID>_<INDEX>.<extension>`
  - Example: `cam11_10.jpg.jpg` and `cam11_0.wav`

## Credentials
- Default FTP credentials:
  - **IP**: `<PowerLink_IP_Address>`
  - **Username**: `<BLANK>`
  - **Password**: `<BLANK>`