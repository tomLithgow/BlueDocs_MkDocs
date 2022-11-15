Bluefish444 Unreal Engine 
User Guide

Version 4.27

# Introduction

Bluefish444, the professionals’ choice, supports Epic® Unreal Engine® to bring true uncompressed 12-bit HD-SDI and SMPTE IP I/O to users of Epic Games Unreal Engine..
Bluefish has been the choice of professionals requiring the highest quality SDI and SMPTE IP input and output solutions with hardware options supporting  4:2:2 YUV, 4:4:4 RGB, 3D, and 4K HD-SDI, 12-bit video processing..
Bluefish has a long history of providing OEM solutions to industry-leading developers requiring high-quality I/O solutions capable of performing day in day out, all year round. The range of Bluefish video hardware caters to video professionals that require tried and tested reliability, combined with the lowest latency of true uncompressed input and output solutions. Supporting 4K/2K/HD/SD capture & playback, 12-bit video processing, and a quality HDMI video preview.


## Versions
Bluefish444 hardware is compatible with the following versions of Epic Games Unreal Engine software:

* Unreal Engine 4.26
* Unreal Engine 4.27
* Unreal Engine 5.0

## Unreal Engine compatible Bluefish444 hardware


||  | |
| :--------: |:-------------:|:---------:|
|KRONOS K8 | Epoch Supernova | Epoch Neutron |
|KRONOS Optikos3G | Epoch Supernova S+ | Epoch Neutron LP |
|                   |                   | Epoch 4K Neutron |
|                   |                   | Epoch 4K Neutron LP |
<div style="page-break-after: always"></div>
## Bluefish444 Hardware Video Modes Supported in Unreal Engine

The supported video modes are detailed below for each Bluefish444 hardware;

| | 4:2:2 YUV 8-BIT | 4:2:2 YUV 10-BIT |4:4:4 RGB 8-BIT | 4:4:4 RGB 10-BIT | 4:4:4 RGB 12-BIT |
| :--------: |:-------------:|:---------:| :--------: |:-------------:|:---------:|
| (SD) (625/525) @ 25, 29.97 fps | KRONOS K8, 4K Supernova S+, 4K Neutron, Neutron | KRONOS K8, 4K Supernova S+, 4K Neutron, Neutron | KRONOS K8, 4K Supernova S+, 4K Neutron, Neutron | KRONOS K8, 4K Supernova S+, 4K Neutron, Neutron |  |
| (HD) 720p @ 23.98, 25, 50, 59.97, 60 fps | KRONOS K8, 4K Supernova S+, 4K Neutron, Neutron | KRONOS K8, 4K Supernova S+, 4K Neutron, Neutron |  |  |  |
| (HD) 1080i @ 25, 29.97, 30 fps | KRONOS K8, 4K Supernova S+, 4K Supernova, 4K Neutron, Neutron | KRONOS K8, 4K Supernova S+, 4K Supernova, 4K Neutron, Neutron | KRONOS K8, 4K Supernova S+, 4K Supernova, 4K Neutron, Neutron | KRONOS K8, 4K Supernova S+, 4K Supernova, 4K Neutron, Neutron | KRONOS K8, 4K Supernova S+, 4K Supernova, 4K Neutron, Neutron |
| (HD) 1080p/PsF @ 23.98, 24, 25, 29.97, 30 fps | KRONOS K8, 4K Supernova S+ , 4K Neutron , Neutron | KRONOS K8, 4K Supernova S+, 4K Neutron, Neutron | KRONOS K8, 4K Supernova S+, 4K Neutron, Neutron | KRONOS K8, 4K Supernova S+, 4K Neutron, Neutron | KRONOS K8, 4K Supernova S+, 4K Neutron, Neutron |
| (HD) 1080p @ 48, 50, 59.97, 60 fps | KRONOS K8, 4K Supernova S+ , 4K Neutron , Neutron | KRONOS K8 , 4K Supernova S+, 4K Neutron, Neutron |  |  |  |
| (2K) 1080p/PsF @ 23.98, 24, 25, 29.97, 30 fps | KRONOS K8, 4K Supernova S+, 4K Neutron , Neutron | KRONOS K8, 4K Supernova S+, 4K Neutron, Neutron | KRONOS K8, 4K Supernova S+, 4K Neutron, Neutron | KRONOS K8, 4K Supernova S+, 4K Neutron, Neutron | KRONOS K8, 4K Supernova S+ , 4K Neutron, Neutron |
| (2K) 1080p @ 48, 50, 59.97, 60 fps | KRONOS K8, 4K Supernova S+ , 4K Neutron | KRONOS K8, 4K Supernova S+, 4K Neutron |  |  |  |
| (UHD) + (4K) p @ 23.98, 24, 25 fps | KRONOS K8, 4K Supernova S+ , 4K Neutron | KRONOS K8, 4K Supernova S+, 4K Neutron | KRONOS K8 , 4K Supernova S+, 4K Neutron | KRONOS K8 |  |
| (UHD) + (4K) p @ 29.97, 30 fps | KRONOS K8 , 4K Supernova S+ , 4K Neutron | KRONOS K8 , 4K Supernova S+, 4K Neutron | KRONOS K8 | KRONOS K8 |  |
| (UHD) + (4K) p @ 48, 50, 59.97, 60 fps | KRONOS K8 | KRONOS K8 |  |  |  |

