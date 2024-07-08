# Blogit (dynamic blog website)

This project is a dynamic blog website that fetches data from an external API and implements pagination to display blog articles based on the selected page number.

## Features

- **Dynamic Content**: Articles are fetched dynamically from an external API ([News API](https://newsapi.org/)) based on user interactions.
  
- **Pagination**: Allows users to navigate through multiple pages of articles.
  
- **Responsive Design**: Ensures optimal viewing experience across various devices.

## Technologies Used

- HTML5
- CSS3 (or CSS framework like Bootstrap)
- JavaScript (ES6+)

## APIs Used

- [News API](https://newsapi.org/): Provides news articles data based on search queries.

## Setup Instructions

To run this project locally:

1. Clone the repository:

   ```bash
   git clone https://github.com/dev-omaFrank/blogit
   ```

2. Navigate to the project directory:

   ```bash
   cd blogit
   ```

3. Open `index.html` in your web browser to view the website locally.

## Usage

- Upon loading the website, articles are fetched and displayed on the homepage.
- Navigate through different pages using the pagination buttons to view more articles.

  
## Implementation Details

- **Fetching Data**: Uses JavaScript `fetch()` API to retrieve articles from the News API based on specified parameters (e.g., search query, page number, page size).
  
- **Pagination Logic**: Calculates total pages based on the number of articles fetched and the desired page size. Updates the UI dynamically to display pagination buttons accordingly.

- **Event Handling**: Clicking on a pagination button triggers an event listener that updates the `page` variable and fetches articles for the selected page.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please fork the repository and create a pull request with your changes.

## Contact

For questions or feedback, please contact:

- Franklyn Nmesoma
- Email: sayhellotodevops@gmail.com
- GitHub: [Dev OmaFrank](https://github.com/dev-omaFrank)
