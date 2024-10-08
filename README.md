# Electric-Vehicle-EV-Simulation-with-Regenerative-Braking
# Electric Vehicle (EV) Simulator

## Overview
This project simulates an Electric Vehicle (EV) drivetrain with a focus on regenerative braking. It demonstrates key components of an EV system and how energy is managed and recovered during various driving conditions.

## Key Components

1. **Power Source (Battery Pack)**
   - Simulated by a DC voltage source
   - Powers the electric motor

2. **Electric Motor and Drive Controller**
   - Converts electrical energy to mechanical energy
   - Manages motor operation based on driver inputs

3. **Regenerative Braking System**
   - Allows the motor to act as a generator during deceleration
   - Converts kinetic energy back into electrical energy

4. **Vehicle Dynamics Model**
   - Simulates physical behavior of the vehicle
   - Responds to forces like acceleration, braking, and road grade

5. **Longitudinal Driver Model**
   - Simulates real driving cycles
   - Issues acceleration and braking commands

6. **Control Inputs and Feedback**
   - Includes throttle and brake commands
   - Provides feedback for motor control adjustments

7. **Drive Cycle Source**
   - Uses FTP75 test cycle
   - Simulates realistic driving conditions

## Regenerative Braking Functionality
- Motor acts as a generator during braking
- Converts mechanical energy back to electrical energy
- Recovered energy is stored in the battery
- Drive controller manages the process via PWM signals

