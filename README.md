# Flask Summarization Application

This is a Flask web application that provides text summarization services. The application allows users to upload text or PDF files and generate summaries using extractive or abstractive methods. It also supports summarizing text input directly through the web interface.
  
## Features  
  
- **File Upload Support**: Upload `.txt` and `.pdf` files for summarization.
- **Summarization Methods**:
  - **Extractive Summarization**: Extracts key sentences from text.
  - **Abstractive Summarization**: Generates a summary by paraphrasing the text.
- **Text Input Support**: Directly input text into the web interface for summarization.

## Dependencies

This application requires the following Python packages:

- Flask
- Werkzeug
- Spacy
- NumPy
- PyPDF2
- scikit-learn
- transformers
- langchain

You can install these dependencies using `pip`:

```bash
pip install Flask Werkzeug spacy numpy PyPDF2 scikit-learn transformers langchain
 ```


## Usage/Examples

Web Interface

- Upload a File

Navigate to the home page.
 Select a file (.txt or .pdf).
 Choose the summary type (extractive or   abstractive).
 Click the "Upload and Summarize" button.

- Summarize Text

 Navigate to the home page.
 Enter text in the text box.
 Choose the summary type (extractive or  abstractive).
 Click the "Summarize Text" button.

## Available Endpoints
- /: Displays the main page with file    upload and text input options.
- /summarize_file: Handles file uploads and summarizes the content based on the selected method.
- /summarize_text: Summarizes the provided text based on the selected method.

## Installation



1. **Clone the Repository**

   ```bash
   git clone https://github.com/sarthakm402/summarizer.git

    
## Contributing

Contributions are always welcome!
 Contributions are welcome! If you have suggestions or improvements, please create a pull request or open an issue.

- Fork the repository.

- Create a new branch for your changes.

- Commit your changes.

- Push to your fork.

- Create a pull request.

