## Anomaly
Testing displays very clear reproduceable trends in changes of sensor data depending on buttons held whilst measuring.
No pneumatic rig was used - testing done by hand which will poison absolute values but there seems to be a trend present that could be indicative of a larger problem.

I included an example reading (Example-Reading.png) and a very short overview (Overview.png) demonstrating the anomaly.

### Optical Units:
WLMouse Beast X Mini Omron Optical (unit 1) - SapphireOS 25H2 - 8Khz High Speed Turbo Mode - No Buttons Held
WLMouse Beast X Mini Omron Optical (unit 1) - SapphireOS 25H2 - 8Khz High Speed Turbo Mode - Mouse 1 Held
WLMouse Beast X Mini Omron Optical (unit 1) - SapphireOS 25H2 - 8Khz High Speed Turbo Mode - Mouse 1+2 Held

WLMouse Beast X Mini Omron Optical (unit 2) - SapphireOS 25H2 - 8Khz High Speed Turbo Mode - No Buttons Held
WLMouse Beast X Mini Omron Optical (unit 2) - SapphireOS 25H2 - 8Khz High Speed Turbo Mode - Mouse 1 Held
WLMouse Beast X Mini Omron Optical (unit 2) - SapphireOS 25H2 - 8Khz High Speed Turbo Mode - Mouse 1+2 Held

### TTC Nihil unit (Pre and Post update)
WLMouse Beast X Mini TTC Nihil - SapphireOS 25H2 - 8Khz High Speed Turbo Mode - No Buttons Held 1.0.2.7R-1.0.2.3M
WLMouse Beast X Mini TTC Nihil - SapphireOS 25H2 - 8Khz High Speed Turbo Mode - Mouse 1 Held 1.0.2.7R-1.0.2.3M
WLMouse Beast X Mini TTC Nihil - SapphireOS 25H2 - 8Khz High Speed Turbo Mode - Mouse 1+2 Held 1.0.2.7R-1.0.2.3M

WLMouse Beast X Mini TTC Nihil - SapphireOS 25H2 - 8Khz High Speed Turbo Mode - No Buttons Held
WLMouse Beast X Mini TTC Nihil - SapphireOS 25H2 - 8Khz High Speed Turbo Mode - Mouse 1 Held
WLMouse Beast X Mini TTC Nihil - SapphireOS 25H2 - 8Khz High Speed Turbo Mode - Mouse 1+2 Held

### Methodology
All tests performed on a fully isolated xHCI usb controller after a fresh boot.
8k Receiver EMI Shielded within a copper insulated grounded Faraday cage to minimize interference.
Ultraglide Ice were used on a SP-004 with bare ESD strapped arms to prevent ESD muddying up the reported data.
Each initial test was isolated and the pad was wiped down with a Windex/water solution to minimize triboelectric buildup.
Sensor data measured at 95-100% battery level.
Firmware used:
	- 8k reciever: 1.0.2.7
	- Mouse: 1.0.2.7

Hope this helps - feel free to contact me at RileyF.dev@protonmail.com
