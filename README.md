# gpt2clip
Python program that captures spoken input using the speech recognition library, combines it with the text currently in the clipboard, and sends the combined text to the OpenAI ChatGPT API to generate a response. The response is then placed in the clipboard and a ding sound is played to indicate success.

Prerequisites
To run this program, you will need to have the following libraries installed:

openai
pyperclip
speech_recognition
winsound
You will also need to replace YOUR_API_KEY in the code with your actual OpenAI API key.

Running the program
To run the program, open a command prompt and navigate to the directory where the file is saved. Then enter python main.py to execute the program.

The program will prompt you to say your question out loud. After you speak, the program will send the combined text of your spoken input and the text in the clipboard to the OpenAI ChatGPT API and copy the response to the clipboard. A ding sound will play to indicate success.
