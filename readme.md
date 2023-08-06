# MultiPDF Chat App

## Introduction

---
Welcome to the AI Chat Bot! This project aims to create a chatbot that can take in PDFs as a knowlegde base and answer queries related to it. It can answer questions about any topic that is covered in the PDF document.It can retrieve information from the document quickly and efficiently.

The MultiPDF Chat App is a Python application that allows you to chat with multiple PDF documents. You can ask questions about the PDFs using natural language, and the application will provide relevant responses based on the content of the documents. This app utilizes a language model to generate accurate answers to your queries. Please note that the app will only respond to questions related to the loaded PDFs.

[streamlit-app-2023-08-05-23-08-32.webm](https://github.com/shivraj-murali/chatbot-ai/assets/102913051/8ba6aefa-8504-4395-a311-e9e18cf2df0b)

## How It Works

---

When the user asks a question, the bot first breaks the question down into smaller chunks. These chunks are then passed to OpenAI's LLM, which generates a response. The response is then passed to the FAISS index, which retrieves the most relevant text from the document. This text is then combined with the LLM's response to generate the final answer

## Dependencies and Installation

---

To install the MultiPDF Chat App, please follow these steps:

1. Clone the repository to your local machine.

2. Install the required dependencies by running the following command:

   ```
   pip install -r requirements.txt
   ```

3. Obtain an API key from OpenAI and add it to the `.env` file in the project directory.

```commandline
OPENAI_API_KEY=your_secrit_api_key
```

## Usage

---

To use the MultiPDF Chat App, follow these steps:

1. Ensure that you have installed the required dependencies and added the OpenAI API key to the `.env` file.

2. Run the `main.py` file using the Streamlit CLI. Execute the following command:

   ```
   streamlit run app.py
   ```

3. The application will launch in your default web browser, displaying the user interface.

4. Load multiple PDF documents into the app by following the provided instructions.

5. Ask questions in natural language about the loaded PDFs using the chat interface.

## Contributing

---

You are welcome to contribute to the project. To contribute to the project follow the following steps

1. Fork the repository.

2. Create a new branch for your feature or bug fix.

3. Make your changes and commit them with descriptive messages.

4. Push your changes to your forked repository.

5. Open a pull request, explaining the changes you have made.

## Contact

For any questions or inquiries, please feel free to reach out to:

- Name: Shivraj Murali
- Email: shivrajmurali8503@gmail.com

## License

---

The MultiPDF Chat App is released under the [MIT License](https://opensource.org/licenses/MIT).



