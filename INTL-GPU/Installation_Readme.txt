Release Version:  Planned Release
Intel(R) Graphics Driver: 10.18.10.5161
Intel(R) Display Audio Driver:  6.16.00.3154
Build Date:  Aug 6, 2020

Operating System(s):   
	Microsoft Windows* 7-64
	Microsoft Windows* 8.1-64
	Microsoft Windows* 10-64

Platforms:
	3rd generation Intel(R) Core(TM) processor family (Codename Ivy Bridge)
	Bay Trail


CONTENTS OF THIS DOCUMENT
I.		Installation Information
II.		System Requirements
III.	Localized Language Abbreviations
IV.		Installing the Software
V.		Verifying Installation of the Software
VI.		Identifying the Software Version Number
VII.	Installation Switches 
VIII.	Uninstalling the Software

I.  INSTALLATION INFORMATION
Supports Intel(R) HD Graphics on:
	3rd generation Intel Core processor family (Codename Ivy Bridge)
	Bay Trail

DISCLAIMER: Intel is making no claims of usability, efficacy or warranty.  The INTEL SOFTWARE LICENSE AGREEMENT contained herein completely defines the license and use of this software.
This document contains information on products in the design phase of development. The information here is subject to change without notice. Do not finalize a  design with this information.

II.  SYSTEM REQUIREMENTS
1.  The system must contain one of the following Intel chipsets/processors:
	3rd generation Intel(R) Core(TM) processor family (Codename Ivy Bridge)
	Bay Trail	
2.  The software should be installed on systems with at
    least 1 GB of system memory.
3.  There should be sufficient hard disk space in the <TEMP>
    directory on the system in order to install this
    software.
    The drivers included with this distribution package are
    designed to function with all released versions of
    Microsoft  Windows* 7, 8.1, and 10 OS(s) available at the time of release of this package.

Please check with your system provider to determine the
operating system and Intel chipset used in your system.

III.  LOCALIZED LANGUAGE ABBREVIATIONS
The following list contains the hexadecimal key of all
languages into which the driver has been localized. You may
have to refer to this section while using this document.

ara – Arabic (Saudi Arabia)
cht – Chinese (Simplified)
cht – Chinese (Traditional)
hrv - Croatian 
cys - Czech
dan - Danish
nld - Dutch
enu - English (US)
fin - Finnish
fra-  French 
deu - German
ell - Greek
heb - Hebrew
hun - Hungarian
ita - Italian
jpn - Japanese
kor - Korean
nor – Norwegian (Bokmal)
plk - Polish
ptg - Portuguese (Brazilian)
ptb - Portuguese 
rom - Romanian
rus-  Russian
SKY - Slovak
SLV - Slovenian
Esp - Spanish
Sve - Swedish  
Tha - Thai
Trk - Turkish

IV.  INSTALLING THE SOFTWARE
General Installation Notes:
1.  The operating system must be installed prior to the installation of the 
    driver.
2.  This installation procedure is specific only to the version of driver 
    and installation file included in this release.
3.  This procedure assumes that all of the software associated with this 
    release is located in the same directory.

INSTALLATION INSTRUCTIONS 
------------------------------------------------------------------
To install from a Web download, you will download either a .zip file or an 
.exe file.

a. If it is a .zip file, double-click on the file you downloaded and choose 
   "Extract all files". Browse to a destination folder and choose "Extract".
b. If it is an .exe file, double-click on the file you downloaded and specify a 
   location to extract the  driver files. Click "Unzip" and the files will 
   extract. Click "OK" on the next window, then click "Close". 

------------------------------------------------------------------
  Microsoft Windows* "igxpin.exe" Installation
------------------------------------------------------------------
1. Locate the hard drive directory where the driver files are stored 
   using the browser or the Explore feature of Windows*.
2. From this directory, double-click the "igxpin.exe" file.
3. The first dialog of the installation user interface will appear. 
4. Click "Next" to continue.
5. Read the License Agreement and, if you agree with the terms, 
   click "Yes" to proceed.
