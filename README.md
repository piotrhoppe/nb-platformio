NetBeans Plugin for PlatformIO
==============================

> [!NOTE]
> This plugin is based on [nbpio](https://github.com/gholdys/nbpio), which is no longer maintained by its original author.

NB PlatformIO is a suite of plugins for [NetBeans](https://netbeans.apache.org) that provides integration with [PlatformIO](https://platformio.org). It consists of two main plugins:

- **PlatformIO Project** — provides a project wizard for PlatformIO projects.
- **SerialMonitor** — provides a serial monitor within the IDE.
 
## Support the project

If you find this project useful, please consider supporting it.

Your support helps cover the time and effort involved in keeping the project available and maintaining its repository.

Every contribution is greatly appreciated. Thank you for supporting open-source software!

[![Sponsor](https://img.shields.io/badge/Sponsor-support%20the%20project-ea4aaa?logo=github)](https://github.com/sponsors/piotrhoppe)

## Quickstart

First, make sure that [PlatformIO CLI](https://docs.platformio.org/en/latest/core/quickstart.html) is installed on your system. For installation instructions, see the official [documentation](https://docs.platformio.org/).

Once PlatformIO is installed, you can start using the NB PlatformIO plugin suite.
Install the **PlatformIO Project** and **SerialMonitor** plugins.

Then follow these steps:

1. In the main menu select **File → New Project**.
2. Select **PlatformIO** in the **Categories** section.
3. Fill in the project form.
4. The project will be created by PlatformIO according to the specified parameters and imported into NetBeans.
5. The generated project contains a source file named `main.cpp`, which should open automatically after the project is created.
6. To build the project use the standard **Build Project** command or press **F11**.
7. To upload the project (firmware), select **Run → Run Project** or press **F6**. PlatformIO's upload command is mapped to the IDE's **Run** command.

To open the Serial Monitor, navigate to **Window → IDE Tools → Serial Monitor**.

See the [NB PlatformIO DEMO](https://raw.githubusercontent.com/gholdys/nbpio/master/nbpio-demo.mp4) for a short demonstration.

**Platform compatibility:** The plugins have been tested only on Linux.
