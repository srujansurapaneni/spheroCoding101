# spheroCoding101
API imp points to remember and capture basic commands to start with

Movement:
Sphero robots move with three basic instructions: heading, speed, and duration.

await roll() -- accepts three integer arguments for heading, speed and duration
setSpeed() -- accepts one integer argument - keeps moving fwd/bkwd if not stopped
stopRoll() -- stops the robot (== setSpeed(0))
setHeading() -- sets heading angle
await spin() -- accepts 2 integer arguments for spin at angle value and for how long to spin
await rawMotor() -- accepts 3 integer values - one for left motor speed, one for right motor and the last argument to run it for certain time period


