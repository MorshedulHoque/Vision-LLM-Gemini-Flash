# Gemini LLM Image Assistant

## Project Overview
This application harnesses the capabilities of Google's Gemini model to describe images and generate content based on user prompts. Built with Streamlit, this application allows users to upload an image and optionally provide a text prompt, receiving detailed descriptions or generated content in response.

## Features

| Feature               | Description                                                              |
|-----------------------|--------------------------------------------------------------------------|
| Environment Variables | Securely loads necessary credentials using `dotenv`.                     |
| Streamlit Interface   | Provides a user-friendly, web-based interface for interaction.           |
| Image Processing      | Supports uploading and processing images in JPG, PNG, and JPEG formats.  |
| Gemini 1.5 Flash Model| Utilizes the advanced capabilities of the Gemini 1.5 Flash model.        |
| Dynamic Content Generation | Generates textual content based on image and optional text input.      |

## How It Works
1. **Setup Environment**: Manages API keys and sensitive data securely using Python's `dotenv` package.
2. **Streamlit Framework**: Utilizes Streamlit to create an interactive web application.
3. **Image and Text Processing**: Integrates image processing and text generation, using the Gemini 1.5 Flash model from Google's generative AI suite.

## Getting Started
To use this application, follow these steps to set up your environment and run the app.

### Prerequisites
- Python 3.8+
- Streamlit
- dotenv Python package
- PIL (Pillow for image handling)

### Installation
1. Clone the repository:   
```bash
git clone https://github.com/YourGitHubUsername/YourRepositoryName.git
```  
2. Install dependencies:
```bash
pip install -r requirements.txt
```  
3. Set up the .env file with your Google API key:
```bash
echo GOOGLE_API_KEY=your_api_key_here > .env
```  
4. Launch the Streamlit application:
```bash
streamlit run app.py
```  


## Usage
- Start the application and navigate to the provided local URL.
  ![benchmark](https://github.com/MorshedulHoque/Vision-LLM-Gemini-Flash/blob/main/images/1.PNG)
- Upload an image using the file uploader.
  ![benchmark](https://github.com/MorshedulHoque/Vision-LLM-Gemini-Flash/blob/main/images/2.PNG)
- Optionally, enter a text prompt related to the image.
  ![benchmark](https://github.com/MorshedulHoque/Vision-LLM-Gemini-Flash/blob/main/images/5.png)
- Click 'Tell me about the image' to process and generate content. It can generate content with or without a prompt. 
  ![benchmark](https://github.com/MorshedulHoque/Vision-LLM-Gemini-Flash/blob/main/images/3.png)

  ![benchmark](https://github.com/MorshedulHoque/Vision-LLM-Gemini-Flash/blob/main/images/4.PNG)

  ![benchmark](https://github.com/MorshedulHoque/Vision-LLM-Gemini-Flash/blob/main/images/6.png)


## Live Demo
A live demo can be accessed here: [Live Demo](https://vision-llm-gemini-flash.onrender.com/)

Note: The demo may experience latency as it runs on a low-configured free server.

## Acknowledgments
-Google AI for the Gemini language model.
-Streamlit for the web application framework.
-Pillow library for handling image data.

## Contributions
Contributions are highly encouraged! Please fork the project, make changes, and submit a pull request for review.

## Contact
Feel free to contact me for any queries or suggestions at `asmmorshedulhoque@gmail.com`.

## Version
This application is currently at version 1.0.
   
