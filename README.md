# DroneBlocks Tello Camera Access with Python, OpenCV, Flask

A Python based project that allows users to manually control Tello, access the camera, and program Tello with DroneBlocks. Check out the course that walks through the details of installing dependencies and using the app:

https://learn.droneblocks.io/p/opencv-python-and-droneblocks-for-tello-camera-control/

**Please note that this project has only been tested on Windows 10 and Mac OS X**

This project was developed by the DroneBlocks team to provide the following capabilities:

1. Navigate Tello using brower based controls
2. Navigate Tello using the keyboard: wasd for left stick control and up/down/left/right arrows for right stick control
3. Access Tello's camera to take photos and record video
4. DroneBlocks for block-based programming and autonomous flight
5. Basic introduction to computer vision with ArUco markers
6. Joystick control coming soon

## Software dependencies

* [Python 3.7.4](https://www.python.org/downloads/)
* [OpenCV 4](https://opencv.org/opencv-4-0/)
* [OpenCV Contrib](https://pypi.org/project/opencv-contrib-python/)
* [ffmpeg](https://github.com/kkroening/ffmpeg-python)
* [Flask](https://github.com/pallets/flask)

## Installation

Install git to download this code. Use git for windows: https://gitforwindows.org/ or follow directions here for other operating systems: https://git-scm.com/book/en/v2/Getting-Started-Installing-Git

Check that you have Python 3.6 or greater in the git bash terminal.
```
python --version
```

Download and install the latest Python 3 if it isn't already installed. https://www.python.org/downloads/

Install pipenv, which creates Python virtual environments for you
```
pip install pipenv
```

Change to directory that will hold this project, e.g.
```
cd Documents
```

Clone this repository
```
git clone https://github.com/holyokecodes/DroneBlocks-Tello-Camera-With-Python-OpenCV.git
```

Change to this new directory
```
cd DroneBlocks-Tello-Camera-With-Python-OpenCV
```

Install dependencies. This will take a few minutes.
```
pipenv install
```

Start the app
```
python ./app.py
```

Open the app at [http://127.0.0.1:5000](http://127.0.0.1:5000)

## Support
If you need help installing dependencies please consider [purchasing our course](https://learn.droneblocks.io/p/opencv-python-and-droneblocks-for-tello-camera-control) to support this project. You can also feel free to [open an issue](https://github.com/dbaldwin/DroneBlocks-Tello-Camera-With-Python-OpenCV/issues) and join our [Facebook group](https://www.facebook.com/groups/droneblocks/).
