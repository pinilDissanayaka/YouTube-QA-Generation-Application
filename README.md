# YouTube-QA-Generation-Application

This repository contains a Python application that generates questions and answers from YouTube video transcripts. The application leverages LangChain for language processing, Google PaLM 2 for generating questions and answers, and Pinecone for vector database management.

## Features
- Fetch transcripts from YouTube videos using the video URL.
- Generate questions based on the video transcript.
- Answer user questions based on the video content.
- Use LangChain for language processing tasks.
- Utilize Google PaLM 2 for advanced question and answer generation.
- Manage and search video transcripts using Pinecone vector database.

## Getting Started

### Prerequisites
- Python 3.7 or higher
- Google PaLM 2 API Key
- Pinecone API Key

### Installation
1. Clone the repository:
    ```
    git clone https://github.com/yourusername/youtube-qa-gen.git
    cd youtube-qa-gen
    ```

2. Create and activate a virtual environment:
    ```
    python3 -m venv venv
    source venv/bin/activate   # On Windows, use `venv\Scripts\activate`
    ```

3. Install the required dependencies:
    ```
    pip install -r requirements.txt
    ```

### Configuration
1. Create a `.env` file in the root directory and add your API keys:
    ```
    GOOGLE_PALM2_API_KEY=your_google_palm2_api_key
    PINECONE_API_KEY=your_pinecone_api_key
    ```

### Usage
1. Run the application:
    ```
    python app.py
    ```

2. Follow the prompts to input the YouTube URL and receive generated questions and answers.

## Contributing
Contributions are welcome! Please fork the repository and submit pull requests.

## License
This project is licensed under the MIT License.

## Acknowledgments
- [LangChain](https://github.com/langchain-ai/langchain)
- [Google PaLM 2](https://developers.google.com/palm)
- [Pinecone](https://www.pinecone.io/)
