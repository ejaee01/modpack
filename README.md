Minecraft Server Modpack

This repository contains the mods and resource pack needed to join the server.

The setup is for Windows 10 and Windows 11 and uses Minecraft 26.2 with Fabric.

What is included

The repository contains the mods used by the server and the server resource pack.

Use the same Minecraft version and mod loader as the server. Do not mix Fabric mods with Forge or NeoForge.

GitHub

For a manual installation, download the required .jar files from the mods folder in this repository.

If there is a resource pack in the repository, download the ZIP from the resourcepacks folder.

Do not unzip .jar files. They must stay as .jar files.

Prism Launcher

Prism Launcher is the easiest option if you want to keep the server setup separate from your normal Minecraft installation.

Install Prism Launcher.

Create a new instance.

Select Minecraft 26.2.

Select Fabric as the mod loader.

Launch the instance once, then close Minecraft.

Right-click the instance in Prism Launcher and select Edit.

Open the Mods tab.

Add the required mods from this repository.

Put the resource pack ZIP in the instance's resourcepacks folder if you want to install it manually.

You can drag .jar files directly into Prism Launcher's Mods tab.

Do not extract the mod .jar files.

Normal Minecraft Launcher

The normal launcher requires a manual setup.

Install Fabric

Download and run the Fabric Installer.

Select Minecraft 26.2.

Install the Fabric client profile.

Open Minecraft Launcher.

Select the new Fabric profile.

Start Minecraft once, then close it.

Install the mods

Press Windows + R and enter:

%appdata%\.minecraft\mods

If the mods folder does not exist, create it.

Download the required .jar files from this repository and put them directly into the folder.

It should look similar to:

.minecraft
└── mods
    ├── fabric-api-....jar
    ├── glitchcore-....jar
    └── serene-seasons-....jar

The exact filenames may be different depending on the versions being used.

Install the resource pack

Press Windows + R and enter:

%appdata%\.minecraft\resourcepacks

Put the resource pack ZIP in this folder.

Do not extract the resource pack ZIP.

It can then be selected from:

Options -> Resource Packs

The server may also provide the resource pack automatically when you join.

CurseForge

If you use the CurseForge App, create a custom Minecraft profile for the server.

Open CurseForge.

Go to Minecraft.

Create a custom profile.

Select Minecraft 26.2.

Select Fabric as the mod loader.

Open the profile's Mods section.

Add the required mods.

Launch the profile.

If a mod is available through CurseForge, it can be installed directly from the app.

If a mod is only available from GitHub, download its .jar from this repository and put it into the CurseForge profile's mods folder.

The CurseForge profile has its own game folder, so it may not use %appdata%\\.minecraft\\mods.

Updating

When the server updates a mod, replace the old version with the version listed in this repository.

Do not keep two versions of the same mod in the mods folder. Having multiple versions can prevent Minecraft from starting.

If the server changes Minecraft versions, update Minecraft and check every mod before joining.

If Minecraft crashes

Check the following first:

Minecraft is version 26.2.

You are using Fabric, not Forge or NeoForge.

Fabric API is installed.

GlitchCore is installed if required by the current Serene Seasons version.

You have the correct Serene Seasons version.

There are no duplicate mod versions.

You did not unzip any .jar files.

The resource pack is still a ZIP.

If it still does not work, send the crash report or latest log.

