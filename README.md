# Table of Contents

- [Drone_S500](#drone_s500)
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

![Drone control](https://github.com/Projectredunimore/Drone_S500/assets/125361810/39cb8d59-2b82-4dd9-9a68-5e05fd69a502)

-   Toggle A: Arming the controller will initialize joystick controls and the drone can now be controlled via the controller.
-   Toggle B: Toggling down this toggle will activate "Emergency Kill" which will stop all motors.

## Flight modes 

**Stabilize:** Stabilize mode provides basic stabilization by automatically leveling the drone and maintaining a stable horizontal attitude.

- Control: The pilot directly controls the drone's throttle, pitch, roll, and yaw inputs, and the flight controller assists by automatically leveling the drone to prevent unwanted tilting or rolling.
- Use Case: Stabilize mode is typically used for manual flying, basic maneuvers, and learning to fly a drone. It's the default mode for many flight controllers and provides a good balance of manual control and stabilization.

**Altitude:** Altitude mode maintains a constant altitude when the throttle stick is centered. It's useful for tasks where you want the drone to hover at a specific height without constant manual adjustments.

- Control: The drone holds its current altitude when the throttle stick is centered. Moving the throttle stick up or down adjusts the altitude.
- Use Case: Ideal for scenarios where you need the drone to maintain a fixed altitude, such as aerial photography or surveying.

**Position:** Position Hold mode allows the drone to maintain its current position (latitude and longitude) using GPS and its current altitude using a barometer or GPS.

- Control: When the control sticks are centered, the drone holds its position in both horizontal and vertical axes. If you move the control sticks, the drone will move accordingly but will return to its held position when the sticks return to the center.
- Use Case: Ideal for tasks where you need the drone to remain stationary in the air, such as aerial photography, surveying, or any application requiring precise positioning.

**Mission:** Executes a series of pre-defined waypoints and commands uploaded to the drone's flight controller.

- Control: The drone follows the mission plan autonomously, including takeoff, waypoint navigation, specific actions (e.g., taking photos), and landing.
- Use Case: Ideal for tasks such as aerial mapping, surveying, inspections, and other applications requiring precise and repeatable flight paths.

**Manual:** Manual mode provides direct control over the drone's movements without any stabilization or assistance from the flight controller.

- Control: The pilot directly controls throttle, pitch, roll, and yaw inputs using the transmitter sticks. The drone responds immediately to these inputs without any automated leveling or stabilization.
- Use Case: Manual mode is typically used by experienced pilots for acrobatic flying, precise maneuvers, or situations where full control over the drone's movements is required.

## Notes before flight

- Before arming the drone, make sure that the throttle is all the way down as it will not be armed because it will read that the throttle is too high.
- Regarding flight modes (specifically altitude and position), the definition given is only an indication as it needs further testing how the drone will behave in correspondence of the joystick positions of the controller.
- For the first flight test, recommended flight mode is "Stabilized" (Knob 1)
