# Self-Learning--ChatBot
This Python project implements a chatbot with a JSON-based knowledge base. It responds to user queries by searching for the closest matching question and allows users to teach it new responses if none are found.
Certainly! Below is a simple README.md file for your chatbot code:

---

# ChatBot with Knowledge Base

This repository contains a Python script for a simple chatbot with a knowledge base stored in a JSON file. The chatbot interacts with users, attempting to match their queries with existing questions in the knowledge base and allowing users to teach it new responses.

## Features

- **Knowledge Base Management**: The chatbot loads and saves questions and answers from a JSON file.
- **Fuzzy String Matching**: It uses the difflib library to find the best match for user queries, enhancing interaction accuracy.
- **Interactive Teaching**: Users can teach the chatbot new responses if it fails to find a suitable answer.

## Requirements

- Python 3.x

## Installation

1. Clone the repository to your local machine:

```bash
git clone [https://github.com/yourusername/chatbot-knowledge-base.git](https://github.com/16adity/Self-Learning--ChatBot.git)
```

2. Install any required Python packages:

```bash
pip install -r requirements.txt
```

## Usage

1. Ensure you have a knowledge base file named `knowledge_base.json` in the project directory. If not, the script will create one.
2. Run the chatbot script:

```bash
python chatbot.py
```

3. Interact with the chatbot by typing your queries. Type "quit" to exit the chatbot.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please feel free to open an issue or create a pull request.

