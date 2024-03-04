# Rag File Preprocessor

The Rag File Preprocessor is a Python script for preparing text files for RAG-based information retrieval. It utilizes operatios from the Natural Language Toolkit (NLTK), such as tokenization, part-of-speech tagging, named entity recognition, and lemmatization. The script also offers functionality for extracting and anonymizing PII and phone numbers, ensuring data privacy and compliance.

## Key Features

- **Tokenization**: Splits text into tokens (words and sentences).
- **Part-of-Speech Tagging**: Assigns parts of speech to each token, such as verb, noun, adjective, etc.
- **Named Entity Recognition**: Identifies and classifies named entities in text into predefined categories.
- **Lemmatization**: Reduces words to their base or dictionary form.
- **Phone Number Extraction and Anonymization**: Detects and anonymizes phone numbers in text.

## Prerequisites

Before you begin, ensure you have the following prerequisites installed on your system:

- Python 3.x
- Natural Language Toolkit (NLTK)

You can install NLTK using pip: 

'''pip install nltk'''

## Installation

Clone the repository to your local machine to get started:

'''git clone https://github.com/Nathandryer/rag-file-preprocessor.git
cd text-preprocessing-utility'''

## Usage

Run the script using the following command:

'''python main.py <input_file> --format <output_format> --logging'''

Replace `<input_file>` with the path to your text file, and `<output_format>` with either `json` or `csv` depending on your desired output format.

## Contributing

Contributions to the Text Preprocessing Utility are welcome!

1. Fork the repository.  
2. Create a new branch for your feature or fix.
3. Submit a pull request with a detailed description of your changes.

## Contact  

- **Nathan Dryer**
- GitHub: [nathandryer](https://github.com/nathandryer)
- Website: [www.nathandryer.com](https://www.nathandryer.com)  

## License

This project is licensed under the MIT License - for more information, refer to the LICENSE file.