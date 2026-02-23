<h1 align="center">ThorRR</h1>

<p align="center">
 <a href="https://creativecommons.org/licenses/by-sa/4.0/legalcode">
     <img src="https://img.shields.io/github/license/angellm/Thor">
 </a>
 <a href="https://discord.com/invite/a5dSVqSUK5">
     <img src="https://img.shields.io/discord/1189278202514907166?label=discord&logo=discord">
 </a>
</p>

<p align="center">
 <em><b>ThorRR</b> is a fork of the open-source <a href="https://github.com/AngelLM/Thor">Thor</a> robotic arm with a fully working <b>RepRapFirmware (RRF)</b> setup, modified parts, and optical endstops. The original Thor listed RRF as supported but the implementation was incomplete and undocumented. ThorRR picks up where that left off with a tested configuration, redesigned parts, and an updated BOM.</em>
</p>
<p align="center">
 <img src="doc/banner.png" width="800">
</p>

## What's Different from Thor?

The original Thor mentioned RepRapFirmware support, but in practice the RRF configuration was incomplete, undocumented, and not usable out of the box. ThorRR fixes that and makes several other changes:

**Firmware & Electronics**
- Fully working, tested RepRapFirmware configuration
- Replaces the Arduino Mega + GRBL setup with a single RRF-compatible board
- Web interface (Duet Web Control) for jogging, configuration, and macros

**Modified Parts**
- Optical endstops instead of mechanical switches
- Redesigned base
- Several parts resized for better fit and printability

**Updated BOM**
- Some components differ from the original Thor bill of materials to accommodate the above changes

## ✨ Key Features

- 🧩 **Open Source**: Built on open source software — FreeCAD, KiCAD, RepRapFirmware, and ROS.
- 🕊️ **CC-BY-SA-4.0 Licensed**: All source files published under the same license as the original Thor.
- 💰 **Low Cost**: Hardware cost below 350€.
- 📚 **Suitable for Education**: Perfect for robotics courses in schools and universities.
- 🧰 **Actually Working RRF Support**: A tested RepRapFirmware configuration — not just listed as supported.
- 🐳 **ROS2 Integration**: Available implementation using Docker for flexibility.


## 📦 Repository Structure
- `freecad-src` – Source files of 3D models created with FreeCAD
- `mods` – Modified models and improvements to standard models
- `stl` – Printable STL files
- `step` – STEP files


## 🔗 Related Repositories
- [**Thor (original)**](https://github.com/AngelLM/Thor): The original Thor project by AngelLM that this fork is based on.
- [**Thor-ROS**](https://github.com/AngelLM/Thor-ROS): ROS2 & Moveit2 configuration files and packages to work with Thor.
- [**ThorControlPCB**](https://github.com/AngelLM/ThorControlPCB): Source & manufacture files of Arduino Mega shield designed for the original Thor.
- [**Asgard**](https://github.com/AngelLM/Asgard): Control software for Thor motors with a simple interface (original Thor).



## 🚀 Getting Started

1. **Read the Documentation**: Comprehensive guides on printing, assembly, electronics, and firmware are available at [thor.angel-lm.com/documentation](http://thor.angel-lm.com/documentation/).
2. **Print the Parts**: Use the STL files in this repository.
3. **Get the Hardware**: Take a look to the [Bill of Materials](http://thor.angel-lm.com/documentation/bom/).
4. **Assemble the Robot**: See [here](http://thor.angel-lm.com/documentation/assembly/) for assembly videos and interactive instructions. 
5. **Assemble & Setup the Electronics**: The [Wiring & Setup](http://thor.angel-lm.com/documentation/electronics/) guide will help you prepare your electronic board and make the hardware connections. 
6. **Install the Firmware**: Depending on which electronics you have chosen, you will have to perform a different firmware configuration. [This page](http://thor.angel-lm.com/documentation/firmware/) explains the steps to follow.
7. **Control the Robot**: Use Asgard to move the robot. [Here](http://thor.angel-lm.com/documentation/control-software/) is how to do it.



## 🧠 Technical Specifications

- **Degrees of Freedom**: 6 (yaw-roll-roll-yaw-roll-yaw).
- **Height Stretched**: 625mm (without end effector).
- **Payload Capacity**: 750g max (including end effector weight).
- **Motors**: Stepper motors.
- **Electronics**: RepRapFirmware-compatible board.
- **Transmission**: 3D printed gears, GT2 pulleys and belts.
- **Software**: FreeCAD, KiCAD, RepRapFirmware, ROS2.



## 📚 Additional Resources

- 🌐 **Official Website**: [thor.angel-lm.com](http://thor.angel-lm.com/)
- ❓ **Frequently Asked Questions**: [FAQ](http://thor.angel-lm.com/faq/)
- 💬 **Thor Community Forums**: [Thor Forums](http://thor.angel-lm.com/forums/)
- 💬 **Thor Discord Server**: [Thor Robot Community](https://discord.com/invite/a5dSVqSUK5)



## 🤝 Contributing

Contributions are welcome! If you'd like to improve ThorRR — whether it's design, documentation, or code — feel free to open an Issue or submit a Pull Request.



## 📜 License

ThorRR is licensed under the [Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/legalcode), the same license as the original Thor project. You’re free to use, modify, and distribute this project under its terms.



## 🎥 Videos

[![Watch on YouTube](https://img.youtube.com/vi/F2CDeHrFr2k/0.jpg)](https://www.youtube.com/watch?v=F2CDeHrFr2k)

[![Watch on YouTube](https://img.youtube.com/vi/e0BGN1eIjiI/0.jpg)](https://www.youtube.com/watch?v=e0BGN1eIjiI)

[![Watch on YouTube](https://img.youtube.com/vi/nDCN46trJvs/0.jpg)](https://www.youtube.com/watch?v=nDCN46trJvs)
