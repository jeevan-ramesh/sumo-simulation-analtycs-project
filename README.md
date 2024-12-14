# traffic-light-with-without-yellow

# Traffic Simulation and Analysis Using SUMO

This repository contains the implementation of a traffic simulation project using the **SUMO (Simulation of Urban Mobility)** simulator. The project analyzes traffic flow under different signal configurations and evaluates the impact of a yellow light on traffic congestion and fuel economy. It also includes statistical analysis and visualization, such as plotting normal distributions of traffic parameters.

## Table of Contents

- [Introduction](#introduction)
- [Project Objectives](#project-objectives)
- [Methodology](#methodology)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Future Work](#future-work)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Efficient traffic management is essential for reducing congestion and improving fuel efficiency. This project leverages SUMO to simulate traffic scenarios and analyze the effects of introducing a yellow light between red and green signals.

## Project Objectives

1. Simulate traffic with and without a yellow light in SUMO.
2. Collect and analyze traffic data for various parameters.
3. Visualize traffic patterns and evaluate the statistical distribution of key metrics.
4. Provide insights into the impact of traffic signal configurations.

## Methodology

1. **Simulation Setup**:
   - Created a traffic network in SUMO.
   - Configured signal plans with and without a yellow light phase.

2. **Data Collection**:
   - Extracted traffic metrics such as vehicle count, average speed, and fuel consumption.

3. **Analysis**:
   - Analyzed the data to observe trends.
   - Plotted normal distributions for traffic parameters.

4. **Visualization**:
   - Generated graphs and heatmaps to represent results.

## Features

- Traffic simulation using SUMO.
- Comparison of traffic conditions with and without yellow lights.
- Statistical analysis and visualization of traffic data.
- Insights into traffic efficiency and fuel economy.

## Requirements

- SUMO Simulator
- Python 3.7+
- Required Python libraries: pandas, numpy, matplotlib, seaborn, scipy

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/sumo-traffic-simulation.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Install SUMO:
   - Follow the official [SUMO installation guide](https://sumo.dlr.de/docs/Installing.html).

## Usage

1. Configure the simulation files in the `simulation` directory.
2. Run the SUMO simulation:
   ```bash
   sumo -c simulation/your_config.sumocfg
   ```
3. Perform analysis:
   ```bash
   python analysis.py
   ```
4. View results:
   - Generated plots will be saved in the `output` directory.

## Results

- Traffic with yellow lights exhibited smoother flow and reduced congestion.
- Normal distribution plots revealed statistical differences in traffic parameters.

## Future Work

- Extend analysis to multi-lane traffic scenarios.
- Incorporate reinforcement learning for adaptive traffic signals.
- Evaluate real-world datasets for further validation.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.
