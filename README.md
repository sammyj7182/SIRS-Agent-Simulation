# SIRS-Agent-Simulation
Repository for SIRS Agent Simulation Project
# SIRS Model Simulation

A simple **SIRS** (Susceptible-Infected-Recovered-Susceptible) model simulation, built using Python. This project simulates disease spread across geographic locations with agents moving and interacting as well as stochastic event implementation using a simple Gillespie Algorithm.

## Description
The model simulates the spread of disease across multiple cities and towns, where agents are randomly assigned to these locations. The model accounts for factors such as:
- Infection rates
- Recovery rates
- Immunity loss
- Agent movement between locations
The model uses a **random walk** for agent movement and applies **SIRS dynamics** at each timestep.

## Installation

To run the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/sammyj7182/sirs-model.git
   ```

2. Navigate to the project directory:
   ```bash
   cd sirs-model
   ```

3. Create and activate a virtual environment (optional but recommended):
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

4. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

To run the model, simply execute the main script:
```bash
python sirs_model.py
