# automatic-umbrella
New York Times Article Searcher

## Overview

The New York Times News Explorer is a web application that allows users to retrieve news articles from The New York Times using their API. Users can search for articles based on topics, choose the number of associated articles to display (1, 5, or 10), and optionally narrow down their search by specifying date ranges.

## Features

- **Search by Topic:** Users can enter specific topics of interest to retrieve relevant news articles.

- **Select Number of Articles:** Users have the flexibility to choose the number of associated articles they want to view (1, 5, or 10).

- **Date Range Filtering:** Optionally, users can narrow down their search by specifying the dates between which they'd like to explore articles.

## Getting Started

Follow these steps to set up and run the New York Times News Explorer locally:

1. Clone the repository:

    ```bash
    git clone git@github.com:Sooey-99/automatic-umbrella.git
    ```

2. Navigate to the project directory:

    ```bash
    cd automatic-umbrella
    ```


3. Obtain API Key:

    - Visit [The New York Times Developer Portal](https://developer.nytimes.com/) to get your API key.
    - Create a `.env` file in the root directory and add your API key:

        ```env
        REACT_APP_NYT_API_KEY=your-api-key
        ```

5. Start the application:

    ```bash
    npm start
    ```

6. Open the application in your browser and navigate to view the result.

## Usage

1. Enter a topic in the search bar.
2. Choose the number of associated articles (1, 5, or 10).
3. Optionally, specify date ranges to narrow down your search.
4. Click the "Search" button to retrieve and display news articles.

## Technologies Used

- React
- Axios (for API requests)
- Bootstrap (for styling)
- JavaScript

## Contributing

Contributions are welcome!

## License

This project is licensed under the [MIT License] Copyright (c) 2024 Émile Siou.

## Acknowledgments

- Thanks to The New York Times for providing the API.

## Contact

For inquiries, please contact [emileluc99@outlook.com].


## Images
![Alt text](<Screenshot 2024-01-21 at 20.49.17.png>)
