---
title: Harmony 3 Graphics Package
nav_order: 1
---

# ![Microchip Technology](docs/images/mhgs.png) MPLAB® Harmony 3 Graphics Support Package

Examples and Demonstrations

### Table of Contents

-   [Overview](#autotoc_md44)
-   [General Naming Principles](#autotoc_md45)
    -   [Project Folder](#autotoc_md46)
    -   [Project Name:](#autotoc_md47)
    -   [Harmony Config Name:](#autotoc_md48)

Overview
--------

Every MPLAB Harmony Graphics Suite release contains a set of examples that demonstrates its software which run on Microchip graphics kits. The applications are best practices meant to be either a quickstart solution, demonstration of features, or a signature UI illustrations. These apps provide functionality that customers can use immediately in their solution.

General Naming Principles
-------------------------

The primary goal of the graphics configuration naming convention is to be descriptive and brief.

Application project names which includes the project folder, project name, and configuration files adhere to the following "\_" delimited attribute naming convention:

### Project Folder

Project folders could be either a MPLABX (.X) or IAR Embedded Workbench (.eww).

\<*gfx-library*\>\_\<*abbr-app name*\>\_\<*mcu*\>\_\<*abbr-dev-board*\>\_\<*display*\>\_\<*opt-desc*\>

### Project Name:

\<*gfx-library*\>\_\<*full-app-name*\>\_\<*mcu*\>\_\<*dev-board*\>\_\<*display-resolution*\>\_\<*opt-desc*\>

### Harmony Config Name:

\<*display-driver*\>\_\<*color-mode*\>\_\<*touch-driver*\>\_\<*opt-desc*\>

The following list contain attributes and possible values:

|Attribute|Value|
|:--------|:----|
|gfx\_library|aria, legato|
|full-app-name|quickstart, showcase, benchmark, radial\_menu|
|abbr-app-name|qs, sc, bm, rm|
|mcu|mzda, mzef, c21, d21, e54, e70, a5d2, 9x60|
|dev-board|meb2, xult, xpro, cult, sk|
|opt-desc|tm4301b, tm5000, wvga, wqvga, ssd1963, spi, parallel, freertos, intddr, extddr|
|color-mode|rgba8888, rgb888, rgb565|

[Legato Applications](LegatoApplications.html) [Blank Applications](BlankApplications.html)

* * * * *

Generated by  [![doxygen](doxygen.png)](http://www.doxygen.org/index.html) 1.8.18