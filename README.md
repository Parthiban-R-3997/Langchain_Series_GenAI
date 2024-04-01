# GenAI Chatbot Project

## Overview
This project demonstrates the integration of Langchain and OpenAI to create a conversational AI chatbot. The chatbot utilizes the capabilities of Langchain for language processing and OpenAI's GPT-3.5 model for generating responses.

## Requirements
- Python 3.10
- langchain_openai
- langchain_core
- streamlit
- python-dotenv

## Installation
1. Clone the repository:
git clone https://github.com/Parthiban-R-3997/Langchain_Series_GenAI.git
cd Langchain_Series_GenAI


2. Install dependencies:
pip install -r requirements.txt



## Usage
1. Set up environment variables:
- Create a `.env` file in the root directory of your project.
- Add the following variables to your `.env` file:
  ```
  LANGCHAIN_API_KEY="your_langchain_api_key_here"
  OPENAI_API_KEY="your_openai_api_key_here"
  ```
2. Run the Streamlit app:
streamlit run app.py


3. Enter the topic you want to search for in the text input field and the chatbot will provide responses based on the input.

## Example
![screenshot](https://github.com/Parthiban-R-3997/Langchain_Series_GenAI/assets/26496805/ef76bcf3-30cd-4745-b338-842966d75fa2)

## License
This project is licensed under the [MIT License](LICENSE).



