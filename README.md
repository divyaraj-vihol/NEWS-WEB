# DVNews - News Aggregator Web Application

DVNews is a responsive news aggregator that fetches and displays current news articles from various categories using NewsAPI.

## Features

- Real-time news from NewsAPI
- Responsive design for all devices
- Category-based news browsing (Cricket, Tech, Food, etc.)
- Search functionality
- Clean, card-based UI
- Mobile-friendly navigation

## Installation

1. Clone the repository
2. Open `index.html` in any modern web browser
3. (Optional) Replace the API key in `script.js` with your own NewsAPI key

## Usage

1. Browse news by clicking on category buttons
2. Use the search bar to find specific news articles
3. Click on any article card to read the full story
4. On mobile devices, use the hamburger menu (☰) to access navigation

## API Key Note

The application includes a demo API key for NewsAPI. For production use:
1. Get your own API key from [NewsAPI.org](https://newsapi.org)
2. Replace the `API_KEY` constant in `script.js`

## File Structure

- `index.html` - Main HTML file
- `style.css` - All styling
- `script.js` - Main application logic

## Technologies Used

- HTML5
- CSS3 (Flexbox, Media Queries)
- JavaScript (ES6, Fetch API)
- [NewsAPI](https://newsapi.org) - News data source
- Font Awesome - Icons
- Google Fonts (Poppins) - Typography

## Known Issues

- Mobile search form has a duplicate ID attribute
- No error handling for failed API requests
- No loading indicators during API calls

## Future Improvements

- Implement error handling for API failures
- Add loading indicators
- Include pagination for news articles
- Add bookmarking functionality
- Implement dark mode

## License

This project is open source and available under the MIT License.
