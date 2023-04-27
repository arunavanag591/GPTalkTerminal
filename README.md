# GPTalkTerminal
This is a command-line assistant implmentation using ChatGPT API

1. Developed using `python 3.8.7`
2. You will need to use your own API key from openai.

## Setting up your openai API key
[How to Get an OpenAI API Key?](https://www.howtogeek.com/885918/how-to-get-an-openai-api-key/)

Once you have created your key, create an excel file named **openaikey.xlsx** and <u>store the key in the first row of first column</u>. Save the file and <u>store it right outside the GPTTalkTerminal folder</u> so your unique key is safe.

1. To install the dependencies
`pip install -r requirements.txt`

2. To run the application
`python openai_cli.py`

3. To exit the chat, type `quit`


## Issues you may run into

1. You might run into `Error 429`, which is a quota limit put by Openai for free users. However paid users do not need to worry about this error.
