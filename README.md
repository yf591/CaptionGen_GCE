# CaptionGen_GCE

**CaptionGen_GCE** is an image captioning application that runs on Google Colab's GPU environment, utilizing the InstructBLIP model. It allows you to select image folders from your local environment or Google Drive and generate detailed captions.


## Features

*   **Powered by InstructBLIP**: Utilizes the high-performance vision-language model InstructBLIP to generate detailed image captions.
*   **Optimized for Google Colab Pro's GPU Environment**: Leverages powerful GPUs for fast caption generation.
*   **Easy to Use**: Generate captions in just a few steps on a Google Colab notebook.
*   **Folder Selection from Local/Google Drive**: Upload images from your local environment or select a folder from Google Drive.
*   **Batch Processing**: Process multiple images at once for efficient caption generation.
*   **Caption Saving**: Saves generated captions as text files associated with image filenames.


## Requirements

*   **Google Colab Pro**: Requires a GPU runtime (T4 or higher recommended).
*   **Browser**: A browser that supports Google Colab, such as Google Chrome, Firefox, or Safari.


## Setup

1. **Subscribe to Google Colab Pro**: This application requires Google Colab Pro's GPU environment.
2. **Clone the Repository**: Clone this repository using the following command:
    ```bash
    git clone https://github.com/yf591/CaptionGen_GCE.git
    ```
3. **Run the Notebook on Google Colab**: Open `caption_gen_app.ipynb` in Google Colab and follow the instructions to run it.


## Usage

1. **Install Required Libraries**: Run the first cell of the notebook to install the necessary libraries.
2. **Select Image Folder**:
    *   **Uploading from Local**:
        1. Run the fourth cell.
        2. Enter `1` and press Enter.
        3. Click the file upload button that appears and select a zipped file containing the folder with images.
    *   **Selecting from Google Drive**:
        1. Run the fourth cell.
        2. Enter `2` and press Enter.
        3. Enter the path to the image folder in your Google Drive when prompted (e.g., `MyFolder/Images`).
3. **Generate Captions**: Run the fifth cell to generate captions. The generated captions will be saved as text files associated with the image filenames in the `output_captions` folder.


## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).


## Disclaimer

The author is not responsible for any damage caused by the use of this application. Please use it at your own risk.