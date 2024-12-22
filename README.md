# Swiss News 🇨🇭

A modern, responsive web application that displays the latest news from Switzerland using the SRF News Feed. The application is built with HTML, CSS, and JavaScript, featuring a clean and intuitive user interface with Swiss design elements.

## Features

- Real-time news feed from SRF (Schweizer Radio und Fernsehen)
- Responsive design that works across all device sizes
- Clean and modern UI with Swiss design elements
- Animated loading states and smooth transitions
- News cards with publication dates and direct links to full articles
- German language interface
- CORS-proxy implementation for reliable feed access

## Project Structure

```
.
├── Roadmap.txt
├── index.html
└── treetamer.sh
```

## Technical Details

### Dependencies

- Animate.css (4.1.1) - For smooth animations and transitions
- SRF News RSS Feed - Primary data source
- AllOrigins - CORS proxy service for fetching RSS feed

### Implementation

The application is built using:

- Semantic HTML5
- Modern CSS3 with CSS Variables and Flexbox/Grid
- Vanilla JavaScript with async/await for data fetching
- CSS animations and transitions for enhanced UX
- RSS feed parsing using DOMParser

### Key Components

- **Header**: Features an animated Swiss flag emoji and responsive title
- **News Grid**: Dynamically populated with news cards using CSS Grid
- **News Cards**: Individual articles with titles, descriptions, and metadata
- **Loading State**: Animated spinner during content fetch
- **Footer**: Copyright information and credits

## Getting Started

1. Clone the repository
2. Open `index.html` in a modern web browser
3. The application will automatically fetch and display the latest news

## Development

The project uses several modern web development features:

- CSS Custom Properties for theming
- CSS Grid for responsive layouts
- Fetch API for data retrieval
- Async/await for handling asynchronous operations

## Browser Support

The application supports all modern browsers including:

- Chrome
- Firefox
- Safari
- Edge

## Contributing

Currently tracked files:

- `index.html`

Files ignored in git:

- `Roadmap.txt`
- `tamed_tree/`
- `treetamer.sh`

## License

Copyright © 2024 Swiss News. All rights reserved.

## Credits

- Powered by SRF News Feed
- Developed by Swiss News Team
- Contact: contact@swissnews.ch
