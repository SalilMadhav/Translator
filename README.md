<h1>🌐 Language Translator Script</h1>
This Python script uses the googletrans library to translate text between different languages. It prompts the user to input a source language, destination language, and the text to be translated, then outputs the translated result.

<h2>📋 Features</h2>
Translates text from one language to another using Google Translate.

Currently supports a few predefined language names:
afrikaans, hindi, marathi, greek, gujararti (note: "gujararti" is a typo; correct form is "gujarati").

Simple and interactive command-line interface.

<h2>🛠 Requirements</h2>
Python 3.x

googletrans (Install via pip)

bash
Copy
Edit
pip install googletrans==4.0.0-rc1
Note: The latest working version of googletrans is usually 4.0.0-rc1.

<h2>🚀 How to Run</h2>
Save the script as translator.py.

Open a terminal and run:

bash
Copy
Edit
python translator.py
Enter the source and destination languages from the supported list and the text you want to translate.

<h2>🧠 Example</h2>
pgsql
Copy
Edit
Please enter the language from which you are translating the text. hindi  
Please enter the language to which you are translating the text. english  
Please enter the text you want to translate. नमस्ते दुनिया  
Hello world


📄 License
This project is open-source and free to use for educational or personal purposes.
