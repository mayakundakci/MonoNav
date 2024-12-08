# Maya Kundakci Project Documentation

## Project Description
Implemented Nathaniel Simon and Anirudha Majumdar's MonoNav monocular navigation stack.

## Hardware
- Crazyflie 2.1
- Wolfwhoomp monocular camera
- Flow deck v2
- 350mAh LiPo battery
- Video receiver
- Crazyradio PA

## Project Timeline

**Setup and Configuration for Crazyflie** 

1. Setting up the required dependencies:
   - [Crazyflie Python Library](https://github.com/bitcraze/crazyflie-lib-python)
   - [Crazyflie Client](https://github.com/bitcraze/crazyflie-clients-python)
   - [Crazyflie Firmware](https://github.com/bitcraze/crazyflie-firmware)
2. Driver Installation and Connectivity
   - Install the Crazyradio USB Driver ([Zadig](https://zadig.akeo.ie/) for Windows)
3. Hardware-Software Integration:
   - Linking the Crazyflie hardware and Crazyflie Python library to interact via cfclient.

**Setup and Configuration for MonoNav** 

1. Setup a Linux environment
2. Install dependencies for MonoNav
3. Install dependencies for ZoeDepth
4. Update MonoNav code base to be compatible with environment
   - ZoeDepth state dict parameter compatability
   - OpenCV path
5. Configure video stream setup (video receiver and computer)

**MonoNav Implementation**

1. Ran demo data to ensure MonoNav was setup correctly
2. Calibrated camera using MonoNav calibrate.py (OpenCV)
3. Collected depth data streaming from Crazyflie and mapped environments (data/Room and data/Hallway)


