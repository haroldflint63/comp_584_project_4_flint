# Star Wars Search

A web-based search application for exploring Star Wars universe data. This project allows users to search and discover information about characters, planets, starships, and more from the Star Wars universe.

## Table of Contents

- [About](#about)
- [Features](#features)
- [How to Use](#how-to-use)
- [Accessing via GitHub Pages](#accessing-via-github-pages)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)

## About

Star Wars Search is an interactive web application that leverages the Star Wars API (SWAPI) to provide comprehensive search functionality for Star Wars universe data. Whether you're a casual fan or a dedicated enthusiast, this tool makes it easy to find detailed information about your favorite characters, planets, vehicles, and more.

## Features

- **Multi-Category Search**: Search across multiple categories including:
  - Characters (People)
  - Planets
  - Starships
  - Vehicles
  - Films
  - Species

- **Real-Time Search**: Instant search results as you type with responsive filtering

- **Detailed Information**: View comprehensive details about each search result

- **Responsive Design**: Mobile-friendly interface that works on all devices

- **User-Friendly Interface**: Clean and intuitive design for easy navigation

- **Star Wars API Integration**: Powered by the comprehensive Star Wars API (SWAPI)

## How to Use

### Local Development

1. **Clone the Repository**
   ```bash
   git clone https://github.com/haroldflint63/comp_584_project_4_flint.git
   cd comp_584_project_4_flint
   ```

2. **Open the Application**
   - Open `index.html` in your web browser, or
   - Use a local server:
     ```bash
     python -m http.server 8000
     # Then navigate to http://localhost:8000
     ```

3. **Search for Content**
   - Select a category from the dropdown menu
   - Type in the search box to find characters, planets, or other Star Wars entities
   - Click on results to view detailed information

### Features in Detail

- **Category Selection**: Use the dropdown menu to select the type of content you want to search for
- **Search Input**: Enter keywords in the search box to filter results in real-time
- **Results Display**: Browse through the results and click for more details
- **Information Panel**: View comprehensive details about selected items

## Accessing via GitHub Pages

This project is hosted on GitHub Pages and can be accessed directly from your browser without any local setup.

**Live Application URL:**
```
https://haroldflint63.github.io/comp_584_project_4_flint/
```

Simply visit the link above to start using the Star Wars Search application immediately!

### GitHub Pages Deployment

The application is automatically deployed to GitHub Pages from the main branch. Any updates pushed to the repository will be reflected on the live site within a few minutes.

## Technologies Used

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **API**: Star Wars API (SWAPI) - https://swapi.dev/
- **Hosting**: GitHub Pages
- **Version Control**: Git & GitHub

## Project Structure

```
comp_584_project_4_flint/
├── index.html          # Main application file
├── style.css          # Application styling
├── script.js          # Application logic
├── README.md          # This file
└── assets/            # Additional resources (if any)
```

## API Reference

The application uses the **Star Wars API (SWAPI)** at https://swapi.dev/

### Supported Endpoints:
- `/people/` - Character information
- `/planets/` - Planet data
- `/starships/` - Starship specifications
- `/vehicles/` - Vehicle details
- `/films/` - Film information
- `/species/` - Species data

## Tips for Best Results

1. Use specific character or planet names for most accurate results
2. Try partial names or words if you're unsure of the exact spelling
3. Explore different categories to discover new information
4. Check out multiple results to compare details

## Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Troubleshooting

**Search returns no results:**
- Try shortening your search term
- Use different keywords
- Check the selected category matches what you're searching for

**Page not loading:**
- Ensure you have a stable internet connection (API requires internet access)
- Clear your browser cache and reload the page
- Try a different browser

## Future Enhancements

- Add favorite/bookmark functionality
- Implement advanced filtering options
- Add data export capabilities
- Create comparison tools for characters and items

## License

This project is created for educational purposes as part of a coursework assignment.

## Author

**Harold Flint**

## Feedback & Support

For issues, suggestions, or feedback, please open an issue on the [GitHub repository](https://github.com/haroldflint63/comp_584_project_4_flint/issues).

---

**Last Updated**: December 2025

Enjoy exploring the Star Wars universe! 🌟
