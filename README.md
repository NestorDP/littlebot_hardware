# littlebot_hardware
Littlebot hardware project
# Littlebot Hardware

The `littlebot_hardware` repository contains the hardware design resources for the Littlebot differential-drive robot.

The repository is intended to maintain the electronic and physical hardware designs, including schematics, PCB layouts, component information, and supporting engineering documentation.

The electronic design files are developed using **KiCad**.

> **Development status:** The hardware design is currently under development. The committed KiCad project contains an initial schematic with generic connector symbols. Electrical connections, component selection, footprints, and PCB layout are not yet finalized.

## Hardware Design Objectives

The hardware subsystem is responsible for providing the physical and electrical infrastructure required by the Littlebot robot.

The design activities include:

- Electronic interfaces for the robot's embedded controller.
- Motor and encoder connections.
- Power distribution and electrical protection.
- Communication and peripheral interfaces.
- PCB design and component integration.
- Mechanical and physical integration with the robot platform.

These are design objectives; the final implementation and specifications will be documented as the hardware design progresses.

## Design Tools

The electronic design files are developed with:

- **KiCad 9.0** — schematic capture and PCB design.

Open the project by launching KiCad and opening:

```text
littlebot/littlebot.kicad_pro
```

The project directory contains:

| File | Description |
|---|---|
| `littlebot.kicad_pro` | KiCad project configuration. |
| `littlebot.kicad_sch` | Electronic schematic. |
| `littlebot.kicad_pcb` | PCB layout. |



## Contributing

Contributions to the hardware design and its documentation are welcome.

Please follow the project contribution guidelines when proposing changes.

## License

This project is distributed under the GNU General Public License v3.0. See [LICENSE](LICENSE) for details.