<div style="page-break-after: always"></div>

# Installation guide
Bluefish444 includes the Epic Games Unreal Engine Media IO Plugin as part of the Professional installation package. For the latest installer, please refer to the Bluefish444 website:
https://bluefish444.com/support/downloads.html

## Included in this installer package:

* Bluefish444 Driver
* Firmware updater
* Bluefish444 feature application
* ASIO audio drivers
* BlueRT (Edit-While-Record plug-ins)
* 3rd-party application plug-ins
* RS-422 port to virtual Serial port driver
* BlueController
 
## Steps to install Bluefish444 driver package for use with Unreal Engine

1. Install Unreal Engine software and third-party applications as required.
2. Physically install the Bluefish444 HD-SDI IO hardware in the recommended PCI express slot. Refer to the hardware user manual for details on physical card installation. The Bluefish444 user manual can be downloaded from the Manual section of the Bluefish444 website.
https://bluefish444.com/support/downloads/details/5/video-card-documentation.html
3. Download, save, and run the current Bluefish444 Professional installer package, available at the download section of the Bluefish444 website.
https://bluefish444.com/support/downloads.html
4. The Bluefish444 installer package may request that you update your hardware to the latest firmware. Bluefish444 recommends running the firmware included in the latest installer for use with all third-party applications.

Your Bluefish444 hardware should now be installed and ready for use with the Unreal Engine.

*If the appropriate plug-ins for your application have not been installed for any reason, or if any application does not detect the
Bluefish hardware, please uninstall the driver package through the Windows Control Panel > Uninstall. Restart the workstation and
run the install package again.

<div style="page-break-after: always"></div>

# Unreal Engine Configuration

## Requirements

In order to use Bluefish444 professional Video hardware within the Unreal Engine there are a number of prerequisites listed below;

* Bluefish444 compatible Hardware
* Bluefish444 Driver and complimentary Firmware
* Bluefish444 Unreal Engine Plugin
(Available from the Marketplace or as part of the Bluefish444 Professional Install package)
* Supported Unreal Engine version

With the above requirements met and the Bluefish444 hardware confirmed as configured and working correctly, we can progress to configure an Unreal Engine Project.

## Unreal Engine Project
* Open the Project that you want to use with Bluefish444  video I/O in the Unreal Editor then;
* From the main menu, select Edit > Plugins.
* In the Plugins window, find the BF444 Media Player plugin under the Media Players category. Check its Enabled checkbox.
* Find the Media Framework Utilities Plugin under the Media Players category. Check its Enabled checkbox, if it's not already checked.
* Click Restart Now to restart the Unreal Editor and reopen your Project.

Your Project is now ready to accept video from the Bluefish444 compatible hardware, and to send the rendered output out the cards interfaces. 

