# Movie Data Sourcing Project

## Project Description
This project is focused on extracting and merging data from The New York Times API and The Movie Database API. The goal is to create a comprehensive dataset that can be used for building a movie recommendation system. This involves fetching movie reviews and related movie details, processing the data, and preparing it for use in natural language processing applications.

## Installation

### Prerequisites
- Python 3.x
- pip (Python package installer)

### Dependencies
Install the required Python packages using pip:
```bash
pip install requests pandas
```

### Setup
1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/JCLavieri/data-sourcing-challenge.git
   ```
2. Navigate to the cloned repository:
   ```bash
   cd data-sourcing-challenge
   ```
3. Add your API keys for The New York Times and The Movie Database to the `.env` file.

## Usage
Run the script to fetch and process the data:
```bash
python retrieve_movie_data.py
```
This will generate a CSV file with the combined data from both APIs.

## Contributing
Contributions to this project are welcome. Please fork the repository and submit a pull request with your changes.

## Acknowledgments
- The New York Times API for providing access to movie reviews.
- The Movie Database API for offering detailed movie information.

