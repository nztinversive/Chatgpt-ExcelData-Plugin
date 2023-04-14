# Excel API and Plugin

This project provides a simple way to interact with an Excel spreadsheet through an API and a plugin for ChatGPT. The Excel API serves an Excel file, allowing users to fetch data from the first sheet in the workbook. The plugin is designed to work with ChatGPT, allowing users to interact with the spreadsheet using natural language queries.

## Getting Started

These instructions will help you set up the project on your local machine for development and testing purposes.

### Prerequisites

- Python 3.6 or later
- [Flask](https://flask.palletsprojects.com/en/2.1.x/)
- [openpyxl](https://openpyxl.readthedocs.io/en/stable/)
- [pandas](https://pandas.pydata.org/)
- [requests](https://docs.python-requests.org/en/latest/)

You can install the required packages using pip:

```bash
pip install Flask openpyxl pandas requests


## Running the Excel API
Navigate to the Excel API directory and run the main.py file:

cd excel-api
python main.py

The API will start running on http://0.0.0.0:8080.

Running the Plugin
Navigate to the plugin directory and run the main.py file:

cd plugin
python main.py

Usage
Once both the Excel API and plugin are running, you can use ChatGPT to interact with the Excel spreadsheet by querying the plugin.

Example usage:


Copy 
User: Get the data from the Excel file.
ChatGPT can then use the plugin to fetch data from the Excel file served by the Excel API.

Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

License
This project is licensed under the MIT License. See the LICENSE file for details.

vbnet
Copy 


You can create a new file named `README.md` in your project's root directory and paste the content above. Make any adjustments as needed, and then you can commit and push the changes to your GitHub repository.
