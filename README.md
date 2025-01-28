# Nutrilytics

## Description

A simple web application that allows users to upload images and interact with the content. Extract nutritional information from images using OCR and Generative AI.

## Genarative AI features

- **OCR and Text Extraction**: Extract text from nutrition facts labels.
- **Nutritional Analysis**: Get detailed nutritional information from the extracted text.
- **Text Generation**: Generate text based on the extracted nutritional information.

## Installation

1. Clone the repository:

    ```sh
    git clone https://github.com/45H15H/Nutrilytics.git
    ```

2. Navigate to the project directory:

    ```sh
    cd Nutrilytics
    ```

3. Create a virtual environment:

    ```sh
    python -m venv .env
    ```
4. Activate the virtual environment:

    ```sh
    source .env/bin/activate
    ```

5. Upgrade pip:

    ```sh
    pip install --upgrade pip
    ```

6. Install dependencies:

    ```sh
    pip3 install -r requirements.txt
    ```

7. Create a .env file in the project directory and add the following environment variables:

    ```sh
    SECRET_KEY=your_secret_key
    ```

## Usage

1. Start the flask application:

    ```sh
    python app.py
    ```

2. Open a web browser and navigate to `http://localhost:5000/`.

3. Enter your API key and upload an image to extract nutritional information.

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.