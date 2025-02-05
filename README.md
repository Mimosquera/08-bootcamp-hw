# Vehicle Builder

## Description

Vehicle Builder is a TypeScript command-line application that allows users to create and manage different types of vehicles, including Cars, Motorbikes, and Trucks. Users can input details about a vehicle, select an existing vehicle, and perform various actions with it.

## Walkthrough Video

[https://drive.google.com/file/d/1X_yyVVxsOYlxfBmzpFpB5j5_-kaVT4bo/view]

## Installation

1. Clone the repository:
   ```bash
   git clone [git@github.com:Mimosquera/08-bootcamp-hw.git]
   ```
2. Navigate to the project directory:
   ```bash
   cd vehicle-builder
   ```
3. Install dependencies:
   ```bash
   npm install
   ```

## Usage

To start the application, run:
```bash
npm start
```

## Features
- Users can create a new vehicle or select an existing one.
- Available vehicle types: **Car, Motorbike, and Truck**.
- Each vehicle type has unique attributes and actions.
- Users can enter specific details for their chosen vehicle.
- After creating or selecting a vehicle, users can perform various actions.
- The application continues prompting for actions until the user chooses to exit.

## Technologies Used
- TypeScript
- Node.js
- Inquirer.js

## File Structure
```
vehicle-builder/
├── src/
│   ├── Car.ts
│   ├── Truck.ts
│   ├── Motorbike.ts
│   ├── Vehicle.ts
│   ├── Wheel.ts
│   ├── cli.ts
├── package.json
├── tsconfig.json
└── README.md
```

## License


