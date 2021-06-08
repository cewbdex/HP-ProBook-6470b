# Updating Intel Management Engine Firmware

In my case HP did not ship right files for Intel Management Firmware upgrade, so I had to do it on my own. Follow this guide on your own risk, basically there is none, but you never know.

- Download [Intel CSME detection tool](https://downloadcenter.intel.com/download/28632/Intel-Converged-Security-and-Management-Engine-Intel-CSME-Detection-Tool), run it. The application will complain that `This system is not supported`, but we don't care, just scroll to the most bottom and find `Version` - `8.1.70.15.90`, look for the first two numbers, `8.1` in my case.

- Open [Win-Raid ME topic](https://www.win-raid.com/t596f39-Intel-Converged-Security-Management-Engine-Drivers-Firmware-and-Tools.html) in your browser. Read it, all disclaimers and warnings apply. Navigate to the C2 section and find a tool that matches your Version (`8` in my case). Extract it to a folder named `ME Tools` (for example in your desktop folder).

- Download [ME Analyzer tool](https://github.com/platomav/MEAnalyzer/releases) and extract it to folder named `ME Analyzer`.

- In the `ME Tools` folder navigate to `FWUpdate\Local-Win64\`. In File explorer navigate to top left corner and click `File` and select run powershell as an administrator. In the powershell window execute `.\FWUpdLcl64.exe -save bkp.bin`, we will analyze this file, but don't lose it, you can reflash it back, if the new firmware causes troubles.

- Copy the `bkp.bin` to the `ME Analyzer` folder, double click `MEA.exe`, type in `bkp.bin` and write down the `SKU` parameter (1.5MB in my case).

- Navigate to the `B1` section of the [Win-Raid ME topic](https://www.win-raid.com/t596f39-Intel-Converged-Security-Management-Engine-Drivers-Firmware-and-Tools.html), find a file that matches your `Version` AND `SKU` (8 and 1.5MB in my case). Download the file and open the archive. Extract the `*.bin` file to the `FWUpdate\Local-Win64\` of the `ME Tools` we have used earlier. Rename the extracted file as `new.bin`.

- Open powershell in the `FWUpdate\Local-Win64\` folder as before. Execute `.\FWUpdLcl64.exe -f new.bin`. Wait till the process finishes and look for any errors. If the flash completes successfully, restart the computer to load the new firmware.

- You can also download the latest Intel ME driver from the [Win-Raid ME topic](https://www.win-raid.com/t596f39-Intel-Converged-Security-Management-Engine-Drivers-Firmware-and-Tools.html) from the `A1` or `D1` section, depending on your `Version`.
