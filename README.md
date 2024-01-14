# SpeccyGUI
This is simply a dumbed down version of speccy that gives the basic and important info's of your system specs, theme will update live and save

this is written in c#/.net  with the ImGUI.NET library

<sub> THIS SHOULD WORK WITH AMD / NVIDIA GPU, intel can probably be added easily, but i am lazy and didnt add it. </sub>

**THIS USES THE FOLLOWING LIBRARIES TO HELP ACHIEVE ITS FUNCTIONALITY:**

- ClickableTransparentOverlay & ImGUI.Net (for the menu/overlay)
- Fody / Costura Fody (to pack the libraries & packages inside the .exe and keep it clean)
- LibreHardwareMonitor & SharpDX / SharpDX.DXGI (to retreive some values about the hardware)
- Newtonsoft.JSON (for handling config file / JSON deserializing)


![Screenshot](screenshot2.png)
