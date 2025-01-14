# OpenAI Chatbot with Streamlit

This repository contains a simple chat application built with Streamlit and OpenAI's GPT-3.5-Turbo model. The application allows users to interact with an AI-powered chatbot.

## Features
- Real-time chat interface
- User and assistant chat message containers
- Persistent chat history during app session


![GitHub Repo stars](https://img.shields.io/github/stars/yourusername/your-repo-name?style=social)
![GitHub last commit](https://img.shields.io/github/last-commit/yourusername/your-repo-name)
![GitHub issues](https://img.shields.io/github/issues/yourusername/your-repo-name)
![GitHub forks](https://img.shields.io/github/forks/yourusername/your-repo-name?style=social)
![Python](https://img.shields.io/badge/Python-3.8-blue)

![Data Source](https://img.shields.io/badge/dataset-Kaggle-blue)
![Status](https://img.shields.io/badge/status-active-brightgreen)
![Contributions](https://img.shields.io/badge/contributions-welcome-brightgreen)


## Prerequisites

Before running the application, ensure you have the following:

- Python 3.8 or higher installed on your system.
- An OpenAI API key.

## Installation

1. Clone this repository to your local machine:
   ```bash
   git clone <repository_url>
   cd <repository_directory>
   ```

2. Create a virtual environment and activate it:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```

4. Create a file named `openai_key.py` in the root directory with the following content:
   ```python
   OPENAI_API_KEY = "your_openai_api_key_here"
   ```

   Replace `your_openai_api_key_here` with your actual OpenAI API key.

## Usage

1. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```

2. Access the app in your browser at `http://localhost:8501`.

3. Enter a prompt in the chat input field and interact with the AI chatbot.

## Code Overview

### Main Components

1. **`openai_key.py`**: Stores the OpenAI API key.
2. **`app.py`**: Main application file that contains the Streamlit chat interface logic.

### Key Functionalities
- **Chat History**: Chat messages (both user and assistant) are stored in `st.session_state` to persist between app reruns.
- **User Input**: User inputs are handled via the `st.chat_input` widget.
- **Assistant Response**: The assistant's responses are generated using the OpenAI API and displayed in real-time using Streamlit's `st.chat_message` and `st.empty` widgets.

## Example Chat Flow
1. The user inputs a message into the chat input field.
2. The message is appended to the chat history.
3. A request is sent to the OpenAI API, which generates a response based on the chat history.
4. The assistant's response is displayed in real-time in the chat interface.

## Requirements File

The `requirements.txt` file should include:
```text
openai
streamlit
```

## Contributing

If you'd like to contribute to this project, please follow these steps:
1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Submit a pull request with a clear description of your changes.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments

- [OpenAI](https://openai.com/) for the GPT-3.5-Turbo model.
- [Streamlit](https://streamlit.io/) for the interactive web app framework.


## Final output

<img width="1440" alt="Screenshot 2025-01-14 at 14 55 10" src="https://github.com/user-attachments/assets/7b014a39-6878-4e7a-a3de-f3e8a96c0b76" />


