# AI-Assisted Programming Tools Workshop @ CCCP UCologne
Welcome to the AI-assisted programming workshop! You can find the slides of the workshop here [![Google Slides](https://img.shields.io/badge/Slides-yellow?logo=google-slides)](https://github.com/chkla/copilot-cccp/blob/main/AI-Assisted_Programming_for_Researchers@CCCP-2023.pdf). In this workshop, we covering a winde range of topics including generative language models, auto-completion tools (GitHub Copilot, etc.), chat-based tools (HuggingChat, etc.), and the limits and open challenges of these new types of models.

## Setup
* Before we can start using GitHub Copilot, we need to install Visual Studio Code. Download the Visual Code installer for Windows/ MAC from the [Visual Studio Code Download page](https://code.visualstudio.com).
* After installing VS Code, you can add the GitHub Copilot extension [Name: GitHub Copilot](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot)

# Pre-Setup
If you are using Python on your system for the first time, please follow the next steps to install it on your computer:

## Windows
### Step 1: Install Anaconda
Anaconda is a free and open-source distribution of Python and R for scientific computing. It simplifies package management and deployment. Here is how you can install it:
* Download the Anaconda installer for Windows from the [Anaconda Downloads page](https://www.anaconda.com).
* Run the installer. During the installation process, you'll see an option to add Anaconda to your PATH environment variable. It is recommended to leave this unchecked and instead use Anaconda command prompts.
* Once the installation is complete, you can verify it by opening the Anaconda Prompt from your Start menu and typing the following command: `conda --version`

### Step 2: Install Packages with Anaconda
After installing Anaconda, you can install additional Python packages using the conda command. For example, to install a package named pandas, you would use the following command: `conda install pandas`

## Unix/Mac
### Step 1: Install Homebrew
Homebrew is a package manager for macOS that simplifies the installation of software. If you don't have [Homebrew](https://brew.sh) installed, open Terminal and run the following command:

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

### Step 2: Install Python and Pip
Python comes pre-installed on macOS, but you might want to install a different version. To do so, you can use Homebrew: `brew install python`

This will also install Pip, which is a package manager for Python.
To confirm that Python and Pip were installed correctly, in Terminal, run: `python3 --version` and `pip3 --version`

## 📚 Additional Resources/ Tools/ Literature
### Literature
* Alammar (2023) "What a time for language models" [[Blog](https://jayalammar.substack.com/p/what-a-time-for-language-models?utm_source=twitter&utm_campaign=auto_share&r=27wcsl)]
* Walsh (2021) "The BERT for Humanists Project" [[Blog](http://www.bertforhumanists.org)]
* Strubell et al. (2019) "Energy and Policy Considerations for Deep Learning in NLP" [[Paper](https://aclanthology.org/P19-1355.pdf)]
* Devlin et al. (2019) "BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding" [[Paper](https://aclanthology.org/P19-1355.pdf)]
* Bender et al. (2021) "On the Dangers of Stochastic Parrots: Can Language Models Be Too Big?" 🦜 [[Paper](https://dl.acm.org/doi/10.1145/3442188.3445922)]
* Brown et al. (2020) "Language Models are Few-Shot Learners" [[Paper](https://arxiv.org/pdf/2005.14165.pdf)]
* Wang et al. (2022) "SELF-INSTRUCT: Aligning Language Model with Self Generated Instructions" [[Paper](https://arxiv.org/pdf/2212.10560.pdf)]
* Gilardi et al. (2023) "ChatGPT Outperforms Crowd-Workers for Text-Annotation Tasks" [[Paper](https://arxiv.org/pdf/2303.15056.pdf)]
* Dai et al. (2023) "AugGPT: Leveraging ChatGPT for Text Data Augmentation" [[Paper](https://arxiv.org/pdf/2302.13007.pdf)]
* Reiss (2023) "Testing the Reliability of ChatGPT for Text Annotation and Classification: A Cautionary Remark" [[Paper](https://www.dropbox.com/s/3z7okruhft74o1a/ChatGPT_Reliability_0405.pdf?dl=0)]
* Kuzman et al. (2023) "ChatGPT: Beginning of an End of Manual Linguistic Data Annotation? Use Case of Automatic Genre Identification" [[Paper](https://www.semanticscholar.org/reader/31f44f0f2124c54e47f4df54dec63118232c25da)]
* Luccioni et al. (2022) "ESTIMATING THE CARBON FOOTPRINT OF BLOOM, A 176B PARAMETER LANGUAGE MODEL" [[Paper](https://arxiv.org/pdf/2211.02001.pdf)]
* Levy et al. (2022): "SAFETEXT: A Benchmark for Exploring Physical Safety in Language Models" [[Paper](https://arxiv.org/pdf/2210.10045.pdf)]
* Bubeck et al. (2023) "Sparks of Artificial General Intelligence: Early experiments with GPT-4" [[Paper](https://arxiv.org/pdf/2303.12712.pdf)]
* ... and many more!

#### 👤 Author
Christopher Klamm

#### 📝 License
_This talk is licensed under the MIT License._
