ofxOpenVR 
====================

Implementation of Valve Software's [OpenVR](https://github.com/ValveSoftware/openvr) API.

## Installation

You will need to pull the repo and the OpenVR submodules, e.g. :

```
git clone https://github.com/smallfly/ofxOpenVR.git
cd ofxOpenVR
git submodule init
git submodule update
```

## Usage

1. Create an openframeworks' project using the Project Generator, or add the addon's source files and the OpenVR headers to your existing project.
2. In `Property Manager` (open it from `View -> Other Windows -> Property Manager`), right click on your project to select `Add Existing Property Sheet...` and select the `ofxOpenVR.props` file.

## Notes
Tested with the HTC Vive and the Oculus Rift (consumer version) on Windows 10.

