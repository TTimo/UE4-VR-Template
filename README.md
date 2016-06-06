
=================================
   HTC Vive Template v2.0 BETA
=================================

##Introduction

This template is for use in Unreal Engine 4 for commercial, non-commercial development and learning projects. 
It designed to work with the HTC Vive Virtual Reality unit. Although its supposed to be used for the HTC Vive, 
anyone using a Oculus Rift, Gear VR, OSVR or other HMD's can also use this template though it might need slight 
modifications in the controller inputs. The entire template is done in UE4's node base programming system 
called Blueprints. This can also be done in C++ however C++ code is not used in this template. 

If you need more information on how to use UE4's Blueprint programming system, you may visit the official documentation by following this link:

Unreal Engine 4: Blueprint Programming Documentation
https://docs.unrealengine.com/latest/INT/Engine/Blueprints/index.html


If you are new to Virtual Reality programming you may also want to visit the official documentation for working with Virtual Reality equipment in Unreal Engine 4.

Unreal Engine 4: Virtual Reality Documentation
https://docs.unrealengine.com/latest/INT/Platforms/VR/?lang=zh-CN



##v2.0 Beta Changelist

- Improved 'Pickup Object' ability

- Changed Render settings in the Project Settings menu back to default due to recent changes to the way rendering happens while using VR

- Pickup ability used to be triggered by the Grip buttons or Triggers but that proved to be too messy to be used in a template. Removed the Trigger pickup ability and 
  replaced all individual button events with Input Events.

- Fixed Player Spawn

- Added new Vive Controller Meshes. These are Skeletal and have animations for the trigger pulls as well as trackpad thumb gesture tracking.


##v2.0 Future Additions

- Ability to Teleport from location to location

- Weapons

- Effects for weapon/item use

- Proper use of VFX

- Proper use of AFX


For more information on this template please visit the official Unreal Engine 4 Forums thread:

https://forums.unrealengine.com/showthread.php?108302-HTC-Vive-Template
