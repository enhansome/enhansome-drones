# Awesome Drones with stars

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) ⭐ 498,208 | 🐛 105 | 📅 2026-08-18

This is a list of various resources related to drones, UAV's and quadcopters. It's an attempt to gather useful material in one place for everybody who wants to learn more about the field.

## Legend

* :dollar: - Paid product
* :ghost: - Outdated or Inactive

## Table of Contents

* [Courses](#courses)
  * [Udemy](#udemy)
* [Software and Librairies](#software-and-librairies)
  * [Simulators](#simulators)
  * [Firmware for Transmitters](#firmware-for-transmitters)
  * [Firmware for Flight Controllers](#firmware-for-flight-controllers)
  * [Libraries](#libraries)
  * [Log Analysis](#log-analysis)
  * [Ground Control Stations](#ground-Control-Stations)
* [Services](#services)
* [Hardware and Components](#hardware-and-components)
  * [Platforms](#platforms)
  * [Remote Control Transmitters](#remote-control-transmitters)
  * [Drone Frames](#drone-frames)
  * [Headsets](#headsets)
  * [Video Receivers](#video-receivers)
  * [Electronics and Motors](#electronics-and-motors)
  * [Cameras](#cameras)
* [Products and Projects](#products-and-projects)
  * [Unmanned Aerial Vehicles](#unmanned-aerial-vehicles)
    * [Consumer](#consumer)
    * [Millitary](#millitary)
  * [Unmanned Ground Vehicles](#unmanned-ground-vehicles)
    * [Autonomous Ground Vehicles](#autonomous-ground-vehicles)
  * [Unmanned Underwater Vehicles](#unmanned-underwater-vehicles)
* [Visual Localization](#visual-localization)

## Courses

* [Flying Car and Autonomous Flight Engineer](https://eu.udacity.com/course/flying-car-nanodegree--nd787) Udacity - Master autonomous flight software engineering skills as you build your career in flying cars and drone robotics.
* [Robotics: Dynamics and Control](https://www.edx.org/course/robotics-dynamics-control-pennx-robo3x) edX - Learn how to develop dynamic models of robot manipulators, mobile robots, and drones (quadrotors).

### Udemy

* [UAS/Drone Remote Pilot Test Prep for Part 107](https://www.udemy.com/remote-pilot-certificate-test-prep-for-part-107-exam/) - :dollar: - A comprehensive class that encompasses everything needed to know to become a proficient Remote Pilot and to pass the FAA written initial or recurrent exam.
* [Drone Photography | Shoot Professional Photos With Any Drone](https://www.udemy.com/course/dronephotography/) - :dollar: - Your Complete Online Guide to Shooting Incredible Drone Photography Like a Professional
* [Drone Programming with Python - Face Recognition & Tracking](https://www.udemy.com/course/drone-programming-with-python-face-recognition-tracking/) - :dollar: - Operating drone with network programming, face recognition using OpenCV, automatic tracking, implementing web camera

## Software and Libraries

* [ArduPilot Mission Planner](https://github.com/ArduPilot/MissionPlanner) ⭐ 2,350 | 🐛 1,362 | 🌐 C# | 📅 2026-08-19 - Mission planner software.
* [FPVTune](https://github.com/chugzb/betaflight-pid-autotuning) ⭐ 6 | 🐛 1 | 📅 2026-02-16 - Betaflight blackbox log analysis and PID tuning guidance.
* [Paparazzi](http://wiki.paparazziuav.org/wiki/Main_Page) - Software suite for UAVs, including ground control and autopilot.
* [QGroundControl](http://qgroundcontrol.com/) - Ground Control Station for PX4 and ArduPilot based UAVs.
* [DroneRoute](https://droneroute.io) - Open-source web-based mission planner for DJI drones withKMZ export. Self-hostable.

### Simulators

* [AirSim](https://github.com/Microsoft/AirSim) ⭐ 18,413 | 🐛 780 | 🌐 C++ | 📅 2026-06-30 - Open source simulator based on Unreal Engine for autonomous vehicles.
* [Drone Racing Arcade](https://thedroneracingleague.com/arcade/) - Mobile based FPV racing game
* [DRL Drone Racing Simulator](https://thedroneracingleague.com/drlsim/) - FPV Racing game and simulator with official DRL tracks.
* [FPV Air 2](https://store.steampowered.com/app/889040/FPV_Air_2/) - :dollar: - Basic FPV simulator, runs on slower hardware. Available on Steam.
* [FPV Freerider](https://fpv-freerider.itch.io/fpv-freerider) - :dollar: FPV (first person view) and LOS (line of sight) racing simulator.
* [FPV Freerider Recharged](https://fpv-freerider.itch.io/fpv-freerider-recharged) - :dollar: FPV (first person view) and LOS (line of sight) racing simulator.
* [LiftOff](https://www.immersionrc.com/fpv-products/liftoff-drone-race-simulator/) - :dollar: FPV racing simulator with realistic OSD (on-screen display) experience.
* [Orqa FPV.SkyDive](https://skydive.orqafpv.com/) - Orqa FPV's racing and freestyle simulator.
* [Parrot Sphinx](https://developer.parrot.com/docs/sphinx/index.html) - Simulator for Parrot ANAFI with physics and sensor emulation using Unreal Engine and Gazebo.
* [RotorRush](http://rotorrush.com/) - :dollar: Formerly known as FPV Event. Subscription based simulator.
* [VelociDrone](https://www.velocidrone.com/) - :dollar: Multiplayer FPV racing simulator.

### Firmware for Transmitters

* [FreedomTX](https://github.com/tbs-fpv/freedomtx) ⭐ 70 | 🐛 20 | 🌐 C++ | 📅 2026-07-08 - Custom firmware for TBS Tango 2 based on OpenTX.
* [OpenTX](http://www.open-tx.org/) - Highly configurable open source firmware for RC radio transmitters.

### Firmware for Flight Controllers

* [Ardupilot](https://github.com/ArduPilot/ardupilot) ⭐ 15,714 | 🐛 3,148 | 🌐 C++ | 📅 2026-08-20
* [PX4 Autopilot](https://github.com/PX4/PX4-Autopilot) ⭐ 12,456 | 🐛 340 | 🌐 C++ | 📅 2026-08-20 - Rebranded to AutoPilot from Firmware
* [Betaflight](https://github.com/betaflight/betaflight) ⭐ 11,440 | 🐛 364 | 🌐 C | 📅 2026-08-20 - Fork of Cleanflight.
* [INAV](https://github.com/iNavFlight/inav) ⭐ 4,187 | 🐛 441 | 🌐 C | 📅 2026-08-20
* [Cleanflight](https://github.com/cleanflight/cleanflight) ⭐ 2,732 | 🐛 3 | 🌐 C | 📅 2023-10-20 - :ghost: Fork of BaseFlight. Supports more FCs and has additional PID contollers.
* [Open Source Rover Control Code](https://github.com/nasa-jpl/osr-rover-code) ⭐ 532 | 🐛 17 | 🌐 Python | 📅 2026-08-13 - Nasa JPL command firmware for the OSR.
* [BaseFlight](https://github.com/multiwii/baseflight) ⭐ 525 | 🐛 23 | 🌐 C | 📅 2016-01-18 - :ghost:
* [EmuFlight](https://github.com/emuflight/EmuFlight) ⭐ 504 | 🐛 53 | 🌐 C | 📅 2026-08-19 - FC Firmware focusing on flight performance, innovative filtering, leading-edge feature additions, and wide target support.
* [madflight](https://github.com/qqqlab/madflight) ⭐ 486 | 🐛 1 | 🌐 C | 📅 2026-08-20 - Flight controller for Arduino ESP32 / RP2350 / RP2040 / STM32.
* [LibrePilot](https://github.com/librepilot/LibrePilot) ⭐ 357 | 🐛 18 | 🌐 C | 📅 2023-12-14 - :ghost: (GitHub fork is Outdated/Inactive)
* [SilverWare(NFE)](https://github.com/NotFastEnuf/NFE_Silverware) ⭐ 124 | 🐛 10 | 🌐 C | 📅 2021-08-12 - :ghost: Firmware for Alienwhoop ZER0, E011, BWHOOP B-03, H8mini, and BETA FPV LITE flight controllers with NotFastEnuf settings and experimental features
* [ButterFlight](https://github.com/ButterFlight/butterflight) ⭐ 107 | 🐛 51 | 🌐 C | 📅 2019-08-08 - :ghost: Fork of Betaflight. Firmware focusing on Mini Quads.
* [SilverWare](https://github.com/silver13/BoldClash-BWHOOP-B-03) ⭐ 70 | 🐛 8 | 🌐 C | 📅 2020-03-03 - :ghost: Firmware for BoldClash BWHOOP B-03 mini drone
* [dRonin](https://dronin.org) - :ghost: Autopilot/flight controller firmware for controllers in the OpenPilot/Tau Labs family.
* [FalcoX](https://flightone.com/download.php?version=stable) - Formerly known as Raceflight one, FlightOne.
* [Kiss](https://www.flyduino.net/en_US/page/downloads) - Firmware for KISS FCs.

### Libraries

* [GoBot](https://github.com/hybridgroup/gobot) ⭐ 9,451 | 🐛 99 | 🌐 Go | 📅 2026-01-07 - Golang framework for robotics, drones, and the Internet of Things (IoT).
* [MAVLink](https://github.com/mavlink/mavlink) ⭐ 2,400 | 🐛 137 | 🌐 Python | 📅 2026-08-20 - Micro Air Vehicle Message Marshalling Library.
* [MAVROS](https://github.com/mavlink/mavros) ⭐ 1,212 | 🐛 410 | 🌐 C++ | 📅 2026-08-14 - MAVLink to ROS gateway with a proxy for Ground Control Station.
* [DJI Onboard SDK](https://github.com/dji-sdk/Onboard-SDK) ⭐ 988 | 🐛 77 | 🌐 C++ | 📅 2024-02-28 - The Onboard SDK allows you to connect to a supported DJI flight controller using a serial port (TTL UART).
* [Libcyphal](https://github.com/OpenCyphal-Garage/libcyphal) ⭐ 328 | 🐛 21 | 🌐 C++ | 📅 2025-12-17 - Portable reference implementation of the Cyphal protocol stack in C++ for embedded systems and Linux. Formerly known as LibUAVCAN.

### Log Analysis

* [SmartTune CLI](https://github.com/raylanlin/smarttune-cli) ⭐ 28 | 🐛 0 | 🌐 Python | 📅 2026-08-13 - Multi-platform flight log analysis & tuning advisor for ArduPilot, Betaflight and PX4. Offline-first, designed for AI agents.

### Ground Control Stations

* [QGroundControl](https://github.com/mavlink/qgroundcontrol) ⭐ 4,858 | 🐛 994 | 🌐 C++ | 📅 2026-08-20 - Cross-platform ground control station for drones (Android, iOS, Mac OS, Linux, Windows).
* [Tower](https://github.com/DroidPlanner/Tower) ⭐ 634 | 🐛 152 | 🌐 Java | 📅 2022-02-19 - :ghost: Ground Control Station for Android Devices.
* [Arduleader](https://github.com/geeksville/arduleader) ⭐ 142 | 🐛 135 | 🌐 Scala | 📅 2018-03-02 - :ghost: An android ground controller (and other things) for Mavlink/Arduplane.
* [Argus](https://github.com/L-X-Yao/argus) ⭐ 0 | 🐛 10 | 🌐 Python | 📅 2026-08-01 - Open-source web-based ground control station for MAVLink drones. Runs in any browser with WebSerial direct USB support. ArduPilot production-tested, 10 languages.
* [MAVProxy](http://ardupilot.github.io/MAVProxy/) - A UAV ground station software package for MAVLink based systems.
* [Ardupilot Mission Planner](https://ardupilot.org/planner/index.html) - A full-featured ground station application for the ArduPilot open source autopilot project.
* [APM Planner 2](https://ardupilot.org/planner2/) - An open-source ground station application for MAVlink based autopilots including APM and PX4/Pixhawk that can be run on Windows, Mac OSX, and Linux.

## Services

* [AirMap](https://www.airmap.com/) - Aeronautical data & services to unmanned aircraft.
* [DroneDeploy](https://www.dronedeploy.com/) - Drone & UAV Mapping Software.
* [FPVTune](https://fpvtune.com/) - Neural-network assistant for Betaflight PID tuning and FPV drone blackbox log analysis.
* [RotorBuilds](https://rotorbuilds.com/) - FPV Part lists and Build Logs.
* [Zeitiew](https://www.zeitview.com/) - Online marketplace for Drone services. Formerly known as DroneBase.
* [GrabaRobot](https://www.grabarobot.com/) - Compare agricultural and industrial drones from Chinese manufacturers (DJI, XAG, and more). Includes pricing index and ROI calculator.

## Hardware and Components

### Platforms

* [OpenUAV](https://openuav.eava.ee) - Open-souce UAV platform for research and development

### Remote Control Transmitters

* [FlySky](http://www.flyskyrc.com/) - Entry level transmitters.
* [FrSky](https://www.frsky-rc.com/) - Taranis and Horus line of transmitters powered by OpenTX firmware.
* [Futaba](https://www.futabarc.com)
* [Spektrum](https://www.spektrumrc.com)
* [Team Blacksheep](https://team-blacksheep.com) - Tango 1 and 2 transmitters.

### Drone Frames

* [Source One by TBS](https://github.com/tbs-trappy/source_one) ⭐ 630 | 🐛 25 | 📅 2025-09-17 - Open Source freestyle FPV drone frame.
* [Source Two by TBS](https://github.com/ps915/source_two) ⭐ 103 | 🐛 3 | 📅 2021-12-19 - Open Source racing FPV drone frame.
* [Source X by TBS](https://github.com/ps915/source_x) ⭐ 47 | 🐛 1 | 📅 2019-06-10 - Open Source giant racing drone frame.
* [Source PodRacer](https://github.com/ps915/source_podracer) ⭐ 40 | 🐛 1 | 📅 2020-07-18 - Open source ultra-light drone frame.
* [Source Micro by TBS](https://github.com/ps915/source_micro) ⭐ 38 | 🐛 1 | 📅 2020-01-07 - Open Source mini drone frame.
* [Source V by TBS](https://github.com/ps915/source_v) ⭐ 21 | 🐛 1 | 📅 2021-03-19 - Open Source ultra-stiff drone frame.

### Headsets

* [DJI Digital FPV System](https://www.dji.com/fpv/) - Low latency digital FPV goggles.
* [FatShark](https://www.fatshark.com) - Headsets praised by racers.
* [ORQA FPV.One](https://orqafpv.com) - Headsets and controllers

### Video Receivers

#### 1.3GHz

* [ClearView XLR 1.3](https://clearview-direct.com/product-category/ground-station-receivers/1-3-receivers/)

#### 2.4GHz

* [ClearView XLR 2.4](https://clearview-direct.com/product-category/ground-station-receivers/2-4-receivers/)
* [TBS Ground station](https://www.team-blacksheep.com/products/prod:tbs_gs_2g4)

#### 5.8GHz

* [ClearView Goggle Receiver](https://clearview-direct.com/shop/clearview-goggle-products/clearview-goggle-module/)
* [ClearView 5.8GHz Ground Station Receivers](https://clearview-direct.com/product-category/ground-station-receivers/5-8-receivers/)
* [rapidFIRE](https://www.immersionrc.com/fpv-products/rapidfire/)
* [TBS Fusion](https://www.team-blacksheep.com/products/prod:tbs_fusion) - Has CRSF integration (for changing channels).

### Electronics and Motors

Terminology:

* FC = Flight Controller
* ESC = Electronic Speed Controller
* PDB = Power Distribution Board
* RX = Receivers
* TX = Transmitters (external)
* VRX = Video Receiver
* VTX = Video Transmitter

List:

* [3BHobby](https://www.3bhobby.com) - Motors
* [Airbot](https://store.myairbot.com/flight-controller.html) - FC, ESC
* [BrotherHobby](https://www.brotherhobbystore.com) - Motors
* [ClearView](https://clearview-direct.com/) - VRX, VTX
* [DalProp](http://dalprop.com) - Props
* [Diatone](https://www.diatone.us/) - FC, ESC, VTX, Motors
* [Fl1ghtOne](https://flightone.com) - FC, ESC
* [Flyduino](https://www.flyduino.net/en_US/) - FC, ESC
* [GemFan](https://www.gfprops.com/) - Props
* [Hobbywing](http://www.hobbywing.com) - FC, ESC, Motors
* [Holybro](http://www.holybro.com) - FC, ESC, PDB
* [HQProp](http://www.hqprop.com) - Props
* [iFlight](https://www.iflight-rc.com) - Motors
* [Lumenier](https://www.lumenier.com) - FC, ESC, PDB, VTX, Motors
* [MatekSys](http://www.mateksys.com) - FC, PDB, VTX
* [RacerStar](https://www.racerstar.com) - FC, ESC, Motors
* [SP Racing](http://seriouslypro.com) - FC
* [T-Motor](http://www.tmotor.com) - FC, Motors
* [Team Blacksheep](https://www.team-blacksheep.com) - ESC, RX, TX, VRX, VTX

### Cameras

* [Caddx.us](https://caddxfpv.com/)
* [DJI O3 Air unit](https://www.dji.com/ee/o3-air-unit) - Camera with digital video transmission
* [Foxeer](http://www.foxeer.com)
* [RunCam](https://runcam.com)

## Products and Projects

### Unmanned Aerial Vehicles

#### Consumer

* [Autel](https://www.autelpilot.eu/) - :cn: - Compact EVO series drones, alternative to DJI Mavic series. Dragonfish series fixed-wing UAVs coming soon.
* [DJI](https://www.dji.com/) - :cn: - DJI is the world's leader in the consumer drone market - Mavic, Phantom, Inspire and Matrice series drones.
* [Eachine](https://www.eachine.com/) - :cn: - Mini and micro drones. FPV beginners sets.
* [Hubsan](https://www.hubsan.com/na/) - :cn: - Micro and Mini lower cost drones.
* [Parrot SA](https://www.parrot.com/global/) - :fr: - Famously Parrot Bebop and Parrot AR series drones.
* [Syma](http://www.symatoys.com/) - :cn: - RC toy quadcopters.
* [Yuneec International](https://www.yuneec.com/) - :cn: - Yuneec camera drones.

#### Military

* [AeroVironment](https://www.avinc.com/) - Small range fixed-wing UAVs.
* [Baykar](https://www.baykartech.com/en/) - Bayraktar series battle- proven long-range fixed-wing UAVs.
* [Eli](http://www.uav.ee/) - Pneumatic launchers for fixed wing UAVs.
* [INSITU](https://www.insitu.com/) - Long-range and extended endurance fixed-wing UAVs.
* [Threod Systems](http://threod.com/) - Fixed-wing and multi-rotor UAVs.

### Unmanned Ground Vehicles

#### Autonomous Ground Vehicles

* [JPL Open Source Rover](https://github.com/nasa-jpl/open-source-rover) ⭐ 9,591 | 🐛 18 | 🌐 Prolog | 📅 2026-08-13 - Nasa JPL scaled down version of the curiosity rover, made of COTS.
* [Turtlebot](https://www.turtlebot.com) - Open sourced UGV, [ROS](http://www.ros.org/) standard platform.

### Unmanned Underwater Vehicles

* [Geneinno](https://www.geneinno.com/) - Underwater drones.

## Visual Localization

* [Drone-Satellite-Ground Three Platiform Localization](https://github.com/layumi/University1652-Baseline) ⭐ 673 | 🐛 34 | 🌐 Python | 📅 2026-08-10
* [Visual Localization Leaderboard](https://github.com/layumi/University1652-Baseline/tree/master/State-of-the-art) ⭐ 673 | 🐛 34 | 🌐 Python | 📅 2026-08-10
* [ACM MM2023 Workshop: UAV in Multimedia](https://www.zdzheng.xyz/ACMMM2023Workshop/)

## License

[![CC0][CC0-badge]](LICENSE)

To the extent possible under law, [Jaan Janesmae](https://jaan.janesmae.com) has waived all copyright and related or neighbouring rights to this work.

[CC0-badge]: http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-20._
