# Prompt Manager - AI Prompts Organizer

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

A powerful web application for organizing, categorizing, and managing AI prompts. Built with Tailwind CSS and vanilla JavaScript, this tool helps you store, search, and reuse your favorite prompts across different AI platforms.

## 🌟 Features

### 🚀 Core Functionality
- **Prompt Management**: Create, edit, and delete AI prompts with ease
- **Smart Categorization**: Organize prompts into customizable categories
- **Advanced Search**: Find prompts by title, content, or tags
- **Multiple Sort Options**: Sort by title, category, or date
- **Dark/Light Mode**: Toggle between themes for comfortable usage

### 📁 Data Management
- **Local Storage**: All data persists in your browser
- **Import/Export**: Backup and restore your prompts via JSON files
- **Category System**: Fully customizable categories with color coding
- **Tag System**: Add multiple tags to each prompt for better organization

### 🎨 User Experience
- **Responsive Design**: Works perfectly on desktop and mobile devices
- **Clean Interface**: Intuitive and modern UI built with Tailwind CSS
- **Quick Actions**: Copy prompts to clipboard with one click
- **Real-time Filtering**: Instant search and filtering results

## 🏗️ Project Structure

```
prompt-manager/
├── index.html          # Main application file
├── README.md          # Project documentation
```

## 🚀 Quick Start

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No additional dependencies required!

### Installation & Usage

1. **Download the Application**
   ```bash
   # Clone the repository or download the HTML file
   git clone https://github.com/brunofullstack/prompt-manager.git
   ```

2. **Run the Application**
   - Open `index.html` in your web browser
   - That's it! No server setup required

3. **Start Using**
   - Add your first prompt using the form on the left
   - Create custom categories for better organization
   - Use search and filters to find prompts quickly

## 💡 How to Use

### Adding Prompts
1. Fill in the prompt title
2. Select or create a category
3. Write your prompt text
4. Add relevant tags (comma-separated)
5. Click "Add Prompt"

### Managing Categories
1. Click the gear icon (⚙️) next to the category dropdown
2. Add new categories with custom names and colors
3. Edit or delete existing categories
4. Categories are automatically saved

### Importing/Exporting Data
- **Export**: Click "Export to JSON" to download all your data
- **Import**: Use "Import from JSON" to restore from backup
- Data includes both prompts and categories

### Searching and Filtering
- Use the search bar to find prompts by content
- Filter by specific categories
- Sort by different criteria (title, date, category)

## 📊 Default Categories

The app comes with pre-defined categories:
- **General**: All-purpose prompts
- **Server Configuration**: System and server setup prompts
- **Content Creation**: Writing and content generation
- **Data Analysis**: Data processing and analysis
- **Programming**: Code-related prompts
- **Design**: UI/UX and design prompts

## 🛠️ Technical Details

### Built With
- **Tailwind CSS** - Modern utility-first CSS framework
- **Vanilla JavaScript** - No external dependencies
- **Font Awesome** - Beautiful icons
- **Local Storage API** - Data persistence

### Browser Compatibility
- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

### Data Structure
```json
{
  "prompts": [
    {
      "id": "unique-id",
      "title": "Prompt Title",
      "category": "category-id",
      "prompt": "Full prompt text",
      "tags": ["tag1", "tag2"],
      "date": "2023-12-01T10:30:00.000Z"
    }
  ],
  "categories": [
    {
      "id": "category-id",
      "name": "Category Name",
      "color": "blue"
    }
  ]
}
```

## 🔧 Customization

### Adding New Category Colors
Edit the `getCategoryColorClass()` and `getCategoryColorClassForBadge()` functions in the JavaScript to add new color options.

### Modifying Default Categories
Update the `categories` array in the JavaScript initialization to change default categories.

## 📱 Mobile Support

The application is fully responsive and works on:
- Desktop computers
- Tablets
- Mobile phones
- Touch-enabled devices

## 🔒 Data Privacy

- All data is stored locally in your browser
- No data is sent to external servers
- You have full control over your data
- Export/import functionality for backups

## 🐛 Troubleshooting

### Common Issues

1. **Data not saving**
   - Check if localStorage is enabled in your browser
   - Ensure you're not in private/incognito mode

2. **Import not working**
   - Verify the JSON file format is correct
   - Check browser console for error messages

3. **Categories not displaying**
   - Try refreshing the page
   - Check if categories exist in localStorage

### Getting Help
- Check the browser console for error messages
- Ensure you're using a supported browser
- Verify JSON file structure when importing

## 🤝 Contributing

Contributions are welcome! Please feel free to submit pull requests or open issues for bugs and feature requests.

### Development
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments

- **Tailwind CSS** for the amazing utility-first CSS framework
- **Font Awesome** for the beautiful icons
- **All contributors** who help improve this project

---

**Happy Prompting!** 🚀

If you find this tool useful, please consider giving it a star ⭐ on GitHub!

## 📞 Support

If you need help or have questions:
1. Check this README first
2. Open an issue on GitHub
3. Check existing issues for solutions

---

<div align="center">

**Made with ❤️ for the AI community**

</div>