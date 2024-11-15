![toledo systems](https://toledo1.com/wp-content/uploads/2024/09/social_media_all_santa_maria.png)
Toledo1 is an LLM browser where the URL points to LLM inference, a direct chat line to any LLM on the public internet, private cloud, or local desktop running OpenAI compatible inference. A paradigm shift in web search, where users pay per query with confidentiality. Its real-time capability to chain multiple models on context using presets makes it a [manual compound AI system](https://bair.berkeley.edu/blog/2024/02/18/compound-ai-systems/), a truth machine.

### Get your free 30 day license key at [toledo1.com](https://toledo1.com)
#### [See what sets Toledo1 apart from the other web LLM apps](https://toledo1.com/wp-content/uploads/2024/07/toledo1_demo_5.mp4)

#### Supported Systems
- [Windows x64](https://github.com/toledo-labs/toledo1/releases/download/v1.7.1/windows-inno-installer-toledo1-v1.7.1.exe)
- [Linux x64](https://github.com/toledo-labs/toledo1/releases/download/v1.7.1/linux-flatpak-installer-toledo1-v1.7.1.zip)
- [macOS](https://github.com/toledo-labs/toledo1/releases/download/v1.7.1/macos-dmg-installer-toledo1-v1.7.1.dmg)

![toledo1_demo](https://toledo1.com/wp-content/uploads/2024/11/toledo1_demo_bitcoin_analysis.gif)

### Toledo1 Features
* 📱 **Client-Side Search:** Powerful native desktop application that integrates seamlessly with your workflow. Search and process information directly from your PC with simple one-click installation

* ⚙️ **Easy Installation:** Get started in minutes - Toledo1 is ready to use immediately after license key activation. No complex setup or configuration required

* ❌ **No Subscriptions:** Transparent pay-per-query pricing model with enterprise-grade security. Only pay for what you actually use with our confidential API system

* 🤖 **AI Agent:** Advanced RAG (Retrieval-Augmented Generation) pipeline with customizable LLM chains. Future updates will include automated chain building and an intelligent Auto-mode in Settings

* 💡 **Dynamic Code Copilot:** Leverage specialized code LLMs with customizable presets for diverse programming solutions. Perfect for feature development, debugging, and application architecture

* 📊 **Real Time Data:** Access live market data, weather information, and current events through integration with Perplexity.ai's advanced Sonar models. Stay updated with accurate, real-time information

* 📁 **History Management:** Seamlessly transfer your chat history between different LLM systems while preserving context, including files and images. Never lose important conversations

* 🔄 **Multi-Purpose Assistant:** Customize Toledo1's behavior and expertise through flexible system settings. Adapt the AI to serve your specific professional or personal needs

* 📂 **File & Image Processing:** Effortlessly process multiple file formats including text, PDF, and images. Advanced LLM processing helps extract and analyze information from your documents

* 🔒 **Local Inference:** Maintain complete privacy with on-device processing using llama.cpp. Keep sensitive data secure while enjoying powerful AI capabilities locally

#### List of tested Operating Systems
- **Windows installer** tested on Windows 11
- **Linux Flatpak installer** tested on Ubuntu 22.04 and RedHat 9.4
- **macOS installer** tested on Sonoma 14.6
  
All installers are single click except the Linux Flatpak which requires an install script to run without sudo. 
The script will build and install the flatpak package locally using artifacts
because there isn't a remote hosted package to pull into the system.
**See instructions below**

[Toledo1 Documentation](https://toledo1.com/quick-start/)

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


