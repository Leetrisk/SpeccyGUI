# SpeccyGUI
This is simply a dumbed down version of speccy that gives the basic and important info's of your system specs, theme will update live and save

this is written in c#/.net  with the ImGUI.NET library

<sub> This should work with Nvidia/AMD/Intel GPU's, but only nvidia is tested</sub>

**THIS USES THE FOLLOWING LIBRARIES TO HELP ACHIEVE ITS FUNCTIONALITY:**

- ClickableTransparentOverlay & ImGUI.Net (for the menu/overlay)
- Fody / Costura Fody (to pack the libraries & packages inside the .exe and keep it clean)
- LibreHardwareMonitor & SharpDX / SharpDX.DXGI (to retreive some values about the hardware)
- Newtonsoft.JSON (for handling config file / JSON deserializing)

$${\color{red}Currently the space the UI is rendered in is grabbed from primary screen (this is also whats reflected as 'primary monitor resolution' on the UI, because of this it may have problems with multiple monitors- specifically, you may not be able to move the UI outsize the zone of the main monitor, i do not care to fix this problem, u can change it with the source.rar above if you know what you are doing}$$


![Screenshot](screenshot2.png)
