# News Check: Journalistic Writing Assistant

An AI-powered web application that analyzes text for journalistic quality, helping writers create better news articles and press releases.

![News Check Screenshot](https://via.placeholder.com/800x400/4f46e5/ffffff?text=News+Check+Demo)

## 🚀 Features

- **📖 Readability Analysis** - Flesch-Kincaid grade level scoring to ensure accessibility
- **✏️ Grammar & Style Check** - Detects passive voice and weak word usage
- **❓ 5 W's Analysis** - Ensures Who, What, When, Where, Why/How are covered
- **⚖️ Bias Detection** - Identifies loaded language and promotional words
- **📰 Buried Lede Check** - Verifies the most important information leads the story

## 🎯 Use Cases

- **Journalists** - Check article quality before publication
- **PR Professionals** - Review press releases for clarity and objectivity
- **Students** - Learn journalistic writing principles
- **Editors** - Provide consistent feedback criteria
- **Content Writers** - Ensure clarity and neutrality

## 🔧 How It Works

1. **Paste your text** into the textarea
2. **Click "Analyze Text"** to run comprehensive checks
3. **Review the report cards** with specific feedback and suggestions
4. **Implement improvements** based on the recommendations

## 📊 Analysis Modules

### Readability Analysis
Uses the Flesch-Kincaid formula to determine grade level complexity. Aims for Grade 8-12 for broad accessibility.

### Grammar & Style
- Identifies passive voice constructions
- Flags weak modifier words (very, really, just, etc.)
- Provides specific examples and alternatives

### Missing Information (5 W's)
Scans the opening paragraphs for essential journalistic elements:
- **Who** - People involved
- **What** - What happened
- **When** - Time/date information
- **Where** - Location details
- **Why/How** - Cause or method

### Bias Detection
Identifies subjective language that could compromise objectivity:
- Loaded adjectives (amazing, shocking, tragic)
- Promotional language
- Emotional modifiers

### Buried Lede Analysis
Sophisticated algorithm that scores sentences for newsworthiness to ensure the most important information appears first.

## 🛠️ Technologies

- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **Styling**: Tailwind CSS
- **Typography**: Inter font family
- **Deployment**: GitHub Pages
- **Dependencies**: None (runs entirely in browser)

## 🚦 Getting Started

Simply open the application in any modern web browser - no installation required!

## 📝 Usage Example

```
Input: "The company announced yesterday that they had achieved amazing results in their groundbreaking research project."

Analysis Results:
✅ Readability: Grade 12 (Good)
⚠️ Grammar: Passive voice detected ("had achieved")
⚠️ Bias: Loaded words found ("amazing", "groundbreaking")
✅ 5 W's: 4/5 found (missing specific location)
✅ Lede: Clear and direct
```

## 🤝 Contributing

Found a bug or have a suggestion? Feel free to open an issue or submit a pull request!

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🔗 Live Demo

[Try News Check →](https://yourusername.github.io/news-check)

---

**Built with ❤️ for better journalism**
