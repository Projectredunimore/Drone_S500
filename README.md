# Table of Contents

- [Drone S500 control manual](#drone-s500-control-manual)
- [Flight modes](#flight-modes)
  - [Stabilize](#stabilize)
  - [Altitude](#altitude)
  - [Position](#position)
  - [Mission](#mission)
  - [Manual](#manual)
- [Notes before flight](#notes-before-flight)

# Drone_S500

## Drone S500 control manual

**IMPORTANT: Make sure Toggle A and Toggle B (Arming and emergency kill switches respectively) are toggled up before turning on the RC Controller**

![Drone control](https://github.com/Projectredunimore/Drone_S500/assets/125361810/ee9e5677-074d-4a08-bf7e-b4beb2a998ca)

- **Toggle A**: Arming the controller will initialize joystick controls and the drone can now be controlled via the controller.
- **Toggle B**: Toggling down this toggle will activate "Emergency Kill" which will stop all motors.

## Flight modes

### Stabilize
Stabilize mode provides basic stabilization by automatically leveling the drone and maintaining a stable horizontal attitude.

- **Control**: The pilot directly controls the drone's throttle, pitch, roll, and yaw inputs, and the flight controller assists by automatically leveling the drone to prevent unwanted tilting or rolling.
- **Use Case**: Stabilize mode is typically used for manual flying, basic maneuvers, and learning to fly a drone. It's the default mode for many flight controllers and provides a good balance of manual control and stabilization.

### Altitude
Altitude mode maintains a constant altitude when the throttle stick is centered. It's useful for tasks where you want the drone to hover at a specific height without constant manual adjustments.

- **Control**: The drone holds its current altitude when the throttle stick is centered. Moving the throttle stick up or down adjusts the altitude.
- **Use Case**: Ideal for scenarios where you need the drone to maintain a fixed altitude, such as aerial photography or surveying.

### Position
Position Hold mode allows the drone to maintain its current position (latitude and longitude) using GPS and its current altitude using a barometer or GPS.

- **Control**: When the control sticks are centered, the drone holds its position in both horizontal and vertical axes. If you move the control sticks, the drone will move accordingly but will return to its held position when the sticks return to the center.
- **Use Case**: Ideal for tasks where you need the drone to remain stationary in the air, such as aerial photography, surveying, or any application requiring precise positioning.

### Mission
Executes a series of pre-defined waypoints and commands