In the next section, we will connect it within the project to allow Bluefish444 inputs to be used within Unreal Engine and to play the final rendering out of the Bluefish444 Output interfaces.

## Rendering Video Input in the Unreal Engine
In this process, we'll make video input from the Bluefish444 input interface visible in the current Level in the Unreal Editor. This process uses a Media Bundle: a kind of Asset that packages together several different types of Assets involved in the Media Framework, and that offers you control over some advanced features like lens deformation, chroma-keying, color correction, and more.

From a new folder in the Content Editor, right-click in the Content Browser and choose Media > Media Bundle.

Your new Asset's name is automatically selected in the Content Browser, so you can give it a descriptive name:
Type a new name, like BF444MediaBundle, and press Enter. A new folder of Media Framework Assets is automatically created next to your Media Bundle, named with the suffix _InnerAssets. 

Save your new Assets by clicking the Save All button in the Content Browser.

Double-click your new Media Bundle to edit its properties. The Media Bundle is capable of playing video from any kind of media source the Engine supports, so you'll need to tell it that you want to get the video from your Bluefish444 hardware.
In the Media Source property, select BF444 Media Source from the drop-down list:

Once you've identified the type of Media Source you want the Media Bundle to handle, you can then set up any configuration properties offered by that type of source.
The most important thing to set here for the BF444 Media Source is the Configuration setting, to make sure that the bundle is set up to capture video from the right device and input port, using the same resolution and frame rate as the actual video feed. Click the arrow to open the settings submenu, select the options that match your setup, then click Apply in the submenu.

If you want to apply any compensation to the incoming video to account for lens distortion, you can set up the physical properties of the lens in the Lens Parameters section. 

These Lens Parameters just set up the physical properties of the lens. You'll actually activate the lens compensation later, when you edit the Material Instance used by the Media Bundle.
Save your Media Bundle when you're done setting up its properties, and return to the BF444 folder in the Content Browser.

Drag your BF444MediaBundle Asset from the Content Browser into the Level Viewport.

You'll see a new plane appear, showing the video currently being played over the port configured for your Media Bundle. Use the transform tools in the Viewport toolbar to move, rotate, and resize it.

If your Media Bundle doesn't start playing automatically, select it, then click the Media Bundle > Request Play Media button in the Details panel.

Now, we'll see how to apply keying and compositing effects to the video stream.
Back in the Media Bundle Editor, click the Open Material Editor button in the Toolbar to edit the Material Instance that this Media Bundle uses to draw its incoming video feed on to an object in the Level.

This Material Instance is saved inside the AjaMediaBundle_InnerAssets folder that was created automatically with your Media Bundle.

In the Material Instance Editor, you'll see a number of properties exposed for you to configure keying, cropping, and color correction, and to activate the correction for the lens distortion that you set up in the Media Bundle.

While you adjust the settings in the Material Instance Editor, you can see the effect of your changes on the video feed playing back in the main Level Viewport.

You may find it more convenient to see the effects of the changes you make in the preview panel of the Material Instance Editor instead. To do this, temporarily enable the IsValid setting, and set its value to 1.0.

Click the arrow at the top left of the viewport toolbar, and enable the Realtime option in the menu.
Realtime viewport
You'll be able to judge the effect of your changes more easily by changing the preview mesh to a plane or a cube. Use the controls at the bottom of the viewport:

When you're done, return the IsValid setting to its previous value.

When you're done changing the Material Instance properties, click the Save button in the Toolbar.

At this point, you should have video playing in your scene from a Bluefish444 SDI or IP Input Interface, and you should understand where to set up more advanced features like lens deformation and chroma-keying.

If you're already familiar with the Media Framework, another way you could get video into your Level is to create a new BF444MediaSource Asset in your Project, and set it up with the same source properties you set up inside the Media Bundle in the procedure above. Then, create your own MediaPlayer and MediaTexture Assets to handle the playback of that source in your Level. For details, see the Media Framework documentation. However, we recommend using the Media Bundle, as shown above, to get the best balance between ease of use and professional quality video features.


