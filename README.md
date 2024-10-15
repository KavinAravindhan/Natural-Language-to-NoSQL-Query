# Natural Language to NoSQL Query Using LLMs

![Development Status](https://img.shields.io/badge/status-under%20development-yellow)
![License](https://img.shields.io/badge/license-MIT-blue)
![Python](https://img.shields.io/badge/Python-3.0%2B-purple)
![LLM](https://img.shields.io/badge/LLM-brightgreen)
![NoSQL](https://img.shields.io/badge/NoSQL-orange)

This project leverages large language models (LLMs) to convert natural language English queries into NoSQL syntax. It then retrieves the query results and translates them back into human-readable English text. This tool aims to simplify database interactions by allowing users to query NoSQL databases directly in plain English

## Key Features

- Converts English queries into NoSQL format using powerful LLMs.
- Uses OpenAI, TogetherAI, and HuggingFace APIs to handle language translation and query processing.
- Allows users to interact with NoSQL databases without needing to know query syntax.

## Technologies Used 🛠️
- **Python** (3.0+)
- **APIs**: 
  - OpenAI 
  - TogetherAI 
  - HuggingFace
- **NoSQL Database**: MongoDB 

## Installation and Setup

> **Note:** This project is currently in the development phase. Be sure to replace API keys with your own to try out the initial files.

1. Clone the repository:
   ```bash
   git clone https://github.com/KavinAravindhan/Natural-Language-to-NoSQL-Query.git
   ```
2. Add your API keys in the respective configuration file:
   - OpenAI API key
   - TogetherAI API key
   - HuggingFace API key
   - MongoDB Connection Server URL

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
