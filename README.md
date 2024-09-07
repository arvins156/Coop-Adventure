# Coop-Adventure

A 2 Player adventure game made in August 2024 using Unreal Engine 5.4

## Description

The game was developed for the purpose of experimenting with multiplayer features and Steam's Online Subsystem API. This includes online functionalities such as remote procedure calls (server, client, multicast, as well as RPC validations), replication, authority, ownership, as well as general networking. As for other gameplay-related features, the game uses moving components (a transporter component), collectable keys, win conditions, as well as custom delegates. All related classes can be found in the source files.

## Getting Started

### Dependencies

* The game was developed for Windows machines using the x86-64 architecture
* Install the latest release of Unreal Engine 5.4 from the Epic Games Launcher
* MacOS and Linux compatibility has not been verified

### Installation

To install and run the application, you will need to first download the files in this repository:

* At the top of this page, click Code and Download Zip
* Extract the zip contents using a tool like [7-Zip](https://7-zip.org/download.html)
* Move the files to into a new folder

Alternatively, you may clone this repository:

* In a command line window with [Git](https://git-scm.com/) or
* On Windows, use [Git Bash](https://git-scm.com/download/win) to execute the commands below
```sh
# Navigate into your desired repository
$ cd (name of the directory of your choice)

# Clone this repository
$ git clone https://github.com/arvins156/Coop-Adventure.git
```

### Executing program

You will need to build from source using Unreal Engine 5.4. 

* In the folder you created, run the [CoopAdventure.uproject](https://github.com/arvins156/Coop-Adventure/blob/main/CoopAdventure.uproject) file
* This will build the project and fulfil the dependencies
* If for any reason the project fails to build, remove the Binaries, Intermediate and Saved folders generated and attempt to build again
* Once the project is successfully built, Unreal Engine will open and you will be able to playtest the game in the editor
* Enjoy!

If you would like to distribute the game to a second player, export the project using the three-dot dropdown next to the green play button for your platform of choice in the Unreal Engine editor. Windows package is recommended.

## Acknowledgments

* Followed content in the [Unreal Engine 5 C++ Multiplayer](https://www.gamedev.tv/courses/ue-cpp-multiplayer) course by GameDev.tv

* Free assets by Epic Games from the Unreal Engine Marketplace
