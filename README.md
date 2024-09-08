
# Multilingual AI Voice Assistant APP
It is a project through which anybody can have a voice chat with AI Assistant in any language.

I made this project using langchain which is a popular and powerful framework for making AI base applications. I have used Groq API keys for the llm which is llama 3.1 8b.

I have used streamlit for the web interface of this application.


## Live Video Overview

https://github.com/user-attachments/assets/5c99769f-9036-4ab6-a6bd-2956b05c406c
## Working

The user will click on the mic icon and ask something. 

In the backend, the text is going to be extracted from the user voice using OpenAI's Whisper model and send it to the AI model for the response,

 and then that response will converted into voice using pyttsx3 library and plays it.

![voice assistant workflow](https://github.com/user-attachments/assets/62b385d4-88db-4b5a-818c-8e9719ff7e44)

## Future Improvements

1-Include Agentic workflow to handle complex tasks

2-Add memory element to make something like JARVIS.

## 🔗 Links

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/usman-tahir-676a51291)




## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`GROQ_API_KEY`

