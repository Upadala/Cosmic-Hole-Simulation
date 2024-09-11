# Cosmic-Hole-Simulation
This project aims to use the data collection and analyze using the shot frequency, distance, angle and implement the output. The planet's motion is influenced by the gravitational forces of both a star and a black hole, and this simulation aims to visualize its trajectory under varying initial conditions

## Features
- Simulates the gravitational force acting on a planet due to a star and a black hole.
- Visualizes the planet's motion over time.
- Allows experimenting with different angles for the planet's initial velocity (like cosmic mini-golf!).
- Stops the simulation if the planet falls into the black hole.

## Project Structure

- `gravitational_force`: Calculates the gravitational force exerted on the planet by both the star and the black hole.
- `simulate_motion`: Uses the force to simulate the planet's motion over a period of time.
- `play_round`: Runs a round of the simulation with an initial angle for the planet's velocity.
- Visualization using `matplotlib`.

## How to Run the Simulation

1. Install the required dependencies:
   ```bash
   pip install numpy matplotlib
python cosmic_simulation.py

