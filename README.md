# SAR Scout – Search and Rescue Drone & Rover

## Overview

SAR Scout is a personal engineering project focused on developing a search-and-rescue system that combines a ground rover with a compact, dockable quadcopter.

The idea is to create a system that can explore areas that may be difficult to access. The rover provides a mobile ground platform, while the drone can launch from the rover to investigate locations that the rover cannot easily reach. By combining both platforms, I hope to create a more versatile search-and-rescue system.

The drone is being designed around a compact, modular frame with four replaceable arms, a removable electronics enclosure, and a front-facing camera. I am also working toward developing a docking system that will allow the drone to land on the rover, transfer captured images, and eventually recharge while docked.

## Project Goals

- **Modular Drone Design:** Develop a compact quadcopter with replaceable arms and accessible electronics.
- **Search and Imaging:** Integrate a camera system capable of capturing useful images during search operations.
- **Ground Rover:** Build a four-wheel-drive rover capable of transporting the drone and exploring its surroundings.
- **Autonomous Capabilities:** Eventually implement autonomous navigation, return-to-rover functionality, and assisted docking.
- **Drone Docking:** Design a docking platform that can securely receive the drone and eventually provide battery charging.
- **Communication:** Establish communication between the rover, drone, and ground station.

## Current Development

I am currently working on the drone's mechanical design using Onshape. This includes the central frame, replaceable arms, motor mounts, electronics enclosure, and camera holder.

The electronics are also being planned around an ESP32 and a Raspberry Pi Zero 2 W, with an Arducam IMX219 8MP camera under consideration for image capture and processing.

The rover, docking system, and autonomous capabilities will be developed as the project progresses.

## Technologies & Tools

- **CAD:** Onshape
- **Microcontrollers:** ESP32
- **Computing:** Raspberry Pi Zero 2 W (planned)
- **Camera:** Arducam IMX219 8MP (planned)
- **Programming:** C++
- **Fabrication:** 3D printing and mechanical assembly

## Long-Term Vision

My goal is to develop a working search-and-rescue prototype that demonstrates how a ground vehicle and an aerial vehicle can work together. I want to design and build as much of the system myself, documenting the engineering decisions, challenges, testing, and improvements along the way.

This project is a work in progress, and the design will continue to evolve as I test different approaches and develop new capabilities.
