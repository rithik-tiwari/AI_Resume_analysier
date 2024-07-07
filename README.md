# AI Resume Analysis

This project utilizes artificial intelligence techniques to analyze resumes uploaded by users. The system converts uploaded PDF resumes into images and extracts key values and keywords using Natural Language Processing (NLP) techniques. This analysis provides valuable insights into the skills, education, experience, and other relevant details present in the resumes.

## Features

- **PDF to Image Conversion**: Automatically converts uploaded PDF resumes into image format for processing.
- **NLP-based Analysis**: Uses NLP models to extract key information such as skills, education history, work experience, and certifications from the resume text.
- **Keyword Extraction**: Identifies important keywords and phrases that are useful for categorizing and summarizing resume content.
- **User-Friendly Interface**: Simple and intuitive web interface for users to upload their resumes and view analysis results.

## How It Works

1. **Upload Resume**: Users upload their PDF resumes through the web interface.
2. **PDF Conversion**: The system converts the uploaded PDF resume into an image format (e.g., PNG or JPEG).
3. **Text Extraction**: Utilizes NLP techniques to extract structured information from the resume text, including skills, education, experience, and more.
4. **Keyword Analysis**: Identifies and extracts key keywords and phrases that are relevant for resume analysis and categorization.
5. **Display Results**: Displays the extracted information and keywords in a structured format, providing users with insights into their resume content.

## Technologies Used

- Python
- Flask (for web interface)
- Tesseract OCR (for text extraction from images)
- SpaCy, NLTK (for NLP processing)
- Pillow (Python Imaging Library for image processing)

## Installation

1. Clone the repository
2. Install dependencies
3. Run the application
4. Access the application at `http://localhost:5000` in your web browser.

## Contributing

Contributions are welcome! If you would like to contribute to this project, please fork the repository and submit a pull request with your proposed changes.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Special thanks to [SpaCy](https://spacy.io/) and [NLTK](https://www.nltk.org/) for their excellent NLP libraries.
- Inspired by the need to automate and streamline resume analysis processes.




