# Melody PPT Generator

This Python script generates PowerPoint presentations based on user input. It utilizes Hugging Face's models for natural language processing and image styling.

## How to Use

1. Install the required libraries using `pip install -r requirements.txt`.
2. Run the script using `python main.py`.
3. Follow the instructions and provide the necessary input.

## Project Structure

- **main.py**: Main script for generating PowerPoint presentations.
- **textfiles/**: Directory containing text files for the script.
- **images/**: Directory for storing images used in the presentation.

## Dependencies

- [Python](https://www.python.org/) (>= 3.6)
- [Hugging Face Transformers](https://github.com/huggingface/transformers): Utilized for natural language processing tasks.
- [Pillow](https://pillow.readthedocs.io/): Used for image manipulation and processing.
- [Requests](https://docs.python-requests.org/en/latest/): Used for making HTTP requests to Hugging Face's API.

## APIs

The script uses the following APIs:

1. [Hugging Face Inference API](https://api-inference.huggingface.co/models/NousResearch/Nous-Hermes-2-Mixtral-8x7B-DPO): Utilized for natural language processing tasks.
2. [GoofyAI Cyborg Style XL API](https://api-inference.huggingface.co/models/goofyai/cyborg_style_xl): Used for styling images.

## Important Note

To use the APIs, you need to obtain your own API keys. Replace the placeholder `<YOUR_API_KEY>` in the script with your actual API keys.

Feel free to customize this structure based on your preferences. Once you've organized your project, you can create a new GitHub repository and upload your files.

**License:** This project is licensed under the MIT License.