6. Review the Readme File information and click "Next" to proceed.
7. When the "Setup Progress" is complete, click "Next" to proceed.
8. When the "Setup is Complete" screen appears, click "Finish" to
   complete the installation.
  
------------------------------------------------------------------
   Microsoft Windows* "Have Disk" Installation 
------------------------------------------------------------------
1.  Click "Start", right-click "Computer", and click "Properties". 
2.  Open "Device Manager" and select "Display Adapters".
3.  Right click on the device listed under "Display Adapters" and select ‘Update Driver’.
4.  Select "Browse my computer for driver software".
5.  Select "Let me pick from a list of device drivers on my computer".
6.  Click on "Have Disk".
7.  Click on “browse" and go to DriverFolder\Graphics
8.  Select any *.INF file from the Graphics folder; select "Open" and then "Ok". 
9.  Click the "Next" button and wait until the driver gets installed to get a message
   "Windows has successfully updated your driver software’.

Note:  No Changes in Graphics Driver Uninstallation
------------------------------------------------------------------
	Microsoft Windows* Manual Installation Instructions
------------------------------------------------------------------
1.  Click "Start", right-click "Computer", and click "Properties".
2.  Click "Device Manager" on the left.
3.  In the "User Account Control" window, click "Yes".
    IF UPDATING DRIVER GO TO STEP 5
4.  Double-click "Video Controller (VGA Compatible)" if present under 
    "Other Devices". (Go to step 6)
5.  Expand "Display adapters" and double-click the graphics controller.  
6.  In the "Driver" tab, click "Update Driver".
7.  Click "Browse my computer for driver software".
8.  Click directly "Browse".
9.  Browse to the directory where you unzipped the file you downloaded
    and click the "Graphics" folder.
10. Click "OK" and click "Next". The operating system will install the 
    driver if it considers this an upgrade.
11. Click "Close" and click "Yes" to reboot. The driver should now 
    be loaded.

------------------------------------------------------------------
	For Intel(R) Display Audio Driver:
------------------------------------------------------------------
1.  Click "Start", right-click "Computer", and click "Properties".
2.  Click "Device Manager" on the left. 
3.  In the "User Account Control" window, click "Yes".
4.  Double-click "Sound, video and game controllers".
5.  If installing from scratch, right-click the "High Definition Audio" 
    controller. If updating the driver, right-click the "Intel(R) 
    Display Audio" controller. Click "Update Driver Software...".
6.  Click "Browse my computer for driver software". 
7.  Click "Let me pick from a list of device drivers on my computer".
8.  Click "Have Disk..." and click "Browse".
9.  Browse to the directory where you unzipped the file you 
    downloaded, click the "DisplayAudio" folder, and select the
    "IntcDAud.inf" file. Click "Open" and click "OK".
10. Select "Intel(R) Display Audio" and click "Next". 
11. The operating system will install the driver. Click "Finish" to
    complete the installation. 
12. Click "Yes" to reboot. The driver should now be loaded. 

To determine if the driver has been loaded correctly, refer to the 
Verifying Installation of the Software section below.

V.  VERIFYING INSTALLATION OF THE SOFTWARE
1.  Click "Start", right-click "Computer", and click "Properties".
2.  Click "Device Manager" on the left. 
3.  In the "User Account Control" window, click "Yes".
4.  Expand "Display adapters". The Intel(R) Graphics Driver should 
    be listed. If not, the driver is not installed correctly. 

------------------------------------------------------------------
	For Intel(R) Display Audio Driver:
------------------------------------------------------------------
1.  Click "Start", right-click "Computer", and click "Properties".
2.  Click "Device Manager" on the left.
3.  In the "User Account Control" window, click "Yes".
4.  Expand "Sound, video and game controllers". The "Intel(R) Display 
    Audio" driver should be listed and should not show a yellow bang. 
    If not, the driver is not installed correctly. 

