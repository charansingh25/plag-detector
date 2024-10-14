
# Plagiarism Detector

A web application designed to analyze text for plagiarism by comparing user input with online sources, providing detailed results with matched links and plagiarism percentage.

## Features

- **Text Input:** Users can input text or documents for analysis.
- **Text Processing:** Automatically converts text to lowercase, removes punctuation, and performs other preprocessing.
- **Similarity Check:** The system compares the processed text with various online sources and identifies similar content.
- **Plagiarism Report:** Displays the plagiarism percentage and provides links to the sources where similar content is found.

## Screenshots

### User Interface

<img src="/public/image-1.png" width="100%">

### Plagiarized Content Example

<img src="/public/image-2.png" width="100%">


## Installation

To run this project locally, follow the steps below:

### 1. Clone the repository

```bash
git clone git@github.com:charansingh25/plag-detector.git
```

### 2. Navigate to the project directory

```bash
cd plag-detector
```

### 3. Install dependencies

Make sure you have Python installed. Then run:

```bash
pip install -r requirements.txt
```

### 4. Start the server

```bash
python main.py
```

## Usage

- Open your web browser and go to `http://localhost:5555`.
- Input the text to be checked for plagiarism.
- Click `Generate Report` to initiate the plagiarism check.
- The results will display the plagiarism percentage and matched sources.

## Technologies Used

- **Python**: Backend processing and text analysis.
- **Flask**: Web framework for creating the application.
- **BeautifulSoup**: For web scraping and content comparison.
- **HTML/CSS**: Frontend interface.
- **JavaScript**: Dynamic functionalities on the webpage.
