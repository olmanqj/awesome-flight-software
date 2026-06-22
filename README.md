# Awesome Flight-Software

This is a list of **open-source** flight software frameworks, and other resources, that I have found across the years.
If you are aware of any flight-software framework or resource that is not listed here, please open an 
issue or submit a pull request.



## Frameworks

## List of Flight-Software Frameworks


| Framework                                                                 | Main Developer                       | Scope                                                   | Impl. Language         | License         | 
| ------------------------------------------------------------------------- | -------------------------------------| ------------------------------------------------------- | ---------------------- | ----------------|
| [core Flight System](https://github.com/nasa/cFS)                         | NASA                                 | HAL, OSAL, Middleware, Component Framework, Services    | C                      | Apache 2.0      |
| [F Prime (F´)](https://github.com/nasa/fprime)                            | NASA JPL                             | Component Framework, Middleware, Services               | C++                    | Apache 2.0      |
| [RODOS](https://gitlab.com/rodos/rodos)                                   | University of Würzburg               | RTOS, Middleware                                        | C++                    | GPLv3           |
| [NanoSat MO Framework](https://github.com/esa/nmf-mission-ops-sat)        | ESA                                  | Component Framework, Middleware, Services               | Java                   | ESA Open Source |
| [CubedOS](https://github.com/cubesatlab/cubedos)                          | Vermont State University             | Component Framework, Middleware, Services               | SPARK Ada              | GPLv3           |
| [Outpost](https://github.com/DLR-RY/outpost-core)                         | DLR                                  | Middleware, Services                                    | C++                    | MPL-2.0         |
| [Flight Software Framework](https://egit.irs.uni-stuttgart.de/fsfw/fsfw)  | University of Stuttgart              | OSAL, Middleware, Services                              | C++                    | Apache 2.0      |
| [sat-rs](https://egit.irs.uni-stuttgart.de/rust/sat-rs)                   | University of Stuttgart              | Middleware, Services                                    | Rust                   | Apache 2.0      |
| [Adamant](https://github.com/lasp/adamant)                                | LASP University of Colorado Boulder  | Middleware, Component Framework, Services               | SPARK Ada              | Apache 2.0      |
| [Space ROS](https://github.com/space-ros/space-ros)                       | NASA and Blue Origin                 | Middleware, Component Framework, Services               | C++ / Python           | Apache  2.0     |
| Kobos [1](https://github.com/neo4reo/kubos)[2](https://github.com/xbai9225/kubos/) 💀| KubOS Corporation         |                                                         | C / Rust              | Apache  2.0      |

where: 
- HAL: Provides a Hardware Abstraction Layer.
- OSAL: Provides an Operating System Abstraction Layer.
- RTOS/OS: Provides the Operating System.
- Middleware: Provides middleware for inter-process/inter-component communication.
- Component Framework: Defines how components should be implemented and how they interact and behave.
- Services: Provides reusable services, typically built on top of the component framework.
- 💀 Apparently project have gone defunct :,(


### Template Flight-Software
These projects do not qualify as frameworks but still provide generic flight software that can be used as a foundation 
for developing flight-software systems.

| Project                                                                   | Main Developer                       | Impl. Language         | License         | 
| ------------------------------------------------------------------------- | -------------------------------------|  --------------------- | ----------------|
| [SUCHAI-Flight-Software](https://gitlab.com/spel-uchile/flight-software/suchai-flight-software-v2) | University of Chile | C              | Apache 2.0      |
| [Cononut Flight Software](https://github.com/ASU-SDSL/coconut-fsw) | Arizona State University | C              | MIT      |




### Educational Frameworks
Projects developed for educational purposes.

| Project                            | Main Developer                      | Impl. Language         | License         |
| ---------------------------------- | ------------------------------------|------------------------|-----------------|
| [SmallSat Flight Software Framework](https://github.com/olmanqj/sfsf)     | SETEC Costa Rica Institute of Technology  | C                      | MIT |
| [PyCubed](https://github.com/pycubed/software)                            | PyCubed Project                           | Python / CircuitPython | MIT |





## Reference Architectures

A list of reference architectures, in other words descriptions of how flight software architecture should be designed 
according to a particular organization, something like a blueprint.

- [ESA's SAVOIR](https://savoir.estec.esa.int/SAVOIROutput.htm) (Required to be in a ESA member state to access documentation 👎)
- [CCSDS CAST](https://ccsds.org/Pubs/811.1o1e1.pdf)



## Operating Systems
A list of open-source operating systems commonly used to host flight-software.

| Operating System                                           | Scope                                                            | Real-Time                              | License                                  | Impl. Language |
| ---------------------------------------------------------- | ---------------------------------------------------------------- | -------------------------------------- | ---------------------------------------- | ----------------------- |
| [FreeRTOS](https://github.com/FreeRTOS/FreeRTOS)           | Lightweight real-time operating system for embedded              | Yes                                    | MIT License                              | C                       |
| [RTEMS](https://gitlab.rtems.org/rtems/rtos/rtems)         | Real-time operating system for safety-critical and embedded      | Yes                                    | Apache-2.0 (mixed permissive components) | C                       |
| [RODOS](https://gitlab.com/rodos/rodos)                    | Distributed real-time operating system                           | Yes                                    | GPLv3                                    | C++                     |
| [Linux](https://github.com/torvalds/linux)                 | General-purpose operating system                                 | Not by default (with PREEMPT_RT patch) | GPLv2                                    | C                       |
| [Zephyr](https://github.com/zephyrproject-rtos/zephyr)     | Real-time operating system for embedded and IoT                  | Yes                                    | Apache-2.0                               | C                       |
| [RACCOON OS](https://gitlab.com/rccn/raccoon-os)     | RACCOON OS is a distribution of Linux based on the Yocto Project intended for space applications                  | No                                    | GNU General Public License v3.0 or later                               | BitBake                       |



## Organizations
Organizations involved in developing open-source flight-software projects, providing a wide range of useful libraries, 
tools, and other resources.

- [LibreCube](https://librecube.org)
  - [Repos](https://gitlab.com/librecube)
- [LibreSpace](https://www.libre.space/)
  - [Repos](https://gitlab.com/librespacefoundation)


## Publications

Publications which also survey flight software frameworks.

- [Development of a flight software framework for student CubeSat missions](https://doi.org/10.18845/tm.v32i8.4992)
- [A Comparative Survey on Flight Software Frameworks for ‘New Space’ Nanosatellite Missions](https://doi.org/10.5028/jatm.v11.1081)
- [Design and implementation of a framework for spacecraft flight software](http://dx.doi.org/10.18419/opus-11205)
