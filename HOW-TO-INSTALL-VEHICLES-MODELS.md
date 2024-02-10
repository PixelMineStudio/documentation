![Logo](https://i.imgur.com/3sVP1xA.png)

# PixelMine | How to Install Vehicles

This document describes the installation of vehicle configurations purchased by PixelMine customers. Everything is written in detail in the document. Please make sure that you have done everything for the installation. You can contact us about all the problems you are experiencing.

## Contact Us

- [Join Community](https://discord.gg/pixelmine)
- [Our Website](https://pixelmine.com)

## Supported Plugins

- Default Resource Pack Downloader
- Any resource pack downloader system (not compatible IA & Oraxen)
- QualityArmory Vehicles
- MTVehicles
- VehiclesPlus

Some of our tools do not support some of the plugins in the supported plugins list. You can see them on the sales page of the product you want to buy. For any questions you may have, you can contact us from the community server.

### Step 1: Installing Resource Pack Downloader;

- 1: After purchasing the product, you can download it with the "downloads" button.
- 2: Extract the downloaded .zip file to your desktop.
- 3: From the extracted folders, go into the one that says "Resource Pack" and save the 3 files in .zip format. You can use the file name as you like.
- 4: Then upload the .zip file to the https://mc-packs.net website.
- 5: It will give you the download URL and SHA-1 Hash code. Do not close that page.
__If you are using the default resource pack downloader;__
- 6: Open the server.properties file of your Minecraft server.
- 7: Enter the download url in front of resource-pack=
- 8: And also enter the sha-1 hash code in front of resource-pack-sha1=
__If you are using plugins like RHForceResourcePack;__
- 6: Open the config.yml file of your RHForceResourcePack plugin folder.
- 7: Enter the download url in front of resourcepack-url: ‘<here>’.
- 8: In the config.yml file, change kick: enabled: false to true.
__We will then continue with your process;__
- 9: Now restart your server and proceed to step 2.

### Step 2: Select and install the appropriate vehicles plugin;

__If your choice is the MTVehicles plugin;__
- 1: Make sure that the MTVehicles plugin is installed correctly on the server.
- 2: In the .zip file you extracted, replace the "vehicles.yml" file in the "MTVehicles" folder with the vehicles.yml file in the MTVehicles folder in the plugins folder.
- 3: You can then reload the MTVehicles plugin and start using it.
**Note:** MTVehicles has a resource pack and vehicles.yml file by default. If you drag and drop, there will be no default assets. In order to use default assets, you need to integrate MTVehicles with the configurations you purchased. You can check the community page of MTVehicles to get information about this.

__If your choice is the VehiclesPlus plugin;__
- 1: Make sure that the VehiclesPlus plugin is installed correctly on the server.
- 2: In the .zip file you extracted, replace the “config.yml” file in the “VehiclesPlus” folder with the “config.yml” file in the VehiclesPlus folder in the plugins folder.
- 3: Then put the "vehicles" folder in the VehiclesPlus folder into the "VehiclesPlus" folder on the server.
- 4: You can then reload the VehiclesPlus plugin and start using it.

Again, it is recommended to read the note in MTVehicles above to merge default assets.

__If your choice is the QAV plugin;__
- 1: This page of the documentation will be activated soon. Work on integration with the plugin owner is ongoing. You can join the community and create a ticket to get private information.

