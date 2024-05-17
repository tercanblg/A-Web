
<br/>

## Features

1) Constructed using with OpenAI's **Chat Completions API**, enables the selection of either the ***gpt-3.5-turbo***, ***gpt-4o*** or ***gpt-4-turbo*** model to **generate high-quality human-like responses** to user’s prompts.

2) Enables communication with the GPT model through either **text messages** or **speech input**.
   
3) Utilizes OpenAI's ***Whisper*** model for accurate **speech-to-text conversion** for user’s speech input, and ***TTS*** (**text-to-speech**) model for chatbot's audio response output.

4) Provides an option to **play the bot’s responses in audio format** for an immersive and realistic conversational experience.

5) Offers a variety of **built-in prompts** that assign roles or personas to the chatbot, provides an effective starting point for each type of conversations, and ensures that the chatbot will produce the desired responses in an efficient manner.

:

1) Enables the selection of either the ***gpt-3.5-turbo***, ***gpt-4o*** or ***gpt-4-turbo*** model to **generate high-quality human-like responses** to user’s prompts.
   
2) Built upon OpenAI's **Assistants API**, **specifically tuned and optimized** to provide coding assistance to programmers of all levels.

3) Supports **various coding tasks**, including code generation, debugging, refactoring, adding comments, code reviewing, generating GitHub README, and suggesting solutions to coding challenges.

4) Provides **auto-prompts** for the GPT model tailored to the various coding tasks that users may need help with.

5) Offers a **user-friendly interface** that surpasses the original ChatGPT.

6) Allows **comfortable code entry and pasting**, and **direct uploading of code scripts** from the user’s local computer, for enhanced convenience.

7) Enables users to code confidently in unfamiliar territory.

<br/>

## Repository Structure

The repository structure of the project is as follows:
```
OpenAI-API-Web-Apps/
├── .streamlit/
│   └── config.toml
├── assets/
│   ├── ChatGPT-Tkinter-Desktop-App.exe
│   └── cover-page.gif
├── pages/
│   ├── 2_Talk_To_GPT.py
│   └── 3_CodeMaxGPT.py
├── Home.py
├── packages.txt
├── requirements.txt
├── .gitignore
├── README.md
└── LICENSE
```
The description of each file and folder in the repository is as follows:

