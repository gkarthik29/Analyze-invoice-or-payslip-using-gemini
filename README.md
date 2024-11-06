# Receipt and Payslip Data Extraction using Google Gemini

This project demonstrates how to extract data from receipts and payslips using Google Gemini's multimodal capabilities. It leverages the `google-generativeai` library to interact with the Gemini API, enabling the extraction of key information from images.

## Functionality

The project provides the following features:

* **Image Input:** Accepts receipts and payslips as input in image format (e.g., PNG, JPG).
* **Data Extraction:** Uses Google Gemini to extract relevant data points from the images.
* **Structured Output:** Presents the extracted data in structured formats such as key-value pairs (dictionary) and JSON.
* **Customization:** Allows customization of the system prompt and user prompt to fine-tune data extraction.


## Usage

1. Install the necessary libraries:
    - bash !pip install -q -U google-generativeai
    
2. Set up your Google Generative AI API key:

   * Obtain an API key from Google Cloud Console.
   * In Colab, use the following code to store the key:
       - python from google.colab import userdata userdata.set('GAPI_KEY', 'YOUR_API_KEY')

3. Run the code provided in the notebook.

4. Specify the image path and prompts:
   * Modify `image_path` to point to your receipt or payslip image.
   * Adjust `system_prompt` and `user_prompt` to control data extraction.

5. Execute the `gemini_output` function to extract and display the data.

## Examples

The provided code includes examples of extracting data from a sample payslip.

## Requirements

* Python 3.7 or higher
* Google Generative AI library
* Active Google Generative AI API key

## Acknowledgments

* **Google Gemini:** For providing the powerful multimodal model.
* **Google Colab:** For offering the platform to run this project.
