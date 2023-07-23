# 🤖 AI-Assisted Programming Tools (Mini-Workshop @ CCCP, UCologne)
Welcome to the AI-assisted programming workshop! You can find the slides of the workshop here [![Google Slides](https://img.shields.io/badge/Slides-yellow?logo=google-slides)](https://github.com/chkla/copilot-cccp/blob/main/AI-Assisted_Programming_for_Researchers@CCCP-2023.pdf). In this workshop, we covering a winde range of topics including generative language models, auto-completion tools (GitHub Copilot, etc.), chat-based tools (HuggingChat, etc.), and the limits and open challenges of these new types of models.

Before we can use 

## Windows

### Step 1: Install Anaconda
Anaconda is a free and open-source distribution of Python and R for scientific computing. It simplifies package management and deployment. Here is how you can install it:
* Download the Anaconda installer for Windows from the Anaconda Downloads page.
* Run the installer. During the installation process, you'll see an option to add Anaconda to your PATH environment variable. It is recommended to leave this unchecked and instead use Anaconda command prompts.
* Once the installation is complete, you can verify it by opening the Anaconda Prompt from your Start menu and typing the following command: `conda --version`

### Step 2: Install Packages with Anaconda
After installing Anaconda, you can install additional Python packages using the conda command. For example, to install a package named pandas, you would use the following command: `conda install pandas`

## Unix

### Step 1: Install Homebrew
Homebrew is a package manager for macOS that simplifies the installation of software. If you don't have Homebrew installed, open Terminal and run the following command:

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

### Step 2: Install Python and Pip
Python comes pre-installed on macOS, but you might want to install a different version. To do so, you can use Homebrew: `brew install python`

This will also install Pip, which is a package manager for Python.
To confirm that Python and Pip were installed correctly, in Terminal, run: `python3 --version` and `pip3 --version`
