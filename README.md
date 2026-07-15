# AI-Website-Summarizer

An intelligent micro-application that summarizes the content of any website using advanced AI models.

## Features

- Fetches website content using a smart scraper.
- Generates concise and comprehensive summaries.
- User-friendly interface built with Gradio.

## Project Structure

- [scraper.py](scraper.py): Handles the data fetching and web scraping.
- [summarizer.py](summarizer.py): Manages the AI model prompt and context for summarization.
- [app.py](app.py): Renders the Gradio user interface.

## Installation

1. Clone the repository.
2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```
   
3. Set up your environment variables in a .env file, including your GROQ_API_KEY.

## Usage

Run the application interface by executing:
```bash
python app.py
```
