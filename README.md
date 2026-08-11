# Self-Balancing Robot using MATLAB & Simulink (LQR Control)

An inverted-pendulum based Self-Balancing Robot dynamic modeling and control system simulation developed in MATLAB & Simulink using Linear Quadratic Regulator (LQR).

##  Project Overview
* **System Model:** Inverted Pendulum on a Cart
* **Control Algorithm:** Full-State Feedback via LQR Matrix Calculation
* **Tools Used:** MATLAB R2023b / Simulink


## Output Video (Drive Link): https://drive.google.com/drive/folders/1hvzbcNUAsTKtpbh_FfF7UkfyzV4Gx46E?usp=drive_link



## Mathematical Model & State Variables
States: $x = [x, \dot{x}, \theta, \dot{\theta}]^T$
* $x$: Position
* $\dot{x}$: Velocity
* $\theta$: Tilt Angle
* $\dot{\theta}$: Angular Velocity

##  How to Run
1. Open MATLAB and run `setup_robot.m` to load system matrices ($A, B, C, D$) and LQR Gain ($K$) into the workspace.
2. Open `robot_model.slx` in Simulink.
3. Click **Run** and open the **Scope** block to view system stability plots.

