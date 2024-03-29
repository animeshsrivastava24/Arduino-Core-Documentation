![](https://img.shields.io/badge/Arduino%20Core-Documentation-brightgreen.svg) ![](https://img.shields.io/badge/Documentation-In%20Process-brightgreen.svg)
# Arduino-Core-Documentation
The repository is created to provide necessary documentation for the Arduino Cores.


## Description 
The [Wiki](https://github.com/animeshsrivastava24/Arduino-Core-Documentation/wiki) of the Repository is dedicated to the Documentation. Please refer to the Table of Contents below for more detailed information.

## Table of Contents

1. [Introduction to Arduino Core](https://github.com/animeshsrivastava24/Arduino-Core-Documentation/wiki/1.-Introduction-to-Arduino-Core)

2. [Introduction to Source files and the Building Process](https://github.com/animeshsrivastava24/Arduino-Core-Documentation/wiki/2.-Introduction-to-Source-files-and-the-Building-Process.)
   1. [General Source Files](https://github.com/animeshsrivastava24/Arduino-Core-Documentation/wiki/2.-Introduction-to-Source-files-and-the-Building-Process./_edit#general-source-files)
   2. [Port-related Source Files](https://github.com/animeshsrivastava24/Arduino-Core-Documentation/wiki/2.-Introduction-to-Source-files-and-the-Building-Process./_edit#port-related-source-files)
       * [Digital Port Source File](https://github.com/animeshsrivastava24/Arduino-Core-Documentation/wiki/2.-Introduction-to-Source-files-and-the-Building-Process./_edit#1digital-port-source-file)
       * [Analog Port Source File](https://github.com/animeshsrivastava24/Arduino-Core-Documentation/wiki/2.-Introduction-to-Source-files-and-the-Building-Process./_edit#2analog-port-source-file)
       * [Other Port Related Files](https://github.com/animeshsrivastava24/Arduino-Core-Documentation/wiki/2.-Introduction-to-Source-files-and-the-Building-Process./_edit#3other-port-related-files)
   3. [Timers/Timing Source Files](https://github.com/animeshsrivastava24/Arduino-Core-Documentation/wiki/2.-Introduction-to-Source-files-and-the-Building-Process./_edit#timerstiming-source-files)
   4. [Hardware Serial Source Files](https://github.com/animeshsrivastava24/Arduino-Core-Documentation/wiki/2.-Introduction-to-Source-files-and-the-Building-Process./_edit#hardware-serial-source-files)
   5. [Wiring-related Source Files](https://github.com/animeshsrivastava24/Arduino-Core-Documentation/wiki/2.-Introduction-to-Source-files-and-the-Building-Process./_edit#wiring-related-source-files)
   6. [Others](https://github.com/animeshsrivastava24/Arduino-Core-Documentation/wiki/2.-Introduction-to-Source-files-and-the-Building-Process./_edit#others)

3. Custom Core Design JSON File Creation

4. Architecture Configuration File: Description
* platform.txt
* boards.txt
* programmers.txt.

5. Building Process: Steps and Workflow
* Compilation
* Core Archive File Creation
* Linking Process
* Hex File Generation
* Binary Sketch Computation
* Preprocessing

6. Arduino Core Testing
* Online Method - JSON Url Creation.
* Offline Method - Addition of Arduino Core to the IDE.

Please refer to [https://github.com/arduino/Arduino/wiki/Arduino-IDE-1.5-3rd-party-Hardware-specification](https://github.com/arduino/Arduino/wiki/Arduino-IDE-1.5-3rd-party-Hardware-specification) for more details.
   
## Contributing
Excerpt from [Arduino Season of Docs Page](https://github.com/arduino/season-of-docs/blob/master/IDEAS.md#document-arduino-cores)
> Document Arduino cores

> How are Arduino cores done, and how to make them your own is something that we cover in a slightly superficial way on the Arduino website. We have increased the number of cores we have in our ecosystem over the years, but there is still little about the philosophy of why they are made the way they are. It would be interesting to have some documentation made on this topic, also for our own hardware architects to-be to understand what makes a board an Arduino one.
