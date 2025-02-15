# How to Install DeepSeek on Visual Studio Code: A Comprehensive Step-by-Step Guide:

This step-by-step guide will show you how to install and run DeepSeek locally, configure it with CodeGPT, and leverage AI to enhance your software development workflow without relying on cloud-based services.

![image](https://github.com/user-attachments/assets/a23f0ad5-a441-4065-a619-a9533f74e3f0)

## `Step 1: Install Ollama and CodeGPT in VSCode:`

To run DeepSeek locally, we first need to install Ollama, which allows us to run LLMs on our machine, and CodeGPT, the VSCode extension that integrates these models for coding assistance.

* `Install Ollama:` Ollama is a lightweight platform that makes running local LLMs simple.

* `Visit the official website:` <a href = "https://ollama.com">Download Ollama</a>

![image](https://github.com/user-attachments/assets/eafddeba-c712-4cba-a420-360752f781d8)

* Download the installer for your operating system (Windows, macOS, or Linux).
* After installation, open a terminal and run: `ollama --version`

If Ollama is installed correctly, it will display the installed version.


### `Install CodeGPT in Visual Studio Code:`

* Open VSCode and navigate to the Extensions Marketplace (Ctrl + Shift + X or Cmd + Shift + X on macOS).
* Search for “CodeGPT” and click Install.

![image](https://github.com/user-attachments/assets/dd9d1f68-3d00-4091-99af-5e4b2125aad9)

* Or you can create a free account here: https://codegpt.co

With Ollama and CodeGPT installed, we’re now ready to download and configure DeepSeek to start coding with AI locally.

## `Step 2: Downloading and Setting Up the Models:`
Now that you have successfully installed both Ollama and CodeGPT, it’s time to download the models you’ll be using locally.

* Chat model: deepseek-r1:1.5b, which is optimized for smaller environments and will run smoothly on most computers.
* Autocompletion model: deepseek-coder:1.3b. This model utilizes Fill-In-The-Middle (FIM) technology, allowing it to make intelligent autocompletion suggestions as you write code. It can predict and suggest the middle part of a function or method, not just the beginning or the end.

`Download the Chat Model (deepseek-r1:1.5b)`

To get started with the chat model:
* Open CodeGPT within VSCode.
* Navigate to the Local LLMs section in the sidebar.
* From the available options, select Ollama as the local LLM provider.
* Choose the model deepseek-r1:1.5b.
* Click the Download button. The model will begin downloading automatically.

Once the download is complete, CodeGPT will automatically install the model. After installation, you’re ready to start interacting with the model.

You can now easily query the model about your code. Simply highlight any code within your editor, add extra files to your queries using the # symbol, and leverage powerful command shortcuts such as:

![image](https://github.com/user-attachments/assets/83ffc654-dffa-4ff7-b6e2-e35ae62d1da7)
* /fix — For fixing errors or suggesting improvements in your code.
* /refactor — For cleaning up and improving the structure of your code.
* /Explain — To get detailed explanations of any piece of code.

This chat model is perfect for assisting with specific questions or receiving advice on your code.


`Download the Autocompletion Model (deepseek-coder:1.3b)`
* Open a Terminal in VSCode.
* Run the following command to pull the deepseek-coder:1.3b model: `ollama pull deepseek-coder:1.3b`
* This command will download the autocompletion model to your local machine.
* After the download completes, return to CodeGPT and navigate to the Autocompletion Models section.
* Select deepseek-coder:1.3b from the list of available models.

Once selected, you can start coding. As you type, the model will begin providing real-time code suggestions, helping you complete functions, methods, and even entire blocks of code with ease.














