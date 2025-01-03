# Crypto Analyst Agent

The Crypto Analyst Agent is an AI-powered tool designed to analyze cryptocurrency markets. It reads the top news, delivers key insights, and summarizes recommendations from analysts. The goal is to create a fully autonomous crypto analyst that enhances technical analysis with forecasting models and technical indicators, and incorporates sentiment analysis to capture market emotions.

## Features

- **Web Searcher**: Searches the web for the latest news on a topic.
- **Article Reader**: Reads articles from URLs and extracts key details.
- **Yahoo Finance Agent**: Retrieves detailed information and analysis from Yahoo Finance, including stock prices, analyst recommendations, company info, and news.

## Next Steps

- Enhance technical analysis with forecasting models and technical indicators.
- Incorporate sentiment analysis to capture market emotions.

## Setup

### Requirements

Install the required Python packages using `requirements.txt`:

```bash
pip install -r requirements.txt
```

### Environment Variables

Create a `.env` file in the root directory of your project to store your API keys and other environment variables. The `.env` file should include:

```plaintext
API_KEY=your_api_key_here
```

### Running the Agent

To run the Crypto Analyst Agent, execute the `main.py` script:

```bash
python main.py
```

## Project Structure

```
.
├── main.py
├── agents.py
├── README.md
├── requirements.txt
├── .env
├── .gitignore
```

- `agents.py`: Defines the agents used for web searching, article reading, and Yahoo Finance analysis.
- `main.py`: Main script to run the Crypto Analyst Agent.
- `requirements.txt`: Lists the required Python packages.
- `.env`: Stores environment variables such as API keys.
- `.gitignore`: Specifies files and directories to be ignored by Git.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or new features.

## License

This project is licensed under the MIT License.