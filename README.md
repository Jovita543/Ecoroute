# EcoRoute – Eco-Route Optimization System

## Project Overview

EcoRoute is a web-based Eco-Route Optimization System developed as part of an academic sustainability project.

The system is designed to help users compare alternative travel routes by considering travel time, distance, traffic conditions, estimated fuel consumption and estimated CO₂ emissions.

These factors are combined into an Eco-Score to identify a route that provides a balance between travel efficiency and environmental performance.

## Problem Addressed

Traffic congestion can increase travel time, fuel consumption, vehicle idling and emissions.

Traditional route selection often focuses mainly on distance and travel time. EcoRoute additionally considers environmental factors such as estimated fuel consumption and CO₂ emissions.

## Main Features

- Plan Your Trip
- Compare Routes
- Emission Calculator
- References

## Technology Used

- HTML
- CSS
- JavaScript

## Eco-Score

The prototype combines several factors into an Eco-Score:

- Travel Time – 25%
- Distance – 15%
- Traffic – 25%
- Fuel-related performance – 35%

The route with the highest Eco-Score is displayed as the recommended route.

## Emission Calculation

Fuel consumption is estimated using:

Fuel Consumption = Distance ÷ Vehicle Fuel Efficiency

Estimated CO₂ emissions are calculated using:

CO₂ Emission = Fuel Consumed × CO₂ Emission Factor

The values used in the prototype are estimates and are not certified measurements.

## Current Prototype

The current prototype uses predefined sample route and vehicle data.

It does not currently use live GPS, real-time traffic information or live navigation APIs.

## Project Structure

- `index.html` – Home page
- `planner.html` – Trip planning and eco-route recommendation
- `compare.html` – Route comparison
- `calculator.html` – Emission calculator
- `references.html` – References
- `css/style.css` – Website styling
- `js/script.js` – Website functionality
- `PPT/` – Group presentation
- `Reports/` – Individual reports

## Project Documentation

The repository contains the group presentation and individual technical reports associated with the project.
