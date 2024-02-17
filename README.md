
# Enriching Stock Market Data Via OpenAI's API

## About this Project
This project analyzes the NASDAQ 100 index constituents, focusing on their performance metrics such as price changes over various time frames. It runs on Python and Jupyter Notebook to process and analyze stock market data, then leverages the OpenAI API for advanced data analysis recommendations.

## Data Sources
- nasdaq100.csv: Contains details about the NASDAQ 100 index companies, including symbols, names, headquarters, CIK numbers, and founding dates.

- nasdaq100_price_change.csv: Includes price change percentages of the NASDAQ 100 companies over different periods, ranging from 1 day to the maximum recorded time frame.

## Features
Data ingestion and preprocessing of NASDAQ 100 constituents.
Analysis of stock price changes over various time frames.
Secure API integration with OpenAI for advanced analysis.

## Environmental Variables
The project uses the following environmental variable for secure API access:

`stock_market_project`: Stores the API key for the OpenAI API.

Ensure this environmental variable is set in your development environment before running the project. See Installation below for more instructions. 

## Setup 
**Prerequisites:**
- Python 3.8 or newer.
- An active OpenAI API key for accessing OpenAI services.

**Libraries and Dependencies:**
The project requires the following Python libraries:

`pandas`: For handling and analyzing the dataset.

`openai`: For utilizing the OpenAI API for advanced data processing or analysis tasks.

## Installation
1. **Clone the repository**: Clone or download the project repository to your local machine.
```
git clone https://github.com/your-username/your-repository-name.git
cd your-repository-name
```

2. **Environment Setup**: It is recommended to create a virtual environment for the project to manage dependencies efficiently. You can create a virtual environment using the following command:

`python -m venv venv`

Activate the virtual environment:

On Windows: `venv\Scripts\activate` 

On macOS/Linux: `source venv/bin/activate`

3. **Install Required Libraries**: Install all the required libraries by running the following command in your terminal or command prompt:

`pip install pandas openai`


4. **Set Environmental Variables**: Set the stock_market_project environmental variable with your OpenAI API key. This step varies by operating system:

On Windows: Use the command `set stock_market_project=YOUR_API_KEY`

On macOS/Linux: Use the command export `stock_market_project=YOUR_API_KEY`

5. **Run the Project**: Navigate to the project directory and start Jupyter Notebook to open the .ipynb file:

`jupyter notebook`

Follow the instructions within the notebook to proceed with the data analysis.

## Running the Project

After setting up the environment and installing all dependencies, you can run the Jupyter notebook Stock_market_data_Openai_api.ipynb to start the analysis. Ensure you are in the project directory and have Jupyter Notebook or Jupyter Lab installed to open and run the notebook.

## License

MIT License


Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

Copyright (c) 2024 AHData_Works
