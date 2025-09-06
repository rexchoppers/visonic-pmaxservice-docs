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
- 



## Accessing Captured Images

- Motion-triggered snapshots are saved in the configured FTP folder.  
- Files are usually named by timestamp (e.g., `2025-09-06_14-30-22.jpg`).  
- View them directly in any image viewer.

## Accessing Audio Clips

- Audio recordings are stored alongside images.  
- Files typically use `.wav` format (check your firmware version).  
- Download them from FTP and open with any standard media player.

## Troubleshooting

- **No media files appear on FTP**: Check PowerLink network connectivity.  
- **Authentication errors**: Re-enter FTP credentials and test with a manual client.  
- **Corrupted files**: Verify the FTP server supports passive mode.