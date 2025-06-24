# Security Log Analyzer Bot (SLAB)

The Security Log Analyzer Bot is a tool designed to analyze security logs and provide insights into potential security threats. It uses a combination of natural language processing and machine learning algorithms to identify patterns and anomalies in the logs. The bot was evaluated using different LLMs (Large Language Models) and retrieval techniques, specifically Base, Parent Document Retrieval, and Ensemble methods, to determine the most effective approach for security log analysis. The evaluation methodology involved the following steps:
1. Data Collection: Security logs were collected from various sources, including bro/zeek, apache web server, healthapp, and os logs.
2. Data Preprocessing: The collected logs were preprocessed to remove any unnecessary information and to convert them into a format suitable for analysis.
3. Model Training: The preprocessed logs were used to train the LLMs and retrieval techniques.
4. Model Evaluation: The trained models were evaluated using the RAGAS framework, which assesses the model's ability to retrieve relevant information and provide accurate answers.
5. Comparison: The performance of the different LLMs and retrieval techniques was compared to determine the most effective approach.

## Features

* Analyzes security logs from various sources, including bro/zeek, apache web server, healthapp, and os logs
* Uses natural language processing and machine learning algorithms to identify patterns and anomalies
* Provides insights into potential security threats and recommends actions to take
* Utilizes a combination of retrieval techniques, including Base, Parent Document Retrieval, and Ensemble methods, to improve the accuracy of the analysis
* Evaluates the performance of the bot using the RAGAS framework, which assesses the bot's ability to retrieve relevant information and provide accurate answers.

## Installation

To install the Security Log Analyzer Bot, follow these steps:

1. Clone the repository to your local machine
2. Install the required dependencies, including Python and the necessary libraries
3. Configure the bot to connect to your security log sources

## Usage

To use the Security Log Analyzer Bot, follow these steps:
1. Run the bot using the command line interface
2. Provide the bot with the security logs to analyze
3. Review the insights and recommendations provided by the bot
4. Evaluate the performance of the bot using the RAGAS framework, which assesses the bot's ability to retrieve relevant information and provide accurate answers
5. Compare the performance of the different LLMs and retrieval techniques to determine the most effective approach.

## Contributing

If you would like to contribute to the Security Log Analyzer Bot, please fork the repository and submit a pull request with your changes. The bot's evaluation methodology and performance comparison can be found in the Security_Log_Analyzer_Bot_RAGAS.ipynb file.
