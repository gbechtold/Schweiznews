# 🇨🇭 Swiss News RSS Reader

A modern, award-worthy RSS reader specifically designed for Swiss news sources, featuring a clean, Swiss-inspired design aesthetic and real-time updates.

## 🌟 Features

- **Swiss Design Philosophy**: Embraces minimalist Swiss design principles with precise typography and grid layouts
- **Real-Time Updates**: Automatically fetches and refreshes news content every 5 minutes
- **Responsive Layout**: Adapts seamlessly to all screen sizes and devices
- **Interactive Elements**: Smooth animations and transitions for enhanced user experience
- **Category Visualization**: Intuitive emoji indicators for different news categories
- **Error Handling**: Graceful error management with retry capabilities
- **Cross-Origin Support**: Built-in CORS proxy for reliable RSS feed fetching

## 🚀 Quick Start

1. Clone this repository:

   ```bash
   git clone https://github.com/yourusername/swiss-news-reader.git
   cd swiss-news-reader
   ```

2. Open `index.html` in your web browser:
   - Double-click the file
   - Or serve it using a local server:
     ```bash
     python -m http.server 8000
     # Then visit http://localhost:8000
     ```

## 📐 Technical Architecture

### Core Components

- **RSS Feed Fetcher**: Uses the AllOrigins CORS proxy to fetch RSS feeds
- **XML Parser**: Converts RSS XML to structured JavaScript objects
- **Dynamic Grid System**: CSS Grid-based responsive layout
- **Category Manager**: Emoji mapping system for visual category representation

### Styling

- **Colors**: Swiss-inspired color palette (red: #FF0000, white: #FFFFFF)
- **Typography**: Uses Inter font family for optimal readability
- **Animations**: CSS transitions and keyframe animations for loading states
- **Responsive Design**: Flexbox and CSS Grid for adaptive layouts

## 🔧 Customization

### Modifying RSS Sources

To change the RSS feed source, update the `RSS_URL` constant in the JavaScript:

```javascript
const RSS_URL = 'your-new-rss-url';
```

### Adding New Categories

Add new category-emoji mappings in the `getEmoji` function:

```javascript
const emojiMap = {
  YourCategory: '🆕',
  // ... existing categories
};
```

### Styling Changes

The main styling variables are defined in the CSS `:root` selector:

```css
:root {
  --swiss-red: #ff0000;
  --swiss-white: #ffffff;
  /* Add your custom variables here */
}
```

## 🔄 Auto-Refresh Configuration

The default refresh interval is 5 minutes. To modify this, update the `setInterval` value:

```javascript
// Change 300000 (5 minutes) to your desired interval in milliseconds
setInterval(initializeNewsApp, 300000);
```

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)

## ⚠️ Known Limitations

- RSS feed must support CORS or be accessed through a proxy
- Some RSS feeds might have different XML structures requiring parser adjustments
- Heavy animations might affect performance on low-end devices

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments

- SRF for providing the RSS feed
- Inter font family by Rasmus Andersson
- AllOrigins for CORS proxy service

## 📮 Contact

For questions and support, please open an issue in the GitHub repository.

---

Made with ❤️ for Switzerland 🇨🇭
