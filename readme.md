_This entire project is currently a WIP by a single person, I aim to have a High-Power (12-24V @ 10A) and a Mid Power (6-24V @ 3.6A) version completely done by the end of the year 2024._

_**Really** open to contributors._

_If time allows I will also make a stacked low-power version specifially for MicroDCs_

**PowerServo AE**

PowerServo AE is an open-source platform designed to effortlessly transform any DC motor into a smart servo with **high precision** and control. Built to provide **high-torque**, **high-RPM**, and accurate positioning through absolute encoding, PowerServo AE is a modular solution for hobbyists, roboticists, and makers. The platform allows users to easily drop in a PowerServo AE controller onto a brushed DC motor, turning it into a powerful and precise smart servo, regardless of the motor's size or specifications.

**Project Overview**

The platform aims to support several variations, including options for high-power, low-power, high-voltage, and low-voltage setups. Each variation is designed to accommodate different performance requirements while maintaining the core features of precise motion control and absolute position feedback.

**Core Features**
- Plug and Play: With minimal considerations for design, it is ready to be strapped on the back of any **extended axis/shaft, with magnet** BRUSHED Dc Motor and turn it into a Smart Servo Motor
- Absolute Encoder: PowerServo AE uses magnetic absolute encoders for precise positioning and reliable feedback, eliminating the need for homing or recalibration after power loss.
- Modular Design: Multiple configurations allow for flexibility across a wide range of applications, from lightweight robotics to heavy-duty industrial tasks.
- Open-Source: Both hardware and software are fully open-source, allowing anyone to contribute, modify, and improve the platform.
- Compact Size: The designs are optimized for compactness, with some controllers as small as 12 mm in diameter, making them suitable for space-constrained applications.

**Getting Started**

Clone the Repository:

```git clone https://github.com/Alex-C-EE/PowerServo-AE.git```

**Build Your Own:**

- Design files (PCB, schematics) are provided in each version's hardware directory. Design files are in KiCad 8.0 format.
- Code (C, STM32) is provided in each version's software directory.
- GERBERS and BOMs are also provided ready to upload to JLCPCB.

**Documentation**
_WIP, planned control: CAN, UART, PWM_

**Contributing**
We welcome contributions to the PowerServo AE project! Whether you want to improve the hardware, add new features to the firmware, or suggest new variations, feel free to contribute through:

- Issues and Pull Requests on GitHub
- Community discussions in our Discord channel

**License**
- Hardware: Licensed under the CERN Open Hardware License.
- Software: Licensed under the MIT License.

**Join the Community**
_WIP_
Stay updated with the latest developments, tutorials, and community projects:

Follow on Hackaday.io
Join the discussion on Discord
Watch video tutorials and project demos on YouTube

**Similar Projects (and source of inspiration)**
Mechduino: Similar, but for Steppers specifically
https://hackaday.io/project/11224-mechaduino

MotCTRL: Similar, but for Brushless speficially
https://github.com/osannolik/MotCtrl
