# Text-to-Speech Project with Python and IBM Watson

This project demonstrates how to convert text into spoken audio using Python and the IBM Watson Text-to-Speech service. With this project, you can leverage the power of IBM Watson's natural language processing capabilities to transform text into lifelike speech.

## Prerequisites

Before getting started, ensure you have the following prerequisites:

- Jupyter Notebook installed on your machine
- IBM Cloud account (sign up at [IBM Cloud](https://cloud.ibm.com/))
- IBM Watson Text-to-Speech service credentials (obtain them from the IBM Cloud dashboard)

## Installation

1. Clone or download this repository.
2. Install the required Python packages by running the following command:

   ```bash
   pip install -r requirements.txt
   ```

3. Update the `config.ini` file with your IBM Watson Text-to-Speech service credentials. Fill in the `api_key` and `url` fields with your specific information.

## Usage

To use the text-to-speech functionality, follow these steps:

1. Open `main.py` in your preferred Python IDE or editor.
2. Modify the `text` variable in the code to the desired text you want to convert to speech.
3. Run the script using the following command:

   ```bash
   python main.py
   ```

4. The program will connect to the IBM Watson Text-to-Speech service and generate an audio file based on the provided text.
5. Once the process is complete, the generated audio file will be saved to the `output` directory.

## Customization

Feel free to customize and extend this project according to your specific needs. Some possible enhancements could include:

- Adding support for different languages and voices
- Implementing text input from a file or user input
- Creating a user-friendly interface for easier interaction

## Resources

- [IBM Watson Text-to-Speech Documentation](https://cloud.ibm.com/docs/text-to-speech)


---
