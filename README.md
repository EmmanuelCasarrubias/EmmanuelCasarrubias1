Control Systems Simulation Examples

This repository contains Python scripts for simulating various control systems using different control strategies. Each script demonstrates the behavior of the controlled system, error signals, and control signals through plots.
Installation

    Clone the repository:

    bash

git clone https://github.com/yourusername/control-systems-simulation.git

Navigate to the repository directory:

bash

cd control-systems-simulation

Install the required dependencies:

    pip install -r requirements.txt

Contents
1. Classic Sliding Mode Controller with Dynamic Gain

    File: classic_sliding_mode_controller.py
    Description: Simulates a second-order system controlled by a Classic Sliding Mode Controller with Dynamic Gain. The plot includes the system response, error signal, and control signal.

2. Higher-Order Sliding Mode Controller with Dynamic Sliding Surface

    File: higher_order_sliding_mode_controller.py
    Description: Simulates a second-order system controlled by a Higher-Order Sliding Mode Controller with a Dynamic Sliding Surface. The plot includes the system response with delay, error signal, control signal, and evolution of dynamic gain.

3. Nonlinear Sliding Mode Control with Lyapunov Function

    File: nonlinear_sliding_mode_control.py
    Description: Simulates a nonlinear dynamic system controlled by a Nonlinear Sliding Mode Controller with a Lyapunov function. The plot includes the system response, reference trajectory, and control signal.

4. Sliding Mode Controller with Delay

    File: sliding_mode_controller_with_delay.py
    Description: Simulates a second-order system controlled by a Sliding Mode Controller with Delay. The plot includes the system response with delay, error signal, control signal, and evolution of dynamic gain.

5. Sliding Mode Control with Levant Observer

    File: sliding_mode_control_with_levant_observer.py
    Description: Simulates a dynamic system controlled by Sliding Mode Control with a Levant Observer. The plot includes the comparison between actual and estimated states, as well as the control signal.

6. Super Twisting Controller

    File: super_twisting_controller.py
    Description: Simulates a second-order system controlled by a Super Twisting Controller. The plot includes the system response, error signal, and control signal.

Usage

Run each Python script using your preferred Python interpreter. Adjust parameters as needed for specific simulations.

Example:

python classic_sliding_mode_controller.py

Contributing

Contributions are welcome! If you'd like to contribute to this project, feel free to open a pull request or submit an issue.
License

This project is licensed under the MIT License. See the LICENSE file for details.
