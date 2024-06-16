# News Detector

News Detector is a web application designed to help users determine the authenticity of news articles. By leveraging advanced AI algorithms, this tool provides users with accurate insights into whether the news is real or fake. This repository contains the source code and instructions to set up and run the News Detector web application.

## Features

- User-friendly interface
- AI-powered news authenticity detection
- Responsive design for various devices
- Easy-to-use form for submitting news headlines or articles

## Technologies Used

- HTML5 and CSS3 for the front-end
- Python and Flask for the back-end
- AI and machine learning algorithms for news detection

## Installation

### Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.7 or higher installed on your machine
- `pip` package installer

### Clone the Repository

```bash
git clone https://github.com/shahram8708/news-detector.git
cd news-detector
```

### Create a Virtual Environment

Create and activate a virtual environment:

```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

### Install Dependencies

Install the required Python packages:

```bash
pip install -r requirements.txt
```

## Running the Application

To start the Flask application, run:

```bash
export FLASK_APP=app.py
export FLASK_ENV=development
flask run
```

Navigate to `http://127.0.0.1:5000` in your web browser to access the application.

## Project Structure

```
news-detector/
├── static/
│   ├── styles.css
├── templates/
│   ├── base.html
│   ├── index.html
│   ├── result.html
├── app.py
├── requirements.txt
├── README.md
```

- `static/`: Contains static files such as CSS.
- `templates/`: Contains HTML templates.
- `app.py`: Main Flask application file.
- `requirements.txt`: Lists required Python packages.
- `README.md`: Project documentation.

## Usage

1. Open the application in your browser.
2. Enter a news headline or article in the input field.
3. Click "Detect" to analyze the news.
4. View the results indicating whether the news is real or fake.

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Create a Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- The Flask framework for providing the web framework
- OpenAI for AI and machine learning support
- All contributors who helped in improving this project
