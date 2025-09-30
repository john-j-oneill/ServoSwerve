# ServoSwerve
Central location for 3D Printed FTC Robot Project

# Concept
This is a hobby project, trying to bring swerve-drive, which is popular in FRC robots, to an FTC-legal robot. It also uses only 4 motors and 4 servos, allowing for additional motors for other mechanisms. Additionally, the idea of the project was to use as much 3D printing as possible, and otherwise cheap components. The servos used in the prototype are cheap and have no feedback, but they could be upgraded to more powerful and/or more capable options.

The total BOM is ~300 USD, which does not include the [Control Hub, Driver Hub and Battery](https://www.revrobotics.com/rev-35-1906/), which would run an additional $720. For non-FTC use however, those could be replaced with much cheaper alternatives, such as Arduino or Raspberry Pi.

# CAD
[Onshape link](https://cad.onshape.com/documents/ad19ade7c9992a06461c1741/w/d23e84fc5c3f91f4c1dab8da/e/eb4be498351a02de772e0bd7) for Swerve drive.

# BOM
| Part | Quantity | Cost (USD) | Link |
|------|----------|------------|------|
| Heat Set Inserts   | ~50   | $5 per 200  | https://a.co/d/6xFzpqj |
| 608-2RS Bearings   | 20    | $18 per 100 | https://a.co/d/bSbgQkI |
| MG996R Servo       | 4     | $18 per 4   | https://a.co/d/boWs8Dm |
| 6005-2RS Bearings  | 4     | $18 per 10  | https://a.co/d/0550xRT |
| M3 12mm SHCS       | ~50   | $9 per 100  | https://a.co/d/3k4A5e6 |
| TPU Filament       | 30g   | $23 per kg  | https://a.co/d/iWYk3IK |
| PLA Filament       | 1.8kg | $28 per kg  | https://a.co/d/3Dp54A6 |
| Rev Ultraplanetary | 4     | $45 per ea  | https://www.revrobotics.com/rev-41-1600/ |
| 5mm x 75mm Hex     | 4     | $12 per 4   | https://www.revrobotics.com/5mm-Hex-Shafts/ (REV-41-1347-PK4) |

# Printer
I printed on a Bambu X1C, but the swerve modules should be printable even on an A1 Mini (although the chassis as currently designed would not fit).
The total print time is approx 66 hours on my X1C with a 0.4 mm nozzle, using approx 1.8kg when printing with the "0.2 Strength" preset.
Strength is probably not needed for all parts, but the main swerve swivelling part with the print-in-place bearing probably needs it at least.

# Code
Basic swerve drive code including both robot-oriented and field-oriented control schemes was coded in Blocks as a proof of concept.
