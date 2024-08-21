# Extractive Text Summarization

## Overview
This Python script, designed to run in Google Colab, implements an extractive text summarization technique specifically tailored for medical reports. It's particularly useful for healthcare professionals, medical researchers, and data scientists working with clinical narratives who need to quickly extract key information from longer medical texts - though the general concept can be modified and used for any texts.

## Features
- **Text Preprocessing**: Removes special characters and converts text to lowercase for standardization.
- **Sentence Tokenization**: Splits the text into individual sentences for analysis.
- **Key Term Identification**: Uses a predefined list of medical terms to identify important sentences.
- **Extractive Summarization**: Selects the most relevant sentences based on the presence of key terms.
- **Customizable Summary Length**: Allows users to specify the number of sentences in the summary.

## Requirements
- Google Colab environment
- Python 3.x
- No additional libraries required beyond Python's standard library

## Usage
1. Open the script in Google Colab.
2. Run the cells in order, following the instructions in the notebook.
3. The script will guide you through:
   - Importing necessary Python modules
   - Defining preprocessing and summarization functions
   - Applying the summarization technique to a sample medical text

## Configuration
You can modify the following parameters in the notebook:
- `key_terms`: List of medical terms used to identify important sentences
- `num_sentences`: Number of sentences to include in the summary (default is 3)

## Output
The script generates:
1. A summary of the input medical text
2. Both the original text and the summary are displayed for comparison

## Limitations
- Uses a simple rule-based approach, which may not capture all nuances in complex medical texts
- Sentence tokenization is based on periods, which may not work perfectly for all types of medical abbreviations
- The effectiveness of the summary depends on the predefined list of key terms

## Contributing
Contributions, issues, and feature requests are welcome. Feel free to suggest improvements or extensions to the summarization technique.

## License
This project is open-source and available under the MIT License.

## Disclaimer
This tool is for research and educational purposes only. It should not be used for clinical decision-making without proper medical review and validation.
