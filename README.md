# Azure Text-to-Speech Integration

This application is a simple `Text-to-Speech` Application using `Azure Cognitive Services`. It allows you to convert ` text into speech ` using a selected Azure speech service, and also supports uploading a `.txt` file to read and convert the content to speech.

## Technologies

- HTML5
- CSS
- JavaScript
- jQuery
- Azure Cognitive Services

## Features

- Convert user input text into speech.
- Upload a .txt file and convert its content to speech.
- Utilizes Azure Cognitive Services for text-to-speech conversion.

## Create a Microsoft Azure Text-to-Speech API key using the following link

- [Create Microsoft Azure Text-to-Speech API key](https://docs.merkulov.design/how-to-get-microsoft-azure-tts-api-key/)

## Files

- `index.html`: The main HTML file containing the structure of the app.
- `config.js`: Stores the Azure subscription key and service region for Text-to-Speech service.
- `text-to-speech.js`: Contains the logic for interacting with Azure's Text-to-Speech API and handling file input.
- `styles.css`: Basic styles for the app.

## Usage

- `Input Text`: Enter text into the textarea and click the Speak button to convert it to speech.
- `Upload a Text File`: Use the file input to upload a .txt file. The file's contents will be displayed in the textarea, and you can click Speak to hear it read aloud.
