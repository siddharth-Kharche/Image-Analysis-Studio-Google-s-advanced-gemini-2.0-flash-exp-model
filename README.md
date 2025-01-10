# Gemini Vision Pro

Gemini Vision Pro is an advanced image analysis tool powered by Google’s Gemini AI 2.0 Flash Exp model. This app allows users to upload images, analyze them, and extract insights based on user prompts. It provides features like Optical Character Recognition (OCR), real-time analysis, and high-accuracy results with multi-format support.

## Features

- **Advanced OCR capabilities**: Extract text and analyze images in detail.
- **Multi-format support**: Accepts images in JPEG, PNG, and other common formats.
- **Real-time image analysis**: Instant insights as soon as the image is uploaded.
- **High accuracy results**: Leverage Gemini AI's advanced analysis model for highly accurate insights.

## Installation

1. Clone or download the repository to your local machine.
2. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Set up Google API keys:
   - Create a `.env` file in the project root directory.
   - Add your API key to the `.env` file:

    ```env
    GOOGLE_API_KEY=your_api_key_here
    ```

4. Run the Streamlit app:

    ```bash
    streamlit run app.py
    ```

## Usage

- **Upload an image**: Click on the file uploader to choose an image (JPEG/PNG).
- **Input a query**: Enter the details of what you'd like to analyze in the text area (e.g., "Extract all text and analyze the content in detail...").
- **Analyze the image**: Click the "🔍 Analyze with Gemini AI" button to get detailed insights from the image.
- **Download the results**: After analysis, you can download the results as a `.txt` file.

## App Interface

### Sidebar

- **About**: Brief description of the app and its features.
- **Powered by Gemini AI 2.0**: Credits for the underlying technology.

### Main Content Area

- **Upload Image**: Interface for uploading JPEG or PNG files.
- **Analysis Section**: After uploading, input a query and click "Analyze with Gemini AI" to receive insights.
- **Image Preview**: Displays the uploaded image for reference.

### Results

Once the analysis is complete, the app displays the analysis results in a detailed format, based on the user's query. You can download the results by clicking the "📥 Download Analysis" button.

## Example Queries

- "Extract all text from the image."
- "Analyze the content of the image in detail."
- "What objects are visible in the image?"
  
## Contribution

Feel free to fork this repository and contribute by submitting issues or pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

