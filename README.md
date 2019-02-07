## League Director
[![License](https://img.shields.io/badge/license-Apache%202-blue.svg)](https://github.com/riotgames/leaguedirector/blob/master/LICENSE)
[![Python](https://img.shields.io/badge/python-3.7-brightgreen.svg)](https://www.python.org/downloads/release/python-372/)
[![Qt](https://img.shields.io/badge/pyside2-5.12.0-brightgreen.svg)](https://www.qt.io/qt-for-python)
[![Chat](https://img.shields.io/badge/chat-on%20discord-lightgrey.svg)](https://discord.gg/010zxwmnpLTuQY6sG)

League Director is a tool for staging and recording videos from [League of Legends](https://leagueoflegends.com) replays.

![Screenshot](resources/screenshot.png)

## Features

* Control replay playback and speed
* First person camera controls
* Attach camera to champion or minion
* Toggle interface elements including HUD, health bars and notifications
* Graphical Options
  - Field of view
  - Near and far clipping
  - Custom skyboxes
  - Shadow direction
  - Depth and height fog
  - Depth of field
* Sequencer
  - Record and playback keyframed camera position + graphical options
  - Timeline for viewing and editing keyframe values
  - Undo / Redo
  - Save and load pre saved sequences
  - Adjustable keyframe blending
* Video capture in webm or png format
* Customizable key bindings

## How To Use

**Note: Windows Only**

1. Download the latest version from the releases page and install.
2. Start League Director and make sure the checkbox next to your install is checked.
3. Start League of Legends and launch a replay. League Director will automatically connect.
4. Select FPS Camera from the Camera Modes **inside the replay client**.
5. Using the numpad keys (4, 5, 6, 8) and the mouse you can free camera move around. Key bindings for free camera can be changed inside the game options.

## Tutorial

[![](http://img.youtube.com/vi/UOxkGD8qRB4/0.jpg)](http://www.youtube.com/watch?v=UOxkGD8qRB4 "League Director Tutorial")

## Frequently Asked Questions
TODO

## Developing
To run the source version of this application you need the [latest 3.7.2 version](https://www.python.org/downloads/release/python-372/)  of Python installed. From the windows command line:

```
# Clone this repository
$ git clone https://github.com/riotgames/leaguedirector.git

# Change directory
$ cd leaguedirector

# Run the startup script
$ run.bat
```

The run batch file will setup a virtual environment using [Pipenv](https://pipenv.readthedocs.io/en/latest/) and install required dependencies such as [Qt](https://www.qt.io/qt-for-python).

_League Director is being release by Riot Games as a reference implementation for the [Replay API](https://developer.riotgames.com/replay-apis.html). You are free to download and modify this source code or create your own fork of the project but we will not be accepting pull requests at this time._

## License
Apache 2 (see [LICENSE](https://github.com/riotgames/leaguedirector/blob/master/LICENSE) for details)

For usage rights of Riot Games intellectual property, such as the skybox textures bundled with this installer, please refer to:

[https://www.riotgames.com/en/legal](https://www.riotgames.com/en/legal)

## Special Thanks
 * Skin Spotlights
 * League of Editing