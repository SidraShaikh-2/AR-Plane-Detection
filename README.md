# AR-Plane-Detection
This Unity AR Foundation plane detection tutorial will teach you how to use ar foundation to visualize horizontal planes.  
Reference: https://www.youtube.com/watch?v=uWWiYfPTUtU

## Download the packages from Unity Registry:  
-AR foundation  
-AR subsystems  
-ARCore XR plugin (for Android build)  
-ARKtit XR plugin (for IOS build)  

## Create the game objects:
1) AR session origin -> AR Camera
2) AR session
3) New GameObject (Rename as AR plane as we will create a new AR plane prefab)

![image](https://github.com/SidraShaikh-2/AR-Plane-Detection/assets/57295469/07f6f5d6-fa1f-458f-a57d-bb8b132e9649)

## AR Plane Game object components and settings:
### Add the following components:   
•	AR Plane (script)  
•	AR plane mesh visualizer  
•	Mesh collider  
•	Mesh filter  
•	Mesh renderer  
•	Line renderer  

### Settings of the components:  
Line renderer:  
![image](https://github.com/SidraShaikh-2/AR-Plane-Detection/assets/57295469/24cfacab-8024-48e8-b212-882d70853bbd)

### Create a material:
![image](https://github.com/SidraShaikh-2/AR-Plane-Detection/assets/57295469/a6b14e7b-578b-4b56-8b9c-9b043bc73a47)

### Add the material to the mesh renderer:
![image](https://github.com/SidraShaikh-2/AR-Plane-Detection/assets/57295469/101c0dc1-beb5-4ceb-a8d7-6425c14061c9)

Then convert the AR Plane game object to prefab.

## AR Session Origin Game object components and settings:  
### Add the following components:   
•	AR Session Origin (script)    
•	AR plane manager (script)  

Then add the create new AR plane Prefab to AR plane manager:  
![image](https://github.com/SidraShaikh-2/AR-Plane-Detection/assets/57295469/cb19271b-1044-459b-9957-85a2a4c6882a)

## AR Camera Game object components and settings:  
![image](https://github.com/SidraShaikh-2/AR-Plane-Detection/assets/57295469/8a70870c-bddb-4722-ba1b-565170de206e)

## Build settings: (Go to Build Player Settings)
•	Remove Vulcan   
•	Disable multithreading rendering  
•	Change the package name  
•	Set Minimum api to level 26  


