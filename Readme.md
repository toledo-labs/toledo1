
Toledo1 is an LLM browser where the URL points to LLM inference, a direct chat line to any LLM on the public internet, private cloud, or local desktop running OpenAI compatible inference. A paradigm shift in web search, where users pay per query with confidentiality. Its real-time capability to chain multiple models on context using presets makes it a [manual compound AI system](https://bair.berkeley.edu/blog/2024/02/18/compound-ai-systems/), a truth finder.

### Get your free 30 day license key at [toledo1.com](https://toledo1.com)
#### [See what sets Toledo1 apart from the other web LLM apps](https://toledo1.com/wp-content/uploads/2024/07/toledo1_demo_5.mp4)

#### Supported Systems
- [Windows x64](https://github.com/toledo-labs/toledo1/releases/download/v1.7.0/windows-inno-installer-toledo1-v1.7.0.exe)
- [Linux x64](https://github.com/toledo-labs/toledo1/releases/download/v1.7.0/linux-flatpak-installer-toledo1-v1.7.0.zip)
- [macOS](https://github.com/toledo-labs/toledo1/releases/download/v1.7.0/macos-dmg-installer-toledo1-v1.7.0.dmg)

#### List of tested Operating Systems
- **Windows installer** tested on Windows 11
- **Linux Flatpak installer** tested on Ubuntu 22.04 and RedHat 9.4
- **macOS installer** tested on Sonoma 14.6

![toledo1_demo](https://toledo1.com/wp-content/uploads/2024/10/toledo1_btc_proj.gif)

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
   
#### List of tested Inference Providers
- [OpenAI](https://openai.com)
- [Anthropic](https://anthropic.com)
- [Perplexity.ai](https://perplexity.ai)
- [Cerebras](https://cloud.cerebras.ai/)
- [Huggingface Endpoints](https://huggingface.co/)
- [Nvidia Inference Microservices](nvidia.com)
- [Llama.cpp](https://github.com/ggerganov/llama.cpp/blob/master/examples/server/README.md)
- [Deepinfra](https://deepinfra.com/)
- [Sambanova](https://sambanova.ai/)
- [Openrouter](https://openrouter.ai/)
- [LambdaLabs](https://lambdalabs.com)


