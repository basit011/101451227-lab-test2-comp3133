# SpaceX Missions Explorer

![SpaceX Missions Explorer Screenshot](./screenshot.png) *(Add a screenshot if available)*

## Overview
A web application that displays SpaceX mission data with filtering capabilities. Users can browse missions, view details, and filter by launch year, launch status, and landing status.

## Features
- 🚀 View all SpaceX missions in a responsive grid
- 🔍 Filter missions by:
  - Launch year
  - Launch status (Success/Failed)
  - Landing status (Success/Failed)
- 📄 Click on mission names to view detailed information
- 🔄 Reset all filters with one click

## Technologies Used
- Angular (v15+)
- TypeScript
- Angular Material (for UI components)
- SpaceX API (https://api.spacexdata.com/v3/launches)
- HTML5 & CSS3

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/basit011/spacex-missions-explorer.git

##  Development Server

Run ng serve for a dev server. Navigate to http://localhost:4200/. The application will automatically reload if you change any of the source files.
Build

Run ng build to build the project. The build artifacts will be stored in the dist/ directory.


##  API Usage

This project uses the public SpaceX API:

 Endpoint: https://api.spacexdata.com/v3/launches


## Project Structure

src/app/
├── components/
│   ├── missiondetails/      # Mission detail view component
│   ├── missionlist/         # Mission list component
│   └── missionfilter/       # Mission filter component
├── models/
│   └── mission.ts           # Mission interface/type
├── services/
│   └── spacex.service.ts    # SpaceX API service
└── shared/                  # Shared utilities


##  Key Components

    Mission List: Displays all missions in a grid with filters

    Mission Details: Shows detailed information about a specific mission

    Mission Filter: Contains the filter controls (year, launch status, landing status)

    SpaceX Service: Handles all API communication with SpaceX


## Contact details