To check the version of the driver, refer to the section below.

VI.  IDENTIFYING THE SOFTWARE VERSION NUMBER
1.  Click "Start", right-click "Computer", and click "Properties".
2.  Click "Device Manager" on the left.
3.  In the "User Account Control" window, click "Yes".
4.  Expand "Display adapters" and double-click the graphics controller.  
5.  In the "Driver" tab, note the Driver Version.

------------------------------------------------------------------
	For Intel(R) Display Audio Driver:
------------------------------------------------------------------
1.  Click "Start", right-click "Computer", and click "Properties".
2.  Click "Device Manager" on the left.
3.  In the "User Account Control" window, click "Yes". 
4.  Expand "Sound, video and game controllers" and double-click 
    "Intel(R) Display Audio".
5.  In the "Driver" tab, click "Driver Details". The function driver 
    (IntcDAud.sys) version should be listed on this screen.

VII.   INSTALLATION SWITCHES
The switches in the igxpin.exe file will have the following syntax. 
Switches are not case-sensitive and may be specified in any order 
(except for the -s switch). Switches must be separated by spaces.
SETUP [-b] [-overwrite] [-nowinsat] [-l<LCID>] [-s] [-report <path>] 

GFX-INSTALLATION CUSTOM SWITCHES
-b Forces a system reboot after the installation completes.
In non-silent mode, the absence of this switch will prompt
the user to reboot. In silent mode, the absence of this
switch forces the igxpin.exe to complete without rebooting
(the user must manually reboot to conclude the installation
process).

-overwrite Installs the Intel(R) Graphics Driver regardless of 
the version of previously installed driver. In non-silent mode,
the absence of this switch will prompt the user to confirm
overwrite of a newer Intel(R) Graphics Driver. In silent mode, 
the absence of this switch means that the installation will 
abort any attempts to regress the revision of the Intel(R) Graphics 
driver.

-l<LCID> Specifies the language used in the installation user 
interface. Without this switch, the installation user interface 
will be shown in the Display language of the OS by default. 
Hexadecimal values for the supported languages can be found in 
the localized language abbreviations section of this readme.

-s Runs in silent mode. The absence of this switch causes
the installation to be performed in verbose mode.

-report <path> Specifies an alternate location for the log file 
created by a silent installation. By default, the log file is 
created and stored during a silent installation under <root 
directory>\Intel\Logs directory as IntelGFX.log
(<WINDIR>\Temp\IntelGFX.log).

-nowinsat Turns off the automatic support for updating / 
obtaining the WinSAT* DWM score on Windows* during installation. 
In non-silent mode, the absence of this switch will enable 
automatic support for updating the WinSAT* score, but allows 
the option to disable this support with a user accessible 
checkbox shown within the installation user interface. 
In silent mode, the absence of this switch forces an automatic 
run of WinSAT and will enable the Windows* Aero* desktop theme 
(if supported).

VIII.  UNINSTALLING THE SOFTWARE
NOTE: This procedure assumes the above installation process
was successful. This uninstallation procedure is specific
only to the version of the driver and installation files
included in this package.


	FOR INTEL(R) GRAPHICS DRIVER:
------------------------------------------------------------------
1. Click "Start", click "Control Panel" icon, and double-click 
   "Programs and Features".
2. Right-click "Intel(R) Graphics Driver" and select "Uninstall".
3. Click "Next" and "Next" to uninstall the driver.
4. Click "Finish" to restart the computer.


	For INTEL(R) DISPLAY AUDIO DRIVER:
------------------------------------------------------------------
1.  Click "Start", right-click "Computer", and click "Properties".
2.  Click "Device Manager" on the left.
3.  In the "User Account Control" window, click "Yes". 
4.  Expand "Sound, video and game controllers", right-click "Intel(R)
    Display Audio", and select "Uninstall".
5.  In the "Confirm Device Uninstall" window, click "OK" and the Intel(R)
    Display Audio driver will be uninstalled.
