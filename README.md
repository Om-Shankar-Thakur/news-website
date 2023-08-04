
# News App

This is a simple News App web application that allows users to browse news articles based on different categories such as IPL, Finance, and Politics, or search for news by entering a specific keyword. The app fetches data from the News API and displays the news articles in a user-friendly format.

## Features

- Browse news articles by categories: IPL, Finance, and Politics.
- Search for news articles using a keyword.
- Click on a news card to open the full article in a new tab.
- Toggle between Dark and Light mode for a personalized viewing experience.

## Technologies Used

- HTML5
- CSS3
- JavaScript
- Fetch API for making API calls
- News API for fetching news data
- Google Fonts for font styles

## How to Use

1. Clone the repository or download the project files.
   ```bash
     git clone https://github.com/your-username/news-app.git
2. Open the index.html file in your web browser.

3. The app will load with news articles related to "Technology" by default.

4. Browse news articles using the navigation links (IPL, Finance, and Politics) or use the search bar to enter a keyword and search for specific news articles.

5. Click on any news card to view the full article in a new tab.

6. Toggle between Dark and Light mode by clicking the "Toggle Dark/Light Mode" button in the navigation bar.

## Dark/Light Mode
  - The app provides a Dark/Light mode toggle feature, which allows users to switch between different color schemes based on their preference. When the app is opened, it checks if the user's system preferences are set to dark mode using the prefers-color-scheme media query. If dark mode is preferred, the app automatically sets the theme to dark. Otherwise, it uses the default light mode.
  
  - Users can manually toggle between dark and light mode by clicking the "Toggle Dark/Light Mode" button in the navigation bar. The selected mode is saved in localStorage, so the chosen theme will be applied on subsequent visits to the website.

## API Key
-  Please note that the app uses the News API to fetch news articles. The API key is provided as a constant variable in the script.js file. If you encounter any issues with API requests, ensure that the API key is valid and active.

## Credits
-  News API: https://newsapi.org/
-  Google Fonts: https://fonts.google.com/

## License
-  This project is licensed under the MIT License. Feel free to use, modify, and distribute the code as per the terms of the MIT License.
