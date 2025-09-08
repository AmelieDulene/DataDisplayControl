# DataDisplayControl
A customizable control for displaying labels and values with adjustable colors and borders.

## Overview

The **DataDisplayControl** is a UI component designed to simplify the display of information such as system statistics, drive status, or sensor data. The control is available in two versions:

* **For classic .NET Framework:** A version compatible with **.NET Framework 4.8**.
* **For modern .NET:** A version based on **.NET 8**.

Both versions are available as NuGet packages and can be easily integrated into your projects.

## Installation

### NuGet package

To use the control in your project, install the corresponding NuGet package via the NuGet Package Manager in Visual Studio or the .NET CLI.

The different version numbers between .NET 4.8 (version 1.0.0.1) and .NET 8 (version 3.0.1.4) arose from my development approach: 
I originally developed the project for .NET 8 and was able to expand on various ideas, fix minor bugs, and implement improvements there. 
It was then relatively easy to port the project to .NET 4.8. However, the further developments and bug fixes from the .NET 8 version were omitted in the .NET 4.8 version, which is why it was given a lower version number.
