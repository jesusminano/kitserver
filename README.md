# Introduction

Kitserver is a companion program for Pro Evolution Soccer 2013.

# How to build

Visual Studio: This project is developed and tested using Visual Studio 2026.
Other Visual Studio versions with CMake integration may also work, but have not been tested.

Prerequisites


    - Install the "Desktop development with C++" workload in Visual Studio.
    - Make sure "C++ CMake tools for Windows" is selected in the Installer.



Build steps


    - Open the project folder with Visual Studio.
    - Set x86-release build type.
    - Configure, build & install kitserver.



Visual Studio code: The VS Code workflow has been tested using Visual Studio Build Tools 2026.
Other configurations may also work, but have not been tested.

Prerequisites


    - Install the "Desktop development with C++" workload in VS Build Tools.
    - Make sure "C++ CMake tools for Windows" is selected in the Installer.
    - Install the CMake Tools extension in VS Code.



Build steps


    - Open the project folder with Visual Studio Code.
    - Run "CMake: Select a Kit" and select "Visual Studio 2026 Build Tools Release: x86".
    - Run "CMake: Select Variant" and select "Release".
    - Build & install kitserver.



Dont forget include "resources" content and "doc" folder in your releases.

