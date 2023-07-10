# Data Matrix 32x32 Encoder/Decoder

## Project Description
This repository contains a web application that converts text data into a 32x32 bit data matrix, allowing users to download the image of the matrix. The application also includes a decoding feature where users can upload a data matrix image and retrieve the text within.

The project is designed with an intuitive user interface that makes the process of encoding and decoding text data simple and secure.

## Features

1. **Data Matrix Encoder Page**: This page takes user input text and converts it into a 32x32 data matrix, which can then be downloaded. The maximum input text length is 128 characters.
   
3. **Data Matrix Decoder Page**: This page enables users to upload a data matrix image and decode the text within.

## Usage

- **Encoding**
    - Navigate to the Encoder page.
       
    - Enter your text (maximum of 128 characters) into the input box.
       
    - Click the 'Create' button to convert your text into a 32x32 data matrix. The generated matrix is displayed on the screen.
       
    - After creating the data matrix, a 'Download' button will appear. Click this button to download the image of your matrix.

- **Decoding**
    - Navigate to the Decoder page.
       
    - Click the 'Upload' button and select the image of the data matrix you wish to decode.
       
    - The application will decode the text from the data matrix and display it in a text area on the page.
       
- **Important Note on Image Sharing**

If you're planning to share the data matrix images through apps like WhatsApp or other platforms that compress images, please be aware that the image compression process could reformat the image to reduce its size. This reformatting could distort the encoded data matrix, making it impossible to decode the original text.
To prevent this issue, it is highly recommended to compress or zip the data matrix images before sharing them through these platforms. Doing so will preserve the integrity of the encoded text, allowing it to be decoded correctly at the destination.
Remember, it's always a good practice to verify the decoded text after sharing the data matrix images, especially when using applications or platforms that might modify the image data.

## Installation

No specific installation is required, as the project comprises HTML files that can be opened in any modern web browser. To run it locally, follow these steps:

1. Clone this repository to your local machine using `git clone <repository-link>`.
2. Navigate to the directory containing the cloned project using your terminal.
3. Open the HTML files in your preferred browser.

*Note: Depending on the project setup, you might need a simple HTTP server to run the webpages.*
