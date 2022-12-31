# SDCND05_Motion_Planning_and_Decision_Making
Project 5 of Udacity's "Self-Driving Car Engineer" Nanodegree Program about motion planning and decision making for automomous vehicles.

## Purpose of This Repo

This repository contains the starter code to launch in the SDC Planning course workspace.

## Project Setup Instructions

Follow the series of the commands in the workspace to launch the CARLA simulator:

Open new terminal window:
```
su - student
// Will say permission denied, ignore and continue
cd /opt/carla-simulator/
// Launch Carla simulator
SDL_VIDEODRIVER=offscreen ./CarlaUE4.sh -opengl
```

Open new terminal window:
```
// Clone this repo
git clone https://github.com/AndiA76/SDCND05_Motion_Planning_and_Decision_Making.git
cd SDCND05_Motion_Planning_and_Decision_Making/project
// Install virtual environment
./install-ubuntu.sh
// Build executable project files
cd starter_files/
cmake .
make
// Run executable project files
cd nd013-c5-planning-refresh/project
./run_main.sh
// This will silently fail 
ctrl + C to stop 
// Run again ... this time a window should open to visizalize the simulation
./run_main.sh again
Go to desktop mode to see CARLA

// If error bind is already in use, or address already being used
ps -aux | grep carla
kill id
```

## License
Remarks: Since the the code in this repository was build on the [starter code](https://github.com/udacity/nd013-c5-planning-starter) provided by Udacity, it automatically falls under the Udacity license, too:

[LICENSE.md](./LICENSE.md)

This also applies to the changes, extensions or modifications implemented by the code owner, s. [CODEOWNERS](./CODEOWNERS).
