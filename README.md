# FBXExporterForUnity
The FBXExporter for Unity 1.3.1
Originally developed by KellanHiggins : https://github.com/KellanHiggins/UnityFBXExporter
Revised by Crisosphinx (Jeff Miller), here.


Functionality was built upon KellanHiggins project
!!! (***note to future me to ask to make a fork of their project...***)

This revised version of KellanHiggins project allows for more functionality:
 - Automatic conversion of FBX files from ASCII to Binary,
 - Works on Windows (Tested with Windows 10),
 - Works on Mac (Tested with Big Sur),


To install, follow the instructions below:
----------------
 - Download the project (RECOMMENDED : https://github.com/crisosphinx/FBXExporterForUnity/blob/master/FBXExporterForUnity.unitypackage)
 - Do one of the following:
   + Drop all files into the Assets directory, or
   + Unzip the FBXExporterForUnity.unitypackage into your project (recommended, as it's easier / less steps),

To use, follow the instructions below:
----------------
 - In Unity click on a Prefab Model,
   + Select your object in the Scene Hierarchy, or
   + Select your object in the Project Window
 - Do one of the following:
   + Right-click that specific Prefab model, or
   + Go to the Assets Menu at the top of your window,
 - An option should appear called "FBXExporer",
   + Select this sub-menu to find one of three options to export,
     ~ Export only the GameObject,
     ~ Export GameObject with new Materials,
     ~ Export GameObject with new Materials and Textures,
- Feedback will appear in the console window / log that states if your export worked:
  + File is missing! (Your_File_Name_Here)
  + Model should now be converted properly to Binary FBX.
  + Model is ASCII, you may have to fix this manually...
  + The end of the path wasn't ".fbx"


What this project comes with:
----------------
 - This comes with a test object, material and textures
   + To test, go to "Prefabs" and right-click the object "TryExportingMe"
   + If all works well, you will receive a debug message that states "Model should now be converted properly to Binary FBX."
 - Materials for if the texture or material is missing from the object on export (so you can debug),
 - Two converter files,
 - Updated code for running conversions,
