# SimpleChatBotWithMemory

**SimpleChatBotWithMemory** is an interactive chatbot application built using LangChain and OpenAI's GPT-3.5-turbo model. The chatbot is designed to maintain conversational context by remembering past interactions within a session, creating a more engaging and personalized user experience.

## Features

- **Conversational Memory**: Tracks and retains user inputs and responses during a session for a coherent conversation flow.
- **Powered by OpenAI**: Utilizes OpenAI's GPT-3.5-turbo model to provide intelligent and context-aware responses.
- **Session Management**: Implements session-based message history to keep conversations contextual and relevant.
- **Scalable Design**: Designed for easy extension and integration into larger applications.
- **Environment Configuration**: Secure handling of sensitive keys and configurations using a `.env` file.

## Setting Up the Environment

1. **Activate the virtual environment**:

   - **Windows**:
     ```bash
     venv\Scripts\activate
     ```

   - **MacOS/Linux**:
     ```bash
     source venv/bin/activate
     ```

2. **Install the required dependencies**:
   ```bash
   pip install -r requirements.txt
   
###  Configure the .env File
You need to add the OpenAI API key and other sensitive information to the .env file. Add the following line to your .env file:

OPENAI_API_KEY=your-openai-api-key
