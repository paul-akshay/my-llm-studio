# My LLM Studio

A personal playground for wrangling Large Language Models \(LLMs\) into doing weird, wonderful, and occasionally useful things.


## Just in case you want to try it out yourself

1. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

2. **Set up your OpenAI API key:**
   
   Create a `.env` file in the project root
   ```
   OPENAI_API_KEY=your_openai_api_key_here
   ```
   
   Replace `your_openai_api_key_here` with your actual OpenAI API key.

## Current Projects

### OrderBot - Pizza Restaurant Chatbot

An interactive chatbot application demonstrating LLM capabilities for conversational ordering systems.

**Features:**
- Interactive web-based chat interface
- Automated pizza ordering workflow
- Handles menu items, toppings, drinks, and sides
- Collects delivery/pickup information
- Error handling for API issues

## Running the OrderBot Application

To run the pizza ordering chatbot:
```bash
python orderbot.py
```

The application will automatically open in your default web browser. If it doesn't open automatically, you'll see a URL in the terminal that you can click or copy to your browser.

## How to Use OrderBot

1. Type your message in the text input field
2. Click the "Chat!" button to send your message
3. The OrderBot will respond and guide you through the ordering process



