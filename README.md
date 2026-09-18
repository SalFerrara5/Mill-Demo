# Mill Demo

A Unity-based mill simulation and demonstration project.

## Overview

**Mill Demo** is an interactive 3D Unity project developed as a demonstration of a manufacturing/milling environment. The project provides a foundation for visualizing a mill operation and can be expanded with additional equipment, processes, automation, and interactive elements.

The project is built using **Unity 6** and the Universal Render Pipeline (URP).

## Features

* 3D mill/manufacturing environment
* Unity Universal Render Pipeline
* Unity Input System
* AI Navigation support
* Timeline support for animations and sequences
* Unity UI support
* Physics and vehicle system support
* Visual Scripting support
* Modular Unity project structure for continued development

## Requirements

### Software

* **Unity 6.0.0**
* Unity Editor version **6000.0.79f1**
* Windows, macOS, or Linux capable of running Unity 6
* Git, if cloning the repository directly

The project was created with:

```text
Unity 6000.0.79f1
```

## Getting Started

### 1. Clone the Repository

Clone the repository using Git:

```bash
git clone https://github.com/SalFerrara5/Mill-Demo.git
```

Then enter the project directory:

```bash
cd Mill-Demo
```

### 2. Open the Project in Unity

Open **Unity Hub** and select:

```text
Add > Add project from disk
```

Select the cloned `Mill-Demo` folder.

Unity should recognize the project automatically and use the version specified by the project settings.

### 3. Open the Project

Open the project in:

```text
Unity 6000.0.79f1
```

Allow Unity to import and compile the project assets. The first launch may take some time while Unity generates its local `Library` data.

### 4. Run the Demo

Once the project has finished importing:

1. Open the appropriate scene from the `Assets` folder.
2. Press **Play** in the Unity Editor.
3. Interact with the simulation using the configured input controls.

## Project Structure

```text
Mill-Demo/
├── Assets/
│   └── Project assets, scenes, scripts, models, materials, etc.
│
├── Packages/
│   └── Unity package dependencies
│
├── ProjectSettings/
│   └── Unity project configuration
│
├── .vscode/
│   └── Visual Studio Code configuration
│
├── .gitignore
├── .gitattributes
└── Mill Demo.slnx
```

## Unity Packages

The project currently uses several Unity packages, including:

* **Universal Render Pipeline**
* **Input System**
* **AI Navigation**
* **Timeline**
* **Unity UI**
* **Visual Scripting**
* **Unity Test Framework**
* **Multiplayer Center**

The project also includes the standard Unity modules for animation, audio, physics, terrain, video, XR, and other Unity functionality.

## Development

When developing the project, it is recommended to use the same Unity version as the project:

```text
Unity 6000.0.79f1
```

Using a different Unity version may cause package, serialization, rendering, or project compatibility issues.

### Recommended Workflow

1. Pull the latest changes from Git.
2. Open the project using the specified Unity version.
3. Make changes inside the `Assets` directory.
4. Test the project in the Unity Editor.
5. Save modified scenes and assets.
6. Commit the changes to Git.

Example:

```bash
git pull
git add .
git commit -m "Describe your changes"
git push
```

## Version Control

The repository is configured as a Unity project and uses Git for version control.

Generated Unity folders such as the following should generally not be committed:

```text
Library/
Temp/
Obj/
Build/
Builds/
Logs/
UserSettings/
```

These are generated locally by Unity and can be recreated when the project is opened.

## Current Project Status

This repository is currently intended as a **demo/development project** rather than a finished production application.

The project can be used as a starting point for:

* Mill process visualization
* Manufacturing demonstrations
* Equipment interaction
* Automation concepts
* Training demonstrations
* Future simulation features

## Future Development

Potential future additions include:

* Interactive machine controls
* Automated mill processes
* Equipment status monitoring
* Production counters
* Machine animations
* Material flow visualization
* Operator interfaces
* Fault and alarm simulation
* Improved environment and lighting
* Additional manufacturing equipment
* Data logging and reporting

## License

No license has currently been specified for this repository.

Unless a license is added, the repository should be treated as **all rights reserved**.

## Author

**Sal Ferrara**

GitHub:
https://github.com/SalFerrara5

## Repository

https://github.com/SalFerrara5/Mill-Demo
