# YouTube Bookmarker

A powerful Chrome extension for bookmarking and organizing YouTube video timestamps with advanced features like categories, search, and export capabilities.

## 📸 Preview

![YouTube Bookmarker Preview](assets/thumbnail.png)

*Screenshot showing the extension popup with bookmarks, categories, and search functionality*

## 🚀 Features

### Core Functionality
- **Timestamp Bookmarking**: Save important moments in YouTube videos with one click
- **Smart Organization**: Organize bookmarks by categories for easy management
- **Real-time Search**: Find bookmarks quickly with powerful search functionality
- **Multiple Views**: Choose from List, Grid, or Compact view modes
- **Progress Bar Indicators**: Visual bookmark markers on the video progress bar

### Advanced Features
- **Category Management**: Create, edit, and delete custom categories
- **Data Export**: Export bookmarks in CSV and JSON formats
- **Cross-video Management**: Manage bookmarks across multiple videos
- **Responsive Design**: Clean, modern interface that works on all screen sizes
- **Real-time Updates**: Instant synchronization across all features

### User Experience
- **Easy Navigation**: Click progress bar indicators to jump to bookmarks
- **Visual Feedback**: Hover effects and tooltips for better interaction
- **Badge Counters**: See bookmark counts at a glance
- **Keyboard Shortcuts**: Efficient bookmark management

## 📦 Installation

### From Chrome Web Store (Recommended)
1. Visit the Chrome Web Store
2. Search for "YouTube Bookmarker"
3. Click "Add to Chrome"
4. Confirm the installation

### Manual Installation (Developer Mode)
1. Download or clone this repository
2. Open Chrome and go to `chrome://extensions/`
3. Enable "Developer mode" in the top right
4. Click "Load unpacked" and select the extension folder
5. The extension will appear in your extensions list

## 🎯 How to Use

### Adding Bookmarks
1. Navigate to any YouTube video
2. Click the bookmark button (📖) in the video player controls
3. The current timestamp will be saved automatically
4. Add descriptions to bookmarks from the popup

### Managing Bookmarks
1. Click the extension icon in your toolbar
2. Use the popup to view, edit, and organize bookmarks
3. Switch between different view modes (List/Grid/Compact)
4. Search through your bookmarks using the search bar

### Organizing with Categories
1. Click "Manage Categories" to create custom categories
2. Assign categories to videos and bookmarks
3. Filter bookmarks by category using the category chips
4. Export organized data in your preferred format

### Progress Bar Navigation
1. Look for red indicators on the video progress bar
2. Hover over indicators to see bookmark details
3. Click any indicator to jump to that timestamp
4. Visual feedback shows bookmark positions at a glance

## 🛠️ Technical Details

### Architecture
- **Manifest V3**: Modern Chrome extension architecture
- **Content Scripts**: Seamless YouTube page integration
- **Chrome Storage API**: Persistent data storage
- **Message Passing**: Secure communication between components

### File Structure
```
youtube-bookmarker/
├── manifest.json          # Extension configuration
├── popup.html            # Main popup interface
├── popup.js              # Popup functionality
├── popup.css             # Popup styling
├── contentScript.js      # YouTube page integration
├── background.js         # Background service worker
├── utils.js              # Utility functions
├── assets/               # Icons and images
│   ├── ext-icon.png      # Extension icon
│   ├── bookmark.svg      # Bookmark icon
│   └── ...               # Other assets
└── README.md             # This file
```

### Storage Keys
- `youtube_bookmarks`: Main bookmark data
- `youtube_bookmarks_categories`: Category definitions
- `youtube_bookmarks_preferred_view`: User's preferred view mode

## 🔧 Development

### Prerequisites
- Google Chrome browser
- Basic knowledge of HTML, CSS, and JavaScript
- Chrome extension development concepts

### Local Development
1. Clone the repository:
   ```bash
   git clone https://github.com/santushdebnath/youtube-bookmarker.git
   cd youtube-bookmarker
   ```

2. Load in Chrome:
   - Open `chrome://extensions/`
   - Enable Developer mode
   - Click "Load unpacked" and select the project folder

3. Make changes and reload the extension

### Building for Distribution
1. Ensure all features work correctly
2. Test on different YouTube pages
3. Update version in `manifest.json`
4. Create a ZIP file for distribution

## 📱 Browser Compatibility

- **Chrome**: Full support (primary target)
- **Edge**: Full support (Chromium-based)
- **Opera**: Full support (Chromium-based)
- **Brave**: Full support (Chromium-based)

## 🤝 Contributing

We welcome contributions! Here's how you can help:

### Reporting Issues
1. Check existing issues first
2. Create a new issue with detailed description
3. Include steps to reproduce the problem
4. Specify your browser and OS version

### Suggesting Features
1. Open a feature request issue
2. Describe the desired functionality
3. Explain the use case and benefits
4. Provide mockups if possible

### Code Contributions
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Santush Deb Nath**
- GitHub: [@santushdebnath](https://github.com/santushdebnath)
- Project: [YouTube Bookmarker](https://github.com/santushdebnath/youtube-bookmarker)

## 🙏 Acknowledgments

- YouTube for providing the platform
- Chrome Extensions API for the development framework
- Open source community for inspiration and tools

## 📞 Support

- **GitHub Issues**: [Report bugs or request features](https://github.com/santushdebnath/youtube-bookmarker/issues)
- **Documentation**: Check this README and code comments
- **Community**: Join discussions in GitHub discussions

## 🔄 Changelog

### Version 1.0.0
- Initial release with core bookmarking functionality
- Category management system
- Search and filtering capabilities
- Multiple view modes (List, Grid, Compact)
- Progress bar bookmark indicators
- CSV and JSON export functionality
- Real-time badge counters
- Responsive design and modern UI

---

**Made with ❤️ for YouTube content creators and learners**