* **.streamlit/**: This folder contains the **config.toml** file, which configures the appearance of the Streamlit web application. The **config.toml** file specifies the theme settings such as primary color, background color, text color, and font.
* **assets/**: This folder contains additional assets used in the project, including the **cover-page.gif** image file for the cover page. It also includes the **ChatGPT-Tkinter-Desktop-App.exe**, which is a simplified desktop version of **Talk to GPT**. You can find the source code for the desktop application in the [ChatGPT-Tkinter-Desktop-App](https://github.com/MaxineXiong/ChatGPT-Tkinter-Desktop-App.git) repository.
* **pages/**: This folder contains the Python code that powers the three web applications. It includes the following Python scripts:
    - **2_Talk_To_GPT.py**: Python script for the **Talk to GPT** web application.
    - **3_CodeMaxGPT.py**: Python script for the **CodeMaxGPT** web application.
* **Home.py**: This is a Python script for the home page of the Streamlit web applications. It contains code related to the navigation between the three web applications.
* **packages.txt**: The file manages the project dependencies and is necessary for deploying the web applications on _Streamlit Cloud_.
* **requirements.txt**: This file lists all the required Python modules and packages. It is also necessary for the deployment of the web applications on _Streamlit Cloud_. It ensures that the required dependencies are installed when deploying the applications.
* **.gitignore**: This file intentionally specifies untracked files that Git should ignore.
* **README.md**: Provides an overview of this repository.
* **LICENSE**: The license file for the project.

<br/>

## **Usage**

The web applications are currently hosted on *Streamlit Cloud*. To access the applications, please visit [**OpenAI API Web Applications on Streamlit**](https://maxinexiong-openai-api-web-apps-home-xbxlm8.streamlit.app/). Once you visit the URL, you will be presented with a home page where you can select the desired web application. Click on the application you want to use, and it will open in a new tab or window.

### **Get Started with Talk to GPT**

To use the **Talk to GPT** application, follow these steps:

1. Visit the [**Talk to GPT on Streamlit**](https://maxinexiong-openai-api-web-apps-home-xbxlm8.streamlit.app/Talk_To_GPT).
2. Select your desired GPT model.
3. Input your [OpenAI API key](https://platform.openai.com/api-keys) in the field at the top.
4. You can start interacting with the chatbot using either the "MESSAGE BOT" or "TALK TO BOT" options.
5. For text input, click on the "MESSAGE BOT" expander, select a built-in prompt from the dropdown menu, and press CTRL + Enter to submit. The chatbot will respond with a generated message. You can continue the conversation by entering your own messages.
6. For speech input, make sure the text message input field is cleared, then click on the "TALK TO BOT" expander, click on the microphone icon, and speak your message. The speech input will be converted to text, and the chatbot will respond accordingly.

Below are two GIF images that demonstrate the usage of the **Talk to GPT** application:


<p align='center'>
    <img width=600 src="https://github.com/MaxineXiong/OpenAI-API-Web-Apps/assets/55864839/ca2629b8-5506-42e8-814b-5319429aaf83">
    <br>Interacting through text messages
</p>

###

<p align='center'>
    <img width=600 src="https://github.com/MaxineXiong/OpenAI-API-Web-Apps/assets/55864839/9d975dc5-5d38-4ee3-8cf2-085249f166fb">
    <br>Interacting through speech input
</p>

### **Get Started with CodeMaxGPT**

To use the **CodeMaxGPT** application, follow these steps:

1. Visit the [**Introducing CodeMaxGPT**](https://maxinexiong.github.io/intro-codemaxgpt.html) webpage.
2. Click on the "Get started now" button, and you'll be directed to the [**CodeMaxGPT on Streamlit**](https://maxinexiong-openai-api-web-apps-home-xbxlm8.streamlit.app/CodeMaxGPT).
3. Select your desired GPT model (*gpt-4-turbo* is **recommended**).
4. Input your [OpenAI API key](https://platform.openai.com/api-keys) in the field at the top.
5. You can now start interacting with the coding assistant by entering your text message or selecting a request from the dropdown menu. Then, enter, paste, or upload your code as needed.
6. The coding assistant will provide suggestions, completions, and other assistance based on the request prompt you select and the code you provide.
7. Feel free to explore the other features of **CodeMaxGPT** to assist you in your coding tasks.

For a detailed demonstration of using **CodeMaxGPT**, please visit the [**introduction page**](https://maxinexiong.github.io/intro-codemaxgpt.html) of the web application.

<br/>

## **Contribution**

Contributions are welcome! If you would like to contribute to the development of these web applications, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your changes to your forked repository.
5. Submit a pull request detailing your changes.

Please ensure that your contributions align with the project's coding conventions and standards. Your efforts are greatly appreciated!

<br/>


## **Acknowledgement**

I would like to acknowledge the following organizations and technologies for their contributions to this project:

- [OpenAI](https://openai.com/) for developing the powerful language models and APIs, which have enabled me to create these web applications.
- [Streamlit](https://streamlit.io/) for providing a wide range of widgets and *Streamlit Cloud*, which is a platform that allows me to deploy these web applications easily and efficiently.
- [Python](https://www.python.org/) for providing a powerful programming language that has been instrumental in the development of these applications.
- [GitHub](https://github.com/) for hosting this repository and providing a collaborative platform for open-source development.

<br/>

Thank you for choosing to use the [**OpenAI API Web Apps**](https://maxinexiong-openai-api-web-apps-home-xbxlm8.streamlit.app/). I hope that these applications will greatly amplify your programming capabilities and boost your efficiency, both in your work and in your everyday life.

# A-Web
