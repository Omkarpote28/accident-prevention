# accident-prevention
# Accident Prevention in Ghat Section using Ultrasonic Sensors and LED Lights

## Overview

This GitHub repository contains the code and documentation for a project aimed at preventing accidents in ghat sections through the use of ultrasonic sensors and LED lights. The system is designed to activate LED lights based on the distance between the vehicle and the surrounding obstacles, enhancing visibility and alerting drivers to potential dangers.

## Table of Contents

- [Introduction](#introduction)
- [Components](#components)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Ghat sections, characterized by winding and steep roads, pose unique challenges for drivers. This project addresses the safety concerns in such areas by utilizing ultrasonic sensors to measure the distance between the vehicle and nearby obstacles. Based on these distance measurements, LED lights are activated to provide visual cues to the driver, indicating the level of proximity to potential hazards. Additionally, a buzzer is included to provide an audible alert.

## Components

The project involves the following components:

- Arduino Board
- Ultrasonic Sensors (1 in total)
- LED Lights (6 in total)
- Buzzer
- Wiring and Connectors

## Installation

Follow these steps to set up the project:

1. **clone the repository**

2. **Upload Code to Arduino:**
   - Open the Arduino IDE.
   - Load the Arduino code [accident_prevention.ino](https://github.com/Omkarpote28/accident-prevention/tree/main/Code) from the repository.
   - Connect the Arduino board to your computer and upload the code.

3. **Assemble Hardware:**
   - Connect ultrasonic sensors, LED lights, and buzzer based on the provided schematic.
   - Ensure all components are securely connected.

## Usage

1. **Power On:**
   - Connect the Arduino board to the power source.

2. **Start Driving:**
   - As you drive through ghat sections, the ultrasonic sensors will measure distances.
   - LED lights will illuminate based on the proximity of obstacles.
   - The buzzer will sound if the vehicle is dangerously close to an obstacle.

3. **Monitor LEDs:**
   - Green LED: Safe distance
   - Yellow LED: Caution (approaching obstacles)
   - Red LED: Danger (imminent collision)

## Configuration

Adjust the following parameters in the code to customize the system:

- `DISTANCE_THRESHOLD`: Set the distance thresholds for activating different LEDs.
- `BUZZER_THRESHOLD`: Define the distance that triggers the buzzer.

## Contributing

Contributions to the project are welcome. Feel free to open issues, submit pull requests, or provide feedback.
