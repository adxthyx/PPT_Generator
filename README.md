![banner](https://github.com/otahina/PowerPoint-Generator-Python-Project/assets/108225969/bfe8f796-3ffa-4c59-92f5-7624f6f9884f)

[![made-with-python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)
[![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/otahina/PowerPoint-Generator-Python-Project.git)
[![View My Profile](https://img.shields.io/badge/View-My_Profile-green?logo=GitHub)](https://github.com/otahina)

<img src="https://img.shields.io/github/stars/otahina/PowerPoint-Generator-Python-Project.svg"> <img src="https://img.shields.io/github/forks/otahina/PowerPoint-Generator-Python-Project.svg">

## PowerPoint Generator: Your Gateway to Effortless Presentations 🚀

Dive into the ease of presentation creation with PowerPoint Generator, a smart web application crafted to automate 
PowerPoint presentations! 🌟 
This project is ripe for growth and eager for your contributions. Let's enhance its capability together! 😊

## Demo Highlights 🎬

https://github.com/otahina/PowerPoint-Generator-Python-Project/assets/108225969/82d98c7a-0244-4fed-8f6b-f6c994fd69e3

## Table of Contents 📋

1. [Features](#features)
2. [Inner Structure of the Project](#inner-structure-of-the-project)
3. [How to Use](#how-to-use)
4. [How to Contribute](#how-to-contribute)

## Features 

* **🤖 AI-Driven Content Creation**: Utilize the power of GPT-3.5 Turbo to generate slide content based on user's input.
* **😎 Intelligent Slide Generation**: The tool intelligently proposes titles and content for each slide.
* **🎨 Customizable Themes**: Choose color themes for your presentation, giving it a personalized touch.
* **🙂 User-Friendly Interface**: Clear instructions and an intuitive design make the PowerPoint generation process seamless and straightforward.

## Inner Structure of the project 

If you want to learn how to use the GPT API for creating PowerPoint presentations or understand how the project is 
organized, check out [CODE_STRUCTURE.md](docs/CODE_STRUCTURE.md). 🧐
In this document, I explain the code and the relationships between different parts of the code.

## How to use

If you want to try using this project, here is a step-by-step guide. 
Those who want to contribute to (which is welcome!), please check [How to Contribute](#how-to-contribute)

<details>
<summary>
Step 1: Star The Repo ⭐️
</summary>

Star the repo to start using this project 👍

![star repo](https://docs.github.com/assets/images/help/stars/starring-a-repository.png)

</details>

---

<details>
<summary>
Step 2: Clone It 🐑
</summary>

- **Using Git** 

Open your terminal and run the following command:

```bash
git clone https://github.com/otahina/PowerPoint-Generator-Python-Project.git
```

- **Using Download ZIP**

1. Go to the GitHub page of the repository.
2. Click on the green **Code** button.
3. In the dropdown menu, select **Download ZIP**.

</details>

---
<details>
<summary>
Step 3: Create a Virtual Environment 📟
</summary>

On Windows 🪟
- Open your **Command Prompt** and navigate to your project's directory.
- Run the command line by line.
    ```bash
    python -m venv venv
    .\venv\Scripts\activate
    pip install -r requirements.txt
    ```
On macOS and Linux 🐧
- Open your **Terminal** and navigate to your project's directory.
- Run the command line by line.
    ```bash
    python3 -m venv venv
    source venv/bin/activate
    pip install -r requirements.txt
    ```
</details>

---

<details>
<summary>
Step 4: Setup API Keys 🔑
</summary>

⚠️ This step is very important to make the project work! 
please make sure if you set up everything correctly. 
Instruction ▶️ [Setup the Secret Key and OpenAI Key](set-up-api-keys)

</details>

---

<details>

<summary>
Step 5: Run 🏃‍
</summary>

Navigate to `myapp` directory. Run `flaskapp.py`

```bash
python3 myapp/flaskapp.py
```

</details>

## Setup the Secret Key and OpenAI Key 

The application uses a secret key for session management and an OpenAI key for the GPT-3.5 Turbo API.
These keys are defined as environment variables, and you can easily set them up using the provided .env.example file.

1. Locate the file named .env.example in the project directory.
2. Copy the contents of .env.example into a new file named .env.
3. Replace the placeholder values with your actual keys:
   
```
SECRET_KEY=your_secret_key
OPENAI_KEY=your_openai_key
PEXELS_API_KEY=your_pexels_key
```

Here's a brief description of each key and how to obtain them:

**SECRET_KEY**: 🔐This is used for web application security such as session management. You can create your own secure, random string for this.

**OPENAI_KEY**: 🤖This is required to access the OPENAI API. Although there's a limitation with the free version, it's sufficient for trying out this web application on your local machine. You can obtain this key by creating an account on the https://platform.openai.com.

**PEXELS_API_KEY**: 🏞️ This key is used for the free image search API provided by Pexels. It's very useful for adding creative images to your presentations. You can get this key by creating a free account on the https://www.pexels.com/api
After registering, the API key is automatically generated for you.









