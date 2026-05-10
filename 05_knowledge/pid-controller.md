# PID Controller

## What is PID?
PID (Proportional-Integral-Derivative) is a control algorithm that moves the robot
to a target position accurately, without overshooting.

## Our implementation
_Add your code + explanation here._

## Tuning process
1. Set I and D to 0, increase P until the robot oscillates
2. Increase D to dampen the oscillation
3. Add a small I if there's steady-state error

## Values that worked for us
| Scenario | P | I | D |
|----------|---|---|---|
| Drive straight | | | |
| Turn | | | |
