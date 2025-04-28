# Prompting Projects: Diverse Examples in Conversational AI

## Overview
This repository contains a Python-based collection of prompting examples, showcasing my skills in crafting effective prompts for conversational AI. Using OpenAI’s API and a Panel GUI, I’ve implemented various techniques including normal prompts, one-shot, few-shot, iteration, summarizing, inferring, transforming, expansion, and a chatbot.

## Features
- **Variety of Prompting Techniques**: Includes normal prompts (e.g., noodle recipe), one-shot, few-shot, iteration, summarizing, inferring, transforming, and expansion examples.
- **Chatbot Implementation**: An interactive chatbot with a GUI for real-time conversation.
- **Customizable Responses**: Adjusts creativity with temperature settings (e.g., 0.7).
- **Practical Applications**: Demonstrates diverse use cases from recipes to inference.

## Requirements
- Python 3.8+
- Libraries: `openai`, `panel`, 'IPython.display'
- OpenAI API key (set in the code or as an environment variable)

## Clone the Repository
To get started, clone the repository to your local machine using the following commands:

```bash
git clone <your-repo-url>
cd prompting-projects
```
## How to Run
1. **Set your OpenAI API key**:
   - Edit `prompting_code_gpt.py` and replace the `client = OpenAI(api_key="your-key")` line with your API key.
2. **Run the script**:
   ```bash
   python prompting_examples.py
   
3. **Interact with the examples via the GUI by entering requests like**:
	- "Give me steps to make noodles."
	- "Infer the sentiment of 'I love this!'"
	- "Chat with me about the weather."

## Example Output
- User Prompt : Based on the fact sheet of Samsung Galaxy S25 Ultra, write 
a description of the phone in the technical specifications
	- Response: The Samsung Galaxy S25 Ultra is a flagship smartphone with a 6.9" Dynamic LTPO AMOLED 2X display, a powerful quad camera system including a 200MP main sensor, and a Qualcomm Snapdragon 8 Elite processor. It features a 5000mAh battery, 5G connectivity, and advanced security features.
- User Prompt: Summarize the comparision of AI image edit tools on smartphones from GSMArena website.
	- Response: Samsung's AI image edit tool is the best, with easy setup and smooth operation. Xiaomi's tool excels in texture generation but is less reliable. Apple and Google's tools are easier to use but have some shortcomings.

## Future Improvements
- Add real-time data integration for weather or recipes.
- Expand with more complex prompting scenarios.

## About Me
I’m Gautham, transitioning into Data Science and Generative AI with 6 years of IT experience. This project reflects my prompt engineering progress, inspired by courses like "ChatGPT Prompt Engineering" and "LangChain: Chat with Your Data" from DeepLearning.AI. Connect with me on https://www.linkedin.com/in/gautham-varadharajan-ab4708331 !
