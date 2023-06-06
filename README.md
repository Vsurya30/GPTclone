# GPTclone
An Clone of ChatGPT using Python-Flask and Open AI
# ChatGPT Clone with OpenAI and Flask

This project is a ChatGPT clone built using the OpenAI API and Flask framework with tailwindCSS. It allows users to have interactive conversations with an AI-powered chatbot. The chatbot is trained on a vast amount of text data by OPENAI and can generate responses based on the input provided by the user.

## Features

- Interactive conversations with an AI chatbot
- Real-time response generation using the OpenAI API
- Easy integration with web applications using the Flask framework

## Prerequisites

Before running this project, ensure that you have the following installed:

- Python (version 3.7 or higher)
- Flask (install using `pip install flask`)
- OpenAI Python SDK (install using `pip install openai`)
- npm i tailwindcss installing tailwindCSS

## Getting Started

To get started with this project, follow these steps:

1. Clone the repository: `git clone https://github.com/your-username/GPTclone.git`
2. Change into the project directory: `cd GPTclone`
3. Install the required dependencies: 
    pip install flask
    pip install openai 
    pip install pymongo
    npm i tailwindcss
  
5. Set up the OpenAI API credentials by creating an account on the OpenAI platform (https://platform.openai.com/) and obtaining an API key.
6. Open the `app.py` file and replace `YOUR_API_KEY` with your actual OpenAI API key.
7. Save the changes and exit the file.
8. Create a cluster using mongodb atlas and connect the mongodb database with the app.
9.  Connect the TailwindCSS with HTML file 
10.  Run Tailwind using `npm run tailwind`
11. Start the Flask development server: `python main.py`
12. Open your web browser and navigate to `http://localhost:5000` to access the chatbot interface.

## Usage

Once you have the chatbot up and running, you can start having conversations by typing messages into the chatbox and pressing Enter. The chatbot will generate responses based on the input you provide.

## Customization

You can customize the behavior of the chatbot by modifying the code in `main.py`. You can tweak the parameters passed to the OpenAI API or add additional functionality to enhance the chatbot's capabilities.

## Limitations

Please note that while this chatbot aims to provide realistic and informative responses, it may occasionally generate incorrect or nonsensical answers. This is a known limitation of language models and should be taken into consideration when using the chatbot.As of now It takes only one input at a time and you need to refresh it.


## Acknowledgements

- This project utilizes the OpenAI API for natural language processing.
- The Flask framework is used for building the web application.
- Mongo Db to store the data received from the OPENAI

Feel free to contribute to this project by submitting pull requests or reporting issues. Enjoy chatting with your AI-powered chatbot!
