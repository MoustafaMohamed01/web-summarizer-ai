
# Website Summarizer

This project uses the **Gemini API** to scrape and summarize the content of a website. It extracts the title and main text from a given URL, removes irrelevant elements (like scripts and styles), and generates a concise summary using the Gemini API.

---

## Features

- **Web Scraping**: Extracts the title and main text content from a website.
- **Content Cleaning**: Removes irrelevant HTML elements (e.g., scripts, styles, images).
- **AI Summarization**: Uses the Gemini API to generate a markdown-formatted summary of the website content.
- **IPython Support**: Displays the summary in markdown format in Jupyter notebooks or IPython environments.

---

## Setup

### Prerequisites

- Python 3.7 or higher.
- A Gemini API key (get it from [Google AI Studio](https://makersuite.google.com/)).

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/MoustafaMohamed01/web-summarizer-ai.git
   cd web-summarizer-ai
   ```

2. Install the required dependencies:
   ```bash
   pip install requests beautifulsoup4 python-dotenv google-generativeai IPython
   ```

3. Set up your environment:
   - Create a `.env` file in the project root directory:
     ```bash
     cp .env.example .env
     ```
   - Open the `.env` file and add your Gemini API key:
     ```
     GEMINI_API_KEY=your_api_key_here
     ```

---

## Usage

### Running the Script

To summarize a website, run the following command:
```bash
python web_summarizer_ai.py
```

Or run the Jupyter Notebook `web_summarizer_ai.ipynb` for interactive usage.

---

## Dependencies

The project relies on the following Python packages:
- `requests`: For making HTTP requests to fetch website content.
- `beautifulsoup4`: For parsing HTML and extracting relevant content.
- `python-dotenv`: For loading environment variables from a `.env` file.
- `google-generativeai`: For interacting with the Gemini API.
- `IPython` (optional): For displaying markdown summaries in Jupyter notebooks.

---

## Contributing

Contributions are welcome! If you’d like to contribute, please follow these steps:
1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Commit your changes.
4. Submit a pull request.

---

## Acknowledgments

- [Google AI Studio](https://makersuite.google.com/)
- [LLM Engineering: Master AI, Large Language Models & Agents](https://www.udemy.com/course/llm-engineering-master-ai-and-large-language-models/?couponCode=KEEPLEARNING)
