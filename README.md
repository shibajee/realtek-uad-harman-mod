## Instructions:
- First uninstall current realtek audio driver.
- Restart ur PC with Disable driver signature enforcement:

Go to Settings > Update & Security > Recovery > Advanced startup > click Restart now

Now go to Troubleshoot > Advanced options > Startup Settings > click Restart

After the restart u will get a Startup Settings page, press F7 to go into disable driver signature enforcement.

- Download driver "Realtek_UAD_Harman_v6.0*****.7z" from here [![Github all releases](https://img.shields.io/github/downloads/shibajee/realtek-uad-harman-mod/total.svg)](https://github.com/shibajee/realtek-uad-harman-mod/releases/) and extract it.

- Go to UAD_Harman_2020 folder and double click Setup.exe.

![alt text](https://i.postimg.cc/9QDrtMSq/Untitled-2.png)

Continue with the warning sign and click Install this driver software anyway. Do not restart, select I will restart my computer later.

- After that go to Harman_Audio folder and install "Audio By Harman.msi" control panel.

- Enable Sideload apps:

Go to Settings > Update & Security > For developers > click Sideload apps and close.

- Now go to UWP_BUNDLE folder and run INSTALL_UWP_BUNDLE.bat as administrator. This will install Realtek UWP audio control panel. Installation is silent and will close automatically.

Wait 1 min to give time to install the UWP application in background properly.

- Restart ur PC and Enjoy Harman Clari-Fi effects.

- Go to Sound Control Panel from Settings > System > Sound and select Custom formats for ur need.

![alt text](https://i.postimg.cc/MTq59k0h/harman2.png)



![alt text](https://i.postimg.cc/GpDrkfb0/harman1.png)


## FAQ:

- Which Windows version is compatible ?

Windows 10 64bit RS5 1809 to latest whatever version.

- Why no 32bit support ?

ƒuck 32bit.

- Which realtek audio chips are supported with this mod ?

Almost every audio chip they made.

- Any plan to add multiple APO in future ?

No, I like things simple and lightweight.

- Any update schedule for driver ?

At least once in every month.
