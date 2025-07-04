# IPCamLive OBS Auto-Player

A simple HTML page that bypasses IPCamLive's autoplay restrictions for use with OBS Browser Sources.

## What it does
- Fetches the direct HLS stream URL from IPCamLive (bypassing their player)
- Automatically plays the stream without requiring any clicks
- Refreshes every 4 minutes to maintain connection
- Works completely unattended in OBS

## How to use
1. Save the HTML file locally
2. Edit the `streamAlias` variable to match your camera ID
3. In OBS, add a Browser Source
4. Point to the local HTML file
5. Set width/height to match your desired resolution

## Why it works
IPCamLive blocks autoplay in their embedded player, but this script finds and plays the direct `.m3u8` HLS stream instead, which has no such restrictions.

## Requirements
- Modern browser (OBS Browser Source works fine)
- The camera must be publicly accessible on IPCamLive
