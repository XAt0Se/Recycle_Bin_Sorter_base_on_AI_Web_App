
# Recycle Bin Sorter Based on AI - Web App

This project is a web application designed to help users sort recyclable items using an AI model. By uploading images of waste items, the AI model will classify them into the appropriate recycling categories.

## Features

- **AI-Powered Classification**: Uses AI to identify and sort items into recyclable categories.
- **Web-Based Interface**: Easy-to-use interface for uploading and viewing results.
- **Categorized Storage**: Organizes sorted items into folders for each recycling category.

## Project Structure

- `app.py`: The main file that runs the web application using Flask.
- `recycle_bin.py`: Contains the logic for processing and classifying the images.
- `folders/`: This directory holds the sorted images for each category.
- `static/`: Contains static files (CSS, JS, images).
- `templates/`: HTML templates for rendering the web pages.
- `__pycache__/`: Python cache files (auto-generated).

## Requirements

- Python 3.x
- Flask
- TensorFlow (or any AI library used for classification)
- Other dependencies can be installed from `requirements.txt` (if provided).

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/recycle-bin-sorter-ai.git
   ```

2. Navigate to the project directory:

   ```bash
   cd recycle-bin-sorter-ai
   ```

3. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Run the application:

   ```bash
   python app.py
   ```

5. Open your browser and navigate to `http://localhost:5000`.

## Usage

- Upload an image of the waste item through the web interface.
- The AI model will classify the item and show the result.
- The item will be stored in its respective category folder in the `folders/` directory.

## Contribution

Feel free to open issues or contribute to the project by submitting a pull request.

## License

This project is licensed under the MIT License.
