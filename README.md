# Groq Chatbot

This is a Python-based CLI chatbot utilizing the Groq API. The chatbot is designed to mimic a human.

## Requirements
- Python 3.x 
- Groq API Key → https://groq.com

## Installation
1. Clone this repository:
   ```sh
   git clone https://github.com/anywindo/Groq-CLI-ChatBot.git
   cd Groq-CLI-ChatBot
   ```
2. Install dependencies:
   ```sh
   pip install groq
   ```
3. Set up the Groq API key as an environment variable:
   ```sh
   export GROQ_API_KEY="your_api_key_here"
   ```
   Alternatively, you can enter the API key when prompted at runtime.

## Usage
Run the chatbot with:
```sh
python bare.py
```

### Commands:
- `exit` or `quit` → Ends the conversation.
- `reset` → Resets the chatbot's memory.
- `help` → Displays command information.

## License
This project is licensed under the MIT License. Feel free to modify and distribute it.
