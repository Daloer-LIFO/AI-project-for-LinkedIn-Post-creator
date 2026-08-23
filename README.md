# AI-project-for-LinkedIn-Post-creator


## AI-Powered LinkedIn Post Generator Using LangChain

### Project Overview

This project is developing an AI Agent using LangChain that generates professional and engaging LinkedIn posts based on user input.

The user is providing a topic and selecting the language of the post. The AI Agent is then using a Large Language Model (LLM) to generate a structured LinkedIn-style post in the selected language.

### Task Objective

The main objective of this project is building an AI Agent with LangChain that generates LinkedIn posts for users.

### Project Functionality

The application is accepting the following inputs:

- Topic of the LinkedIn post
- Language of the post

The AI Agent is then:

- Generating a professional LinkedIn-style post
- Writing the post in the selected language
- Maintaining a professional and engaging tone
- Structuring the output into approximately 2–4 paragraphs
- Adding relevant hashtags

### Technologies Used

- Python
- Google Colab
- langchain
langchain-google-genai 
Gemini API

### Installation

Install the required libraries:

```python
!pip install -qU langchain-google-genai langchain-core
```

### Setting Up the API Key

The OpenAI API key is being entered securely using the following code:

```python
import os
from getpass import getpass

os.environ["GOOGLE_API_KEY"] = getpass("Enter your Gemini API Key: ")
```

### Running the Project

The user is entering a topic and language:

```python
topic = input("Enter the topic: ")
language = input("Enter the language: ")
```

The AI Agent is then generating the LinkedIn post using the LangChain pipeline.

### Example Input

```text
Topic: AI in Healthcare
Language: English
```

### Example Output

The AI Agent is generating a professional LinkedIn post discussing the role and importance of Artificial Intelligence in healthcare.

### Project Workflow

```text
User Input
    ↓
Topic and Language
    ↓
LangChain Prompt Template
    ↓
Large Language Model
    ↓
Output Parser
    ↓
Generated LinkedIn Post
```

### Features

- Supporting multiple topics
- Supporting multiple languages
- Generating professional LinkedIn-style content
- Using LangChain for LLM orchestration
- Producing structured and engaging output

### Testing Examples

The following examples are being used for testing:

| Topic | Language |
|---|---|
| AI in Healthcare | English |
| Remote Work Productivity | English |
| Artificial Intelligence in Education | Bengali |
| Machine Learning | Spanish |

### Author

**Md. Daloer Hossain**

### Submission

This project is submitted as part of the **Module 21 – AI Agent Project** assignment.

The project deliverables include:

- Google Colab Notebook / Code Repository
- 2–3 minute demonstration video
