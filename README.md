# Billboard Top 100 Playlist Creator

This Python application prompts the user to input a particular date, then sends a request to the Billboard Top 100 website to obtain the 100 most popular songs on that date. It then uses BeautifulSoup to scrape the webpage and extract the names of the songs. Finally, using the Spotipy library, the application communicates with the Spotify API to create a playlist on the user's account with the top 100 songs obtained.

To get your own USER_ID and USER_SECRET (both required),you wiil need to:

    1. Go to https://developer.spotify.com/
    2. Log into your account.
    3. Go to the dashboard and select Create App.
    4. Set your app details up and set the redirect URL to "http://example.com/".

The first time you run the program it will open a browser tab with the Spotify Web API authorization page, select "agree" and it will redirect
you to the redirect URL you set your app to (http://example.com/). Copy the URL of the example.com website, and paste it into the token.txt file
that will be automatically created into your project.

## Installation

1. Clone this repository to your local machine.

    git clone https://github.com/your-username/playlist-creator.git

2. Install the required packages by running the following command:

    pip install -r requirements.txt


## Usage

1. Run the application by running the following command in your terminal:
    python main.py

2. Enter the date for which you would like to create the playlist in the format YYYY-MM-DD.

3. Follow the instructions provided by the application.


## Contributing

If you would like to contribute to this project, please create a pull request and we will review your changes. We welcome all contributions!
