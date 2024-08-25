### Get your free 30 day license key at [toledo1.com](https://toledo1.com)
#### Watch [Demo](https://rumble.com/v5bpmh9-toledo1-a-multi-llm-app-can-now-run-any-anthropic-api-model.html)

#### Supported Systems
- [Windows x64](https://github.com/toledo-labs/toledo1/releases/download/v1.3.0/windows-inno-installer-toledo1-v1.3.0-promo.exe)
- [Linux x64](https://github.com/toledo-labs/toledo1/releases/download/v1.3.0/linux-flatpak-installer-toledo1-v1.3.0-promo.zip)
- [macOS](https://github.com/toledo-labs/toledo1/releases/download/v1.3.0/macos-dmg-installer-toledo1-v1.3.0-promo.dmg)


Windows installer tested on Windows 11,
Linux Flatpak installer tested on Ubuntu 22.04 and RedHat 9.4,
macOS installer tested on Sonoma 14.6


All installers are single click except the Linux Flatpak which requires an install script to run without sudo. 
The script will build and install the flatpak package locally using artifacts
because there isn't a remote hosted package to pull into the system.
**See instructions below**

#### Linux Flatpak Install Instructions

1. (Optional) Add your API key to the operating system environment with name "OPENAI_API_KEY" 

   Example: add the below line into the user ~/.bashrc with a text editor:
   
   ```bash
   export OPENAI_API_KEY="API KEY from your inference server"
   ```  
    
   Save ~/.bashrc then exit and source it:
   
   ```bash
   $ source ~/.bashrc
   ```   
   
2. Install Toledo1 

   ```bash
   # Do not run with sudo!
   $ ./install_toledo1_with_flatpak.sh
   ```
   
3. Search for Toledo1 and pin it to the taskbar
4. Launch Toledo1 by clicking on its icon

#### Remove Toledo1 instructions

1. Remove Toledo1
   ```bash
   $ flatpak uninstall com.toledo1.Toledo1
   ```
