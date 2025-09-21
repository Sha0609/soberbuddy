# BlaBlaCar Clone App

## Overview
This project is a clone of the BlaBlaCar carpooling application, designed to connect drivers and customers for ride-sharing. The app allows users to log in, manage rides, and search for available trips.

## Features
- User authentication (login, logout, register)
- Driver interface for managing rides and viewing requests
- Customer interface for searching and booking rides
- Navigation between different screens (Login, Driver, Customer)

## Project Structure
```
blablacar-clone-app
├── src
│   ├── components
│   │   ├── DriverInterface.tsx
│   │   ├── CustomerInterface.tsx
│   │   └── LoginPage.tsx
│   ├── navigation
│   │   └── AppNavigator.tsx
│   ├── screens
│   │   ├── DriverScreen.tsx
│   │   ├── CustomerScreen.tsx
│   │   └── LoginScreen.tsx
│   ├── services
│   │   └── authService.ts
│   ├── types
│   │   └── index.ts
│   └── App.tsx
├── package.json
├── tsconfig.json
└── README.md
```

## Installation
1. Clone the repository:
   ```
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```
   cd blablacar-clone-app
   ```
3. Install the dependencies:
   ```
   npm install
   ```

## Usage
1. Start the application:
   ```
   npm start
   ```
2. Open your browser and go to `http://localhost:3000` to access the app.

## Contributing
Contributions are welcome! Please submit a pull request or open an issue for any suggestions or improvements.

## License
This project is licensed under the MIT License.