# SpeccyGUI
This is simply a dumbed down version of speccy that gives the basic and important info's of your system specs, theme will update live and save

this is written in c#/.net  with the ImGUI.NET library

<sub> This should work with Nvidia/AMD/Intel GPU's, but only nvidia is tested</sub>

**THIS USES THE FOLLOWING LIBRARIES TO HELP ACHIEVE ITS FUNCTIONALITY:**

- ClickableTransparentOverlay & ImGUI.Net (for the menu/overlay)
- Fody / Costura Fody (to pack the libraries & packages inside the .exe and keep it clean)
- LibreHardwareMonitor & SharpDX / SharpDX.DXGI (to retreive some values about the hardware)
- Newtonsoft.JSON (for handling config file / JSON deserializing)

> [!warning]  
> With multiple monitors, it may be only visible in the main monitors area
> I wont fix this because its not a problem for myself, you can recompile with the source above and fix it yourself if you know what you are doing


![Screenshot](screenshot2.png)
