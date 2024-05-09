# FIFA24 Streamlit ChatGPT

An interactive Streamlit app powered by ChatGPT for querying and exploring FIFA 24 game data.

## Overview

This project allows users to interact with the FIFA 24 game data using natural language queries. Users can ask questions about player stats, plot graphs, and explore the dataset in an intuitive chat interface.

## Setup

Follow these steps to set up and run the app locally:

1. Clone this repository:

   ```bash
   git clone https://github.com/your_username/your_repository.git
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Set up your OpenAI API key:
  * Obtain an API key from the OpenAI website.
  * Export your API key as an environment variable:
  ```bash
  export OPENAI_API_KEY="your_openai_api_key"
  ```
4. Run the Streamlit app:
  ```bash
  streamlit run streamlit_app.py
  ```

## Dataset

The dataset used in this project is a Kaggle dataset stored as a pickle file (`fifa.pkl`) inside the `data` folder. This file contains player statistics from the FIFA 24 game.

## Usage

1. Launch the Streamlit app using the steps mentioned above.
2. Enter your queries in the text area provided.
3. Explore the responses provided by the app.
4. Optionally, expand the "Dataframe Preview" section to view a preview of the dataset.

## File Structure

- `streamlit_app.py`: Contains the main code for the Streamlit app.
- `data.py`: Defines functions for loading the FIFA 24 dataset.
- `requirements.txt`: Lists the Python dependencies required for the project.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your_feature_name`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add some feature'`).
5. Push to the branch (`git push origin feature/your_feature_name`).
6. Create a new Pull Request.

## License

This project is licensed under the MIT License - see the `LICENSE` file for details.
