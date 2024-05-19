# Capture FabLab Project

## Authors
- [BELABDELLI Rizlène](https://github.com/Riizlene)
- [BOUGHERARA Hanane](https://github.com/hanane-bougherara)
- [IDOUDERB Karima](https://github.com/karima-idouderb)
- [OUERFILI Chaïma](https://github.com/Chaimaaaaaaaaaaa)

## Overview
The Capture FabLab project was designed to address a crucial need within the FabLab: project documentation. Often overlooked or considered tedious by users, the documentation process has been simplified through a system that captures videos of the work being done and automatically uploads them to a dedicated server. This project aims to make documentation more accessible and attractive, encouraging comprehensive and regular recording throughout a project's lifecycle. This will facilitate the continuation, improvement, reproduction, and collaboration on projects within the FabLab community.

## Table of Contents
1. [Introduction](#introduction)
2. [Client Requirements](#client-requirements)
3. [System Architecture](#system-architecture)
4. [Project Development Stages](#project-development-stages)
5. [Project Validation](#project-validation)
6. [Conclusion](#conclusion)

## Introduction
The Capture FabLab project was initiated to meet a critical need in the FabLab: project documentation. Users often neglect or find this step tedious. To streamline this process, we developed a system that captures videos of ongoing work and automatically sends them to a dedicated server. The primary goal is to make documentation more accessible and appealing, thereby encouraging users to document their projects comprehensively and consistently throughout their development. This initiative aims to facilitate the continuation, improvement, reproduction, and collaboration on projects within the FabLab.

## Client Requirements
- **Video Recording Control**: Ability to start and stop video recording on demand.
- **User-friendly Interface**: Simple interface with easily identifiable buttons for starting and stopping video recording, ensuring intuitive use.
- **Battery Power**: The system must be powered by a rechargeable battery with a minimum autonomy of 6 hours and a maximum recharge time of 8 hours.
- **Recording Indicator**: An LED should clearly indicate when video recording is in progress.
- **Framerate Adjustment**: A dial to adjust the video framerate, providing flexibility in recording quality.
- **Video Storage on Dedicated Server**: Set up a server to store captured videos, ensuring data preservation and availability for FabLab users.
- **Automatic Data Transfer**: Videos should be automatically transferred from the Raspberry Pi 4 (or other components) to the server upon recording, ensuring continuous documentation.
- **Ease of Assembly for Makers**: The system should be easy to assemble and reproduce, encouraging wider adoption within the FabLab community.
- **Portable and Practical Prototype**: The prototype should be compact and lightweight for easy relocation and use in different FabLab contexts.

## System Architecture
- **Raspberry Pi 4**: Acts as the system's brain, running Python code to control video capture, manage webcam settings, handle recording, and manage video transfers to the server.
- **Webcam**: Used to capture videos of FabLab projects, connected to the Raspberry Pi 4 and controlled by the Python code.
- **External Battery**: Provides continuous power for a minimum of 6 hours as required by the client.
- **PCB (Printed Circuit Board)**: Connects and organizes electronic components, ensuring a compact layout and stable connections.
- **Enclosure**: A specially designed box houses and protects all system components, robust enough for FabLab environments while being compact for easy transport.

## Project Development Stages
1. **Research and Integration of Video Recording Code**: We began by researching and testing Python codes to capture videos from a webcam and store them on the Raspberry Pi 4. Once a functional code was found, it was modified to integrate into the system, ensuring basic recording functionality.
2. **Integration of Control Buttons**: Physical buttons were added to the system to start and stop video recording. These buttons were connected to the Raspberry Pi 4 and programmed to trigger the appropriate actions in the Python code.
3. **Framerate Selection Using a Strip Switch**: A strip switch was used to allow users to select different predefined framerate values for the video, as the Raspberry Pi 4 can only handle numerical values for framerate. This approach was chosen over a potentiometer to avoid additional analog-to-digital conversion.
4. **Testing and Adjustments**: After integrating the main functionalities, tests were conducted to ensure everything worked correctly. Adjustments were made to the code and hardware based on test results to ensure system reliability.
5. **Enclosure Design**: During development, the enclosure design was finalized to house all components neatly.

## Project Validation
- **Regular Client Meetings**: Bi-weekly meetings with the client were held to discuss project progress, gather feedback on developed features, and obtain advice and recommendations. These meetings ensured transparent and effective communication, ensuring the project met the client's needs.
- **Regular Testing**: Continuous testing was performed throughout development to verify that all system functionalities worked correctly, including video recording, control buttons, framerate selection, etc.
- **Internal Team Meetings**: Regular team meetings were held to organize tasks, discuss challenges, and resolve any obstacles. These meetings ensured effective collaboration and smooth project progress.

## Conclusion
The Capture FabLab project has been successful on many fronts. Not only did we deliver a functional and reliable prototype on time, but we also gained valuable skills and experiences for future projects. Despite the challenges encountered, our determination and commitment were key to our success. This project represents an important milestone in our professional journey, and we are proud of the contribution we have made to the FabLab community.
