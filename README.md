# IPCamLive OBS Source

A simple HTML page that allows a feed from [IPCamLive](https://www.ipcamlive.com/) to be used as an OBS source.

## Instructions

1. Save the HTML file locally.
1. In OBS, add a _Browser Source_.
1. Don't use the "Local File" option!
1. Use the full local file path, eg. `file:///full/path/to/camera.html?alias=5582ee930f0e6`
1. Set the alias value to match the ID of your camera.

## Requirements
- The camera must be publicly accessible.
