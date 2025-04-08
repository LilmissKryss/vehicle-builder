# Vehicle Builder Application

A command-line application that allows users to create and interact with different types of vehicles using TypeScript and Inquirer.

## Table of Contents

- [Description](#description)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
  - [Creating a Vehicle](#creating-a-vehicle)
  - [Performing Actions](#performing-actions)
- [Video Walkthrough](#video-walkthrough)
- [Technologies Used](#technologies-used)
- [License](#license)

## Description

The Vehicle Builder is an interactive CLI application that demonstrates object-oriented programming concepts in TypeScript. Users can create different types of vehicles (Cars, Trucks, and Motorbikes), each with their own unique properties and behaviors, and perform various actions on them.

## Features

- Create three types of vehicles:
  - Cars
  - Trucks (with towing capability)
  - Motorbikes (with wheelie capability)
- Perform common vehicle actions:
  - Start/stop the vehicle
  - Accelerate/decelerate
  - Turn left/right
  - Reverse
- Perform vehicle-specific actions:
  - Trucks can tow other vehicles
  - Motorbikes can do wheelies
- View detailed information about each vehicle

## Installation

1. Clone the repository
2. Install dependencies:
   ```
   npm install
   ```
3. Build and run the application:
   ```
   npm start
   ```

## Usage

When you start the application, you'll be presented with a menu to either create a new vehicle or select an existing one.

### Creating a Vehicle

1. Select "Create a new vehicle"
2. Choose the type of vehicle (Car, Truck, or Motorbike)
3. Enter the required information:
   - All vehicles: color, make, model, year, weight, top speed
   - Trucks: additional towing capacity
   - Motorbikes: additional wheel specifications

### Performing Actions

After creating or selecting a vehicle, you can perform various actions:

- Print details
- Start vehicle
- Accelerate/decelerate
- Stop vehicle
- Turn left/right
- Reverse
- Tow a vehicle (Trucks only)
- Do a wheelie (Motorbikes only)

## Video Walkthrough

[Click here to watch a video demonstration of the Vehicle Builder application](https://www.dropbox.com/scl/fi/1y2qklxy48axb9he9gudg/vehicle-builder-video-walkthrough.mov?rlkey=fyx8pmg2n954j6rbu1eby7hg8&st=7tt8l1yl&dl=0)

## Technologies Used

- TypeScript
- Node.js
- Inquirer.js (for interactive CLI)

## License

MIT
