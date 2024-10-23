# Project Title: Enhanced Video Search and Q&A with RAG & Langchain

## Overview
This project uses Retrieval-Augmented Generation (RAG) in combination with Langchain to provide an AI-powered assistant capable of analyzing YouTube video transcripts. By leveraging the capabilities of RAG, the assistant efficiently retrieves relevant information from video transcripts to answer user questions in a concise and contextually aware manner.

## Features
- **Retrieval-Augmented Generation**: Searches through YouTube video transcripts to enhance the response accuracy.
- **Interactive Question Answering**: Allows users to query video content, providing concise answers with relevant video context.
- **Metadata Access**: Provides the video ID to ensure traceability of the response source.

## Requirements
- Python 3.7+
- Langchain library
- OpenAI API key
- MoviePy (for video processing tasks)

## Installation
```sh
pip install langchain openai moviepy chromadb
```

## Usage
1. Set your OpenAI API key as an environment variable.
2. Run the script to analyze video transcripts and answer user queries.

## License
This project is open source and available under the MIT License.

