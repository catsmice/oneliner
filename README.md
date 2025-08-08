# Oneliner

A modern, professional web tool for converting multi-line commands and text into clean, single-line format. Perfect for developers working with SQL queries, curl commands, shell scripts, and any multi-line text that needs to be converted to one-liners.

## 🚀 Features

### Dual Mode Support
- **Single Command Mode**: Convert one multi-line text block to a single line
- **Multiple Commands Mode**: Process multiple commands at once with intelligent splitting

### Intelligent Command Detection
- Automatically detects numbered commands (1. 2. 3. ...)
- Splits by double line breaks
- Recognizes common command prefixes (curl, psql, git, docker, etc.)

### Conversion Options
- ✅ **Preserve Spaces**: Keep single spaces between joined lines
- ✅ **Trim Whitespace**: Remove leading/trailing spaces from each line
- ⚙️ **Remove Comments**: Strip SQL-style comments (-- and /* */)
- ⚙️ **Compact Spaces**: Replace multiple spaces with single space

### Professional UI
- 🌙 **Dark/Light Theme**: Toggle between themes with persistent preference
- 📊 **Real-time Statistics**: Track lines, words, size reduction, and command count
- 📋 **Smart Copy Functions**: Copy individual commands or all at once
- ⌨️ **Keyboard Shortcuts**: Ctrl+Enter to copy, Ctrl+Shift+Delete to clear
- 📱 **Responsive Design**: Works perfectly on desktop and mobile

### Developer Experience
- Real-time conversion as you type
- Visual feedback with animations
- Toast notifications for actions
- Processing indicators
- Monospace font for code readability

## 🎯 Use Cases

### SQL Queries
```sql
-- Input:
SELECT * 
FROM users
WHERE age > 18
  AND status = 'active'

-- Output:
SELECT * FROM users WHERE age > 18 AND status = 'active'
```

### Curl Commands
```bash
# Input:
curl -X POST \
  http://localhost:3000/api/users \
  -H "Content-Type: application/json" \
  -d '{"name": "John", "age": 30}'

# Output:
curl -X POST http://localhost:3000/api/users -H "Content-Type: application/json" -d '{"name": "John", "age": 30}'
```

### Multiple Commands
Perfect for processing lists of commands like:
1. Database repair commands
2. API testing sequences
3. Deployment scripts
4. Monitoring checks

## 🛠️ Installation & Usage

### Option 1: Use Online (Recommended)
Visit the live demo: [https://catsmice.github.io/oneliner](https://catsmice.github.io/oneliner)

### Option 2: Run Locally
```bash
# Clone the repository
git clone https://github.com/catsmice/oneliner.git

# Navigate to the project directory
cd oneliner

# Open index.html in your browser
open index.html  # macOS
start index.html # Windows
xdg-open index.html # Linux
```

That's it! No build process or dependencies required.

## 🎮 How to Use

### Single Command Mode
1. Paste your multi-line text in the input area
2. See the real-time conversion in the output area
3. Adjust conversion options as needed
4. Click "Copy to Clipboard" or press Ctrl+Enter

### Multiple Commands Mode
1. Click "Multiple Commands" toggle
2. Paste multiple commands (numbered or separated by blank lines)
3. Each command gets its own one-liner output
4. Copy individual commands or use "Copy All Commands"

### Keyboard Shortcuts
- `Ctrl/Cmd + Enter`: Copy result(s) to clipboard
- `Ctrl/Cmd + Shift + Delete`: Clear all content

## 🧪 Examples

### Example 1: Database Commands
```
Input:
1. First, repair the GeneratedPost back-references:

curl -X POST http://localhost:3000/api/debug/repair-backlinks | jq '{success: 
.success, repaired: .data.summary.backLinksRepaired, processed: 
.data.summary.socialPostsProcessed}'

2. Verify the repair worked with psql:

psql "$DATABASE_URL" -c "SELECT COUNT(*) as empty_postid_count FROM 
\"GeneratedPost\" WHERE \"postId\" IS NULL OR \"postId\" = '';"

Output:
Command 1: curl -X POST http://localhost:3000/api/debug/repair-backlinks | jq '{success: .success, repaired: .data.summary.backLinksRepaired, processed: .data.summary.socialPostsProcessed}'

Command 2: psql "$DATABASE_URL" -c "SELECT COUNT(*) as empty_postid_count FROM \"GeneratedPost\" WHERE \"postId\" IS NULL OR \"postId\" = '';"
```

## 🏗️ Technical Details

- **Framework**: Pure HTML5, CSS3, and Vanilla JavaScript
- **No Dependencies**: Works without any external libraries
- **File Size**: < 50KB total
- **Browser Support**: All modern browsers (Chrome, Firefox, Safari, Edge)
- **Mobile Support**: Fully responsive design

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

### Development Setup
1. Fork the repository
2. Clone your fork: `git clone https://github.com/yourusername/oneliner.git`
3. Create a feature branch: `git checkout -b feature-name`
4. Make your changes and test them
5. Commit your changes: `git commit -m "Add some feature"`
6. Push to the branch: `git push origin feature-name`
7. Submit a pull request

### Reporting Issues
- Use GitHub Issues for bug reports and feature requests
- Provide clear steps to reproduce bugs
- Include browser version and operating system

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Inspired by the need for quick command formatting in development workflows
- Built with modern web standards and accessibility in mind
- Design inspired by contemporary developer tools

## 📊 Project Stats

![GitHub stars](https://img.shields.io/github/stars/catsmice/oneliner?style=social)
![GitHub forks](https://img.shields.io/github/forks/catsmice/oneliner?style=social)
![GitHub issues](https://img.shields.io/github/issues/catsmice/oneliner)
![GitHub license](https://img.shields.io/github/license/catsmice/oneliner)

---

**Made with ❤️ for developers who value clean, efficient code